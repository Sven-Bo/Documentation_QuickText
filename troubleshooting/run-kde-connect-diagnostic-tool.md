# Run KDE Connect Diagnostic Tool

### Video Tutorial

{% embed url="https://iframe.mediadelivery.net/play/289332/a9f671f5-9ee8-4694-a944-4c351f072073" %}

**How to use:**

1. [Download kde\_connect\_diagnostic.bat](https://github.com/Sven-Bo/quicktext_kde_connect_cli_diagnostic_tool/blob/main/kde_connect_diagnostic.bat)
2. Right-click the downloaded file, select Properties, and unblock it if needed.
3. Double-click the `kde_connect_diagnostic.bat` file to run it.
4. Share the diagnostic results (log file) with QuickText support.

***

### Fix 1: Enable App Execution Aliases

{% embed url="https://iframe.mediadelivery.net/play/289332/5b8be44f-64c4-4277-832e-ac9f6ee5d448" %}

Windows Store apps use execution aliases that need to be enabled.

1. Open **Settings**
2. Navigate to **Apps** → **Advanced app settings** → **App execution aliases**
3. Scroll down and find **KDE Connect**
4. Ensure the toggle is **ON** (enabled)

<figure><img src="../.gitbook/assets/image (19) (1).png" alt=""><figcaption></figcaption></figure>

***

### Fix 2: Add Windows App Path to Environment Variables

{% embed url="https://iframe.mediadelivery.net/play/289332/fda6a521-08bb-4cee-8269-f7bc6c17a2f1" %}

#### Step-By-Step Instructions

1. Press **Win + R**, type `sysdm.cpl`, and press **Enter**\
   ![](<../.gitbook/assets/image (17) (1).png>)
2. Click the **Advanced** tab
3. Click the **Environment Variables** button
4. Under **User variables for \<username>**, find and select **Path**
5. Click **Edit**
6.  Check if the following path already exists:\\

    ```
    %USERPROFILE%\AppData\Local\Microsoft\WindowsApps
    ```
7. If it doesn't exist, click **New** and add the path\
   ![](<../.gitbook/assets/image (18) (1).png>)
8. Click **OK** on all dialogs to save changes

{% hint style="warning" %}
**After all steps: Restart your compute**r and run the diagnostic tool again
{% endhint %}

***

### Fix 3: Use KDE Connect Desktop Installer

{% embed url="https://iframe.mediadelivery.net/play/289332/3fd24a19-5cb3-4a74-ab93-7f524f747fe3" %}

#### Step-By-Step Instructions

**Uninstall the Windows Store Version**

1. Click the **Start** button or press the **Windows key**
2. Type **KDE Connect** in the search bar
3. Right-click on **KDE Connect** in the search results
4. Select **Uninstall**
5. Confirm the uninstallation

**Install the Desktop Version**

1. Go to [kdeconnect.kde.org/download.html](https://kdeconnect.kde.org/download.html)
2. Download the Windows installer
3. Run the installer and follow the installation steps

**Add KDE Connect to Environment Variables**

After installing the desktop version, you need to add it to your PATH:

1. Press **Win + R**, type `sysdm.cpl`, and press **Enter**
2. Click the **Advanced** tab
3. Click the **Environment Variables** button
4. Under **User variables for \<username>**, find and select **Path**
5. Click **Edit**
6. Click **New**
7.  Add the path:\\

    ```
    C:\Program Files\KDE Connect\bin
    ```
8. Click **OK** on all dialogs to save changes\
   ![](<../.gitbook/assets/image (2) (1) (2).png>)

{% hint style="warning" %}
**After all steps: Restart your compute**r and run the diagnostic tool again
{% endhint %}
