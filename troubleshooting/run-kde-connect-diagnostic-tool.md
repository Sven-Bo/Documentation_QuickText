# Run KDE Connect Diagnostic Tool

### Video Tutorial

Coming Soon!

**How to use:**

1. [Download kde\_connect\_diagnostic.bat](https://raw.githubusercontent.com/Sven-Bo/quicktext_kde-connect-cli-diagnostic-tool/main/kde_connect_diagnostic.bat)
2. Double-click the downloaded kde\_connect\_diagnostic.bat file
3. Review the diagnostic results
4. Follow the appropriate fix below based on the results

### Common Fixes

Based on the diagnostic results, here at the common fixes:

<details>

<summary>Fix 1: Enable App Execution Aliases</summary>

Windows Store apps use execution aliases that need to be enabled.

1. Open **Settings**
2. Navigate to **Apps** → **Advanced app settings** → **App execution aliases**
3. Scroll down and find **KDE Connect**
4. Ensure the toggle is **ON** (enabled)

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary>Fix 2: Add Windows App Path to Environment Variables</summary>

### Video Tutorial

Coming Soon!

***

### Step-By-Step Instructions

1. Press **Win + R**, type `sysdm.cpl`, and press **Enter**\
   &#x20;![](<../.gitbook/assets/image (20).png>)
2. Click the **Advanced** tab
3. Click the **Environment Variables** button
4. Under **User variables for \<username>**, find and select **Path**
5. Click **Edit**
6.  Check if the following path already exists:\


    ```
    %USERPROFILE%\AppData\Local\Microsoft\WindowsApps
    ```
7. If it doesn't exist, click **New** and add the path\
   ![](<../.gitbook/assets/image (21).png>)
8. Click **OK** on all dialogs to save changes

{% hint style="warning" %}
**After all steps: Restart your compute**r and run the diagnostic tool again
{% endhint %}

</details>

<details>

<summary>Use KDE Connect Desktop Installer</summary>

### Video Tutorial

Coming Soon!

***

### Step-By-Step Instructions

#### **Uninstall the Windows Store Version**

1. Click the **Start** button or press the **Windows key**
2. Type **KDE Connect** in the search bar
3. Right-click on **KDE Connect** in the search results
4. Select **Uninstall**
5. Confirm the uninstallation

#### **Install the Desktop Version**

1. Go to [kdeconnect.kde.org/download.html](https://kdeconnect.kde.org/download.html)
2. Download the Windows installer
3. Run the installer and follow the installation steps

#### **Add KDE Connect to Environment Variables**

After installing the desktop version, you need to add it to your PATH:

1. Press **Win + R**, type `sysdm.cpl`, and press **Enter**
2. Click the **Advanced** tab
3. Click the **Environment Variables** button
4. Under **User variables for \<username>**, find and select **Path**
5. Click **Edit**
6. Click **New**
7.  Add the path:\


    ```
    C:\Program Files\KDE Connect\bin
    ```
8. Click **OK** on all dialogs to save changes\
   ![](<../.gitbook/assets/image (22).png>)

{% hint style="warning" %}
**After all steps: Restart your compute**r and run the diagnostic tool again
{% endhint %}

</details>

