# SMS Not Sending: Quick Troubleshooting

If your SMS messages are not being sent, follow these steps:

#### 1. Do you see an error in the status column?

* If **yes**, what does the error say?
  * If it says **"Access denied"**: Your firewall or antivirus is blocking QuickText. Please turn off your antivirus/firewall or add an exception for QuickText, then try again.
  * If it’s a different error: Copy the error and email it to me at sven@pythonandvba.com.

***

#### 2. Are the messages marked as transmitted, but not visible in your SMS app?

* This usually means the connection to your phone was lost.
* Make sure the KDE Connect app stays open on your phone while you send messages. Don’t close or swipe away the app during sending.

Also, please check that KDE Connect has permission to send SMS:

* Open the KDE Connect app on your phone.\
  If you see “Send SMS” with a warning icon, tap it and grant permission.\
  ![](<../.gitbook/assets/image (4) (1) (1).png>)
* In your phone’s Settings → Apps → KDE Connect → Permissions, make sure both **Notifications** and **SMS** are allowed.\
  ![](<../.gitbook/assets/image (1) (1) (1) (1) (1).png>)
* On your PC, open the KDE Connect desktop app and go to **Plugin Settings**. Ensure **Send and receive SMS** and **Ping** are ticked.\
  ![](<../.gitbook/assets/image (23).png>)

***

#### 3. Do you see the messages in your SMS app, but the recipient doesn’t get them?

* Your phone provider may have blocked your number for bulk sending.
* More info and what you can do:\
  [SMS is marked as sent on my phone, but the recipient does not receive it](https://docs.pythonandvba.com/quicktext/troubleshooting/the-sms-is-marked-as-sent-on-my-phone-but-the-recipient-does-not-receive-it)

***

#### 4. Do you see a warning on your Android phone about sending lots of SMS?

* Tap **Allow** when you see the popup.
* For how to prevent or fix this, see:\
  [KDE Connect is sending a large number of SMS messages (popup)](https://docs.pythonandvba.com/quicktext/troubleshooting/kde-connect-is-sending-a-large-number-of-sms-messages-popup)

***

If none of these help, just send me an email at sven@pythonandvba.com and describe what’s happening (screenshot helps too).
