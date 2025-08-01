# Windows Defender Blocking QuickText (ASR Rule)

If you see this message from Windows Security:

<div align="left"><figure><img src="../.gitbook/assets/ff-2f9d2bc7153e7799c2e7d61581a445f8-ff-2025-07-31-13_04_39-Windows-Security.png" alt=""><figcaption></figcaption></figure></div>

**What’s going on?**\
Windows Defender has a security rule (“Attack surface reduction”) that blocks Excel from running background commands. This stops QuickText from sending SMS.

**How to fix it:**\
You have two options:

**Option 1: Enable “Bypass ASR” in QuickText (quick fix)**

* Open QuickText
* Go to Settings > Advanced Settings
* Set “Bypass ASR” to **Enabled**
* Save the settings

<div align="left"><figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
_Note: This option is the quickest and doesn’t require changing your Windows security settings. However, it may add a small delay (a few seconds) each time you send an SMS._
{% endhint %}

**Option 2: Disable the Defender Rule (permanent fix for admins)**\
If you have admin rights, you can turn off just this security rule:

* Open PowerShell **as administrator**
*   Run this command:

    ```
    Set-MpPreference -AttackSurfaceReductionRules_Ids D4F940AB-401B-4EFC-AADC-AD5F3C50688A -AttackSurfaceReductionRules_Actions Disabled
    ```

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

_This will remove the block and allow QuickText to send SMS without any added delay._
