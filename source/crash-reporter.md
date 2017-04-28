---
title: Crash Reporter
permalink: /crash-reporter/
slug: crash-reporter
description: Info about our Crash Reporter dialog
---

# MPC-HC Crash Reporter

The *Crash Reporter* is a dialog box that warns you when MPC-HC closed unexpectedly.
It lets you submit extra information to help developers fix the issue.


## When MPC-HC crashes

After MPC-HC crashes, the *Crash Reporter* window will appear.

<img class="img-responsive defer" src="data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20xmlns%3Axlink%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink%22%20viewBox%3D%220%200%20300%20200%22%3E%3Cdefs%3E%3Csymbol%20id%3D%22a%22%20viewBox%3D%220%200%2090%2066%22%20opacity%3D%22.3%22%3E%3Cpath%20d%3D%22M85%205v56H5V5h80m5-5H0v66h90V0z%22%2F%3E%3Ccircle%20cx%3D%2218%22%20cy%3D%2220%22%20r%3D%226%22%2F%3E%3Cpath%20d%3D%22M56%2014L37%2039l-8-6-17%2023h67z%22%2F%3E%3C%2Fsymbol%3E%3C%2Fdefs%3E%3Cuse%20width%3D%2220%25%22%20x%3D%2240%25%22%20xlink%3Ahref%3D%22%23a%22%2F%3E%3C%2Fsvg%3E" data-src="/assets/img/crash-reporter/crash_reporter.png" width="466" height="428" alt="Crash reporter dialog">
<noscript><img class="img-responsive" src="/assets/img/crash-reporter/crash_reporter.png" width="466" height="428" alt="Crash reporter dialog"></noscript>

This dialog can be used to provide information that might be useful to the developers:

* **E-mail**: If you allow our developers to contact you should they need follow-up information from you about this crash, provide the e-mail address you wish to be contacted at here. You may also receive an e-mail after your crash has been processed, for example to let you know that the problem has been fixed.
* **Problem description**: Use this box to add any further information that might be useful to developers trying to find the cause of the crash. For example, it is always helpful that you explain us what you were doing exactly when the crash happened so that we can reproduce it more easily. Note that it is important that you use English or your comment might not be usable by our developers.

If you do not wish to provide extra information, you may leave any of those fields blank, but be aware that it may prevent us from fixing the issue you encountered.

After you quit this dialog, the *Crash Reporter* will try to identify the crash in case it has already been reported. If it has not, the following dialog will request your authorization before sending more information about the crash.

<img class="img-responsive defer" src="data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20xmlns%3Axlink%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxlink%22%20viewBox%3D%220%200%20300%20200%22%3E%3Cdefs%3E%3Csymbol%20id%3D%22a%22%20viewBox%3D%220%200%2090%2066%22%20opacity%3D%22.3%22%3E%3Cpath%20d%3D%22M85%205v56H5V5h80m5-5H0v66h90V0z%22%2F%3E%3Ccircle%20cx%3D%2218%22%20cy%3D%2220%22%20r%3D%226%22%2F%3E%3Cpath%20d%3D%22M56%2014L37%2039l-8-6-17%2023h67z%22%2F%3E%3C%2Fsymbol%3E%3C%2Fdefs%3E%3Cuse%20width%3D%2220%25%22%20x%3D%2240%25%22%20xlink%3Ahref%3D%22%23a%22%2F%3E%3C%2Fsvg%3E" data-src="/assets/img/crash-reporter/send_more_info.png" width="348" height="189" alt="Send more info dialog">
<noscript><img class="img-responsive" src="/assets/img/crash-reporter/send_more_info.png" width="348" height="189" alt="Send more info dialog"></noscript>

If you agree, just press **Send information** and wait while the crash report is transmitted to us. Remember that if you choose not to send us that information, it could be extremely difficult for us to get a clear view of what happened.

After the crash reporter terminates, a web page with more information about the status of the crash you just reported will be opened.

## What about privacy?

Your privacy is very important to us and we will not transmit potentially private information before you explicitly give your consent. Moreover, any information you choose to send is kept private and is only accessible to MPC-HC development team.

If you choose to send more information to our developers, a dump file will be transmitted to them. This dump file is a snapshot of MPC-HC's state when it crashed. It may contain private data handled by MPC-HC (for example: the path of the currently playing file, the name of the files in the playlist, etc.).
