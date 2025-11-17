# Antivirus or Firewall Warning (False Positive)

Sometimes QuickText triggers a warning from antivirus or firewall software. This is a false positive.

#### Why does this happen?

QuickText uses VBA macros and runs small scripts in the background to send SMS. Some antivirus tools flag any file that automates tasks or opens a command prompt, even if it’s safe. This is common for tools built with macros or automation.

#### Is QuickText safe?

Yes. I monitor QuickText on VirusTotal every day. Most major antivirus tools like **Kaspersky** and **Windows Defender** show it as clean. Sometimes a smaller antivirus will flag it. When that happens, I submit a false positive report to the vendor. In some cases, I don’t get a response, so the warning may stay active for a while.

You can check today's scan here:\
[https://www.virustotal.com/gui/file/daaf4fafbbc024849c76ec6e0ffbc7fdc348415e5aabe59e9233024b32715530](https://www.virustotal.com/gui/file/daaf4fafbbc024849c76ec6e0ffbc7fdc348415e5aabe59e9233024b32715530)

Last checked: November 17, 2025

#### What should you do?

* If your antivirus or firewall warns you, please contact me at contact@pythonandvba.com. Let me know which program shows the warning so I can report it.
* You can also add QuickText as an exception in your antivirus settings if you trust the file.
* If you’re not comfortable with this, let me know and I’ll help you out.
