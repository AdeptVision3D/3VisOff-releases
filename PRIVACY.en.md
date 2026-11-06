# What 3VisOff sends to the internet

Your clients, projects, finances, documents, database contents, passwords, PIN, tokens and keys are **never sent to the developer**. A PRO key is verified on your computer, without internet.

## Always (can be turned off)
- **Update check** (GitHub, the releases repository): to learn about a new version and download it. Ordinary network data is visible, as when visiting a website; no app data. Turn it off in Settings ("Check for updates on launch").

## Only if you turned the function on yourself
- **Email (Gmail):** emails and reply checks go through Google servers from your mailbox, on your command.
- **Telegram notifications:** messages go to your own bot through Telegram servers.
- **Requisites by INN (Russia):** one INN you entered is sent to DaData.
- **Order search (PRO):** the 3ddd orders page is opened from your computer at most once every 3 hours; from your Gmail only emails from the platforms you chose are read (subject and links). Nothing is sent to the developer.
- **Sync:** the backup file is placed in the cloud folder you chose; the app itself contacts no server.

## Only with your consent (Settings → "Privacy and reports")
- **Anonymous statistics** (off by default): once a day a random installation number, app version and system.
- **Error report:** on a crash the app asks in a window and shows the report text. The error text and a technical trace are sent; names of personal folders, emails, tokens and keys are replaced with placeholders. You can allow "always" in Settings. The window has optional fields "What were you doing?" and "How can we reach you?": they are sent only if you fill them in. The "Report a problem" button in Help sends your description the same way, when you press it.
- Recipient of reports: the support service on Cloudflare (Worker `visoff-support-bot`); new errors reach the developer in Telegram, install counters are stored for 90 days without any personal data.

## Support bot and website
- **Bot:** consent to data processing is given as a separate document with an “Agree” button before the first message (https://visoff.pages.dev/en/consent/); you can withdraw it with /revoke. If you write to the support bot we receive your Telegram ID, name, @username, the text and attachments of your messages and the PRO keys issued to your account: to answer, issue keys and record payment.
- **Website:** visits and downloads are counted anonymously (an irreversible mark is kept for two days, only daily totals remain, the network address is not stored); the site uses no cookies and the counter does not run when “Do Not Track” is on.
- Full policy: https://visoff.pages.dev/en/privacy/ . Offer: https://visoff.pages.dev/en/terms/ .

## Links
Support (Telegram bot) and the download page simply open in your browser.
