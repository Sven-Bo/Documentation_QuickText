# Resolve Connection Issue

<details>

<summary><strong>No device found. Please check KDE Connect on your phone.</strong></summary>

This means your phone is not detected at all. Most of the time, KDE Connect isn’t running on the phone, or the phone is on a different network.

**✅ Steps to fix:**

1. **Make sure KDE Connect is installed on your phone**\
   If it’s not installed, download it from the Play Store and open the app.
2. **Connect both devices to the same Wi-Fi**\
   Mobile data won't work. Your phone and computer must be on the same Wi-Fi network.
3. **Open KDE Connect on your phone**\
   Once open, it should start scanning for nearby devices.
4.  **Click "Refresh Devices" in KDE Connect Desktop**\
    Your phone should now appear in the list.\


    <figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
5. **Pair your devices**
   * Select your phone on the left panel and click **Pair**
   *   On your phone, tap **Accept** when the request appears\


       <figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

You should now see **Device trusted and connected** in KDE Connect. Go back to Excel and click **Connect Your Phone** to confirm everything works.\


<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
If you’ve done all the steps above and your phone still isn’t found, there may be an issue with your KDE Connect installation. Please run the KDE Connect Diagnostic Tool to check what’s going wrong:\
[https://docs.pythonandvba.com/quicktext/troubleshooting/run-kde-connect-diagnostic-tool](https://docs.pythonandvba.com/quicktext/troubleshooting/run-kde-connect-diagnostic-tool)

Once you’ve run the tool, email me the logfile. The video on the page shows exactly how to do this.
{% endhint %}

</details>

<details>

<summary><strong>Device is paired but not reachable.</strong></summary>

This usually means the KDE Connect app on your phone has stopped running or cannot be reached.

**✅ Steps to fix:**

1. **Check if KDE Connect is running**\
   Open the KDE Connect app on your phone. If it’s not running, start it manually.
2. **Disable battery-saving mode**\
   Battery optimization can stop background apps like KDE Connect. In your phone settings, exclude KDE Connect from battery-saving features. [Learn how to disable it here.](../how-to-disable-battery-saving-for-kde-connect.md)
3. **Make sure both devices are on the same Wi-Fi**\
   Your phone and your computer must be connected to the same Wi-Fi network. Mobile data won’t work.

After doing the steps above, click the **Test Connection** button to check if your phone is now reachable.

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><strong>Device is reachable but not paired.</strong></summary>

KDE Connect sees your device, so both the phone and computer are on the same Wi-Fi and have KDE Connect installed. The only thing missing is permission to let them talk to each other — pairing.

**✅ Steps to fix:**

1.  **Open KDE Connect on your computer**\
    Your phone should show up as available. Select it and click the **Pair** button.\


    <figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>
2. **Check your phone**\
   You’ll get a pairing request in the KDE Connect app. Tap **Accept** to confirm.\
   ![](<../.gitbook/assets/image (3).png>)
3.  **Connection confirmed**\
    After pairing, the status should change to **Device trusted and connected** on the desktop app.\


    <figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Now go back to Excel and click **Test Connection** to confirm everything is working.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><strong>Error checking KDE Connect installation: ERROR: Permission denied</strong></summary>

This error usually means your antivirus or **firewall is blocking QuickText**.

Some antivirus or firewall tools can falsely flag QuickText as a risk, even though there is nothing harmful inside. Well-known programs like Kaspersky and Windows Defender show it as safe.\
See more details here: [Antivirus or Firewall Warning / False Positive](https://docs.pythonandvba.com/quicktext/troubleshooting/antivirus-or-firewall-warning-false-positive)

**What you can do:**

* Temporarily turn off your antivirus or firewall and run QuickText again.
* Or, add QuickText as an exception (whitelist it) in your antivirus or firewall settings.

{% hint style="info" %}
If this solves the issue, please [send me a quick email (contact@pythonandvba.com)](mailto:contact@pythonandvba.com?subject=QuickText%20-%20Antivirus%20False%20Positive\&body=Hi%20Sven%2C%0A%0AI%20ran%20into%20a%20'Permission%20denied'%20error%20and%20found%20out%20it%20was%20my%20antivirus%20or%20firewall.%20I%20wanted%20to%20let%20you%20know%20I%20am%20using%20%5Bname%20of%20antivirus%2Ffirewall%5D.%0A%0AThanks%2C%0A%5Byour%20name%5D) and let me know which antivirus or firewall software you are using. I’ll reach out to them to fix the false positive, so you (and others) won’t need to whitelist QuickText in the future.
{% endhint %}

</details>

