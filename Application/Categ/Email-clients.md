<!-- current link
https://github.com/iulmit/Tidy-web/blob/main/Application/Categ/Email-clients.md
-->

# Email clients

What is email?</br>
https://en.wikipedia.org/wiki/Email</br>
https://en.wikipedia.org/wiki/History_of_email<br>

What is an email client?</br>
https://en.wikipedia.org/wiki/Email_client</br>
https://en.wikipedia.org/wiki/Webmail</br>

Comparison of email clients</br>
https://en.wikipedia.org/wiki/Comparison_of_email_clients</br>

Email providers</br>
https://en.wikipedia.org/wiki/Comparison_of_webmail_providers</br>
https://wiki.installgentoo.com/wiki/Email_providers</br>

Emails may travel and be stored on networks and computers without the sender's or the recipient's control. During the transit time it is possible that third parties read or even modify the content. Internal mail systems, in which the information never leaves the organizational network, may be more secure, although information technology personnel and others whose function may involve monitoring or managing may be accessing the email of other employees. Due to this, [email privacy](https://en.wikipedia.org/wiki/Email_privacy), without some security precautions, can be compromised.</br>

With no encryption, much like for postcards, email activity is plainly visible by any occasional eavesdropper. [Email encryption](https://en.wikipedia.org/wiki/Email_encryption) enables privacy to be safeguarded by encrypting the mail sessions, the body of the message, or both. Without it, anyone with network access and the right tools can monitor email and obtain login passwords. Examples of concern include the government [censorship](https://en.wikipedia.org/wiki/Censorship) and [surveillance](https://en.wikipedia.org/wiki/Surveillance) and fellow wireless network users such as at [public hotspots](https://en.wikipedia.org/wiki/Hotspot_%28Wi-Fi%29) or [Internet cafe](https://en.wikipedia.org/wiki/Internet_cafe).</br>

Encrypted email sessions transfer messages in their original format, between a user's local/remote email box (mailbox) and the destination mailbox. The email exchange between mailboxes can be done using an [email client](https://en.wikipedia.org/wiki/Email_client), or via [webmail](https://en.wikipedia.org/wiki/Webmail).</br>

There are two widely used standards for email encryption.
- OpenPGP/GnuPG is popular among individuals
- S/MIME/X.509 is mostly used by enterprises</br>
In both cases, only the message body is encrypted. Header fields, including originator, recipients, and often subject, remain in plain text. 

One of the risks using email is getting email address in the hands of [spammers](https://en.wikipedia.org/wiki/Email_spam). There are a number of methods to fight with this:
- [The Spamhaus Project](https://en.wikipedia.org/wiki/The_Spamhaus_Project)

There are a number of hardware encryption devices: [Yubikey](https://keylockguide.com/yubikey-vs-nitrokey/), [Nitrokey](https://www.nitrokey.com/).

---

## Applications (desktop clients)

### Thunderbird</br>
https://www.thunderbird.net/en-US/

Building Thunderbird is detaild on [Gettings Started](https://developer.thunderbird.net/thunderbird-development/getting-started) page. There are [Build details](https://developer.thunderbird.net/thunderbird-development/building-thunderbird) specific to each platform: Windows, Linux, macOS.


Some changes of the default settings:
- Menu > Tools > Preferences
  - General
    - Default Search Engine > DuckDuckGo
    - Files & Attachements > Portable Document Format (PDF) > Action: use other client ([details](https://support.mozilla.org/en-US/questions/1347362))
  - Privacy & Security
    - Thunderbird Data Collection and Use > Send technical and interaction data to Mozilla > `disable`
    - Thunderbird Data Collection and Use > Send backlogged crash reports on your behalf > `disable`
  - Chat
    - Status > When Thunderbird starts: `Keep my Chat Account offline`
    - Notifications > When messages directed at you arrive > Play a sound > `disabled`
- Menu > Help > More Troubleshooting Information 
  - [about:telemetry](https://support.mozilla.org/en-US/kb/thunderbird-telemetry) > "Telemetry is collecting release data and upload is enabled." > `disable` (???)
    - info to review: https://groups.google.com/g/mozilla.support.thunderbird/c/sB3KVS-EBMs

An error appears after adding some Gmail accounts: "Your browser is not supported anymore. Please update to a more recent one."</br>
[The solution](https://libredd.it/r/Thunderbird/comments/ovdb86/your_browser_is_not_supported_anymore_please/) is to go to Thunderbird Preferences > General > Config Editor, and set the following flag to **True**:
  `general.useragent.compatMode.firefox`


---
## Webmail providers

### ProtonMail
[Website](https://protonmail.com/) | [Tips & tricks](https://protonmail.com/support/categories/tipsandtricks/)

---

## Reference links

[S/MIME](https://en.wikipedia.org/wiki/S/MIME) Email Encryption (S/MIME = secure email)</br>
https://docs.nitrokey.com/pro/smime.html</br>
https://askubuntu.com/questions/181851/how-to-obtain-a-s-mime-certificate-for-e-mail-encryption

OpenPGP/GnuPG</br>
https://docs.nitrokey.com/pro/openpgp.html
