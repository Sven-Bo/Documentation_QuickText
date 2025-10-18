# "KDE Connect is sending a large number of SMS messages" Popup

<div align="left"><figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt="" width="456"><figcaption><p>Popup - KDE Connect is sending a large number of SMS messages</p></figcaption></figure></div>

### **What this message means**

Android shows this warning when an app tries to send many SMS messages in a short time. It’s a built-in security feature to prevent apps from sending messages in the background without your consent. This protects you from unexpected charges and helps avoid network congestion.

When QuickText (powered by KDE Connect) sends many messages quickly, your phone may display this popup:

> **"KDE Connect is sending a large number of SMS messages. Do you want to allow this app to continue sending messages?"**

You’ll need to tap **Allow** to continue sending.

### **How to reduce the chance of this popup**

Add delays between messages to stay under Android’s detection limits.

I recommend:

* **4 seconds** fixed delay
* **Random delay between 1 and 2 seconds**

You can set both in the **Settings** tab (see screenshot below). This helps throttle message sending to a more natural pace and may prevent this warning from appearing again.

<div align="left"><figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt="" width="341"><figcaption></figcaption></figure></div>

