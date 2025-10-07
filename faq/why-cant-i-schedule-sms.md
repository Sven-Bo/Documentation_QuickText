# Why Can’t I Schedule SMS?

I get a lot of requests about scheduling SMS in QuickText. Scheduling means you set a time, and the message is sent later, maybe tomorrow or next week. This sounds useful, right? I agree.

But here’s why it is not possible in QuickText (for now):

#### How QuickText Works

When you use QuickText, your SMS goes straight from your Excel to your phone. Nothing goes through my server. No one else ever sees your messages (except the receiver of course 😉).

#### Why Scheduling Is Tricky

For QuickText to send a message at a certain time, your computer must be:

* Turned on.
* Excel must be open, with your file running.
* QuickText must be ready.
* Your phone must be connected to your computer with KDE Connect.

If even one of these is missing, the message will not send.\
For example, if your laptop is closed or you turned it off, nothing will happen at the scheduled time.

#### Why Some Apps Can Schedule SMS

Apps that can schedule messages usually send your SMS through their own servers. Your message is stored on their side, and they send it when the time comes, even if your computer is off (but not using your own phone number).

QuickText does not do this. Your messages are always private and only sent by you, from your own phone.

#### The Main Benefit (and Limitation)

The main benefit of QuickText is that your SMS are always sent from your own phone, using your own number. Because of this, scheduling is not possible. I am always keeping an eye out for practical ways to add this feature, but for now, there is no simple solution.
