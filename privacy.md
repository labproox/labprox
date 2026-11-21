# Privacy Policy

**Effective date:** 21 November 2026

This policy explains how the Lab ProX desktop program handles information. Lab ProX is software for a medical laboratory. It runs on the laboratory’s Windows PC.

The laboratory decides what patient information is entered and who may see it. Lab ProX, the publisher of the software, does not receive a copy of the laboratory database on its own servers.

Contact: [labproox@gmail.com](mailto:labproox@gmail.com) · [WhatsApp +92 342 5534 260](https://wa.me/923425534260)

## Information stored on the laboratory computer

When staff use Lab ProX, the program stores the laboratory’s records in a database on that computer. After installation, that file is `C:\ProgramData\LabProX\LabProX.db`. A copy started from a folder keeps the database next to the program.

Those records can include:

- Patient name, age or date of birth, sex, and pregnancy status
- Phone number, email address, and national identity number (CNIC), when the laboratory enters them
- Medical-record number, sample number, referring doctor, and the laboratory’s own name
- Test orders, results, reference ranges, and report status
- Bill amounts, discounts, and payment status
- Staff names, roles, and passwords
- The laboratory’s logo, report layout, email settings, and license

Staff passwords are stored as a PBKDF2 hash, not as plain text. Email passwords and the Google sign-in are stored on the same computer.

Lab ProX does not use patient records for advertising, and it does not sell them.

## Google Drive backups

Google Drive backup is off until a person in the laboratory chooses **Connect Google Drive** in Settings and signs in with a Google account.

That sign-in is handled by Google. Lab ProX asks only for permission to create and manage files that Lab ProX itself places in Google Drive. It does not ask to read the rest of that Google account.

After the account is connected:

- Lab ProX uploads a snapshot of the laboratory database to a folder named **LabProX Backups** in that Google account.
- An automatic upload runs about once an hour, and also when someone clicks **Backup Now**.
- The snapshot contains the same laboratory records as the database on the PC, including patient and billing information.
- Lab ProX keeps about the 30 newest snapshots in that folder and deletes older ones that it created.
- The Google sign-in is stored only on that PC, protected by Windows encryption. It is not sent to Lab ProX.
- **Disconnect** stops new uploads from that PC. Files already in Google Drive stay there until someone deletes them in Google Drive.

Google stores those files under the Google account the laboratory chose. Google’s own privacy policy applies to that storage: [https://policies.google.com/privacy](https://policies.google.com/privacy).

If the PC is lost before anyone connects Google Drive, there is no Drive copy.

## Other sharing the laboratory turns on

These stay off unless the laboratory configures them:

- **Email.** If the laboratory saves its own mail-server settings, Lab ProX can email a finished PDF report to the address on that patient’s record. The message is sent through the laboratory’s mail server.
- **The laboratory’s website.** If report upload is configured, Lab ProX can upload a PDF report to the laboratory’s own web hosting. A QR code on the bill or report can point at that file.

The current program does not send SMS.

The license key is checked on the computer. Lab ProX does not contact a website to validate it.

## How long information is kept

Records remain on the laboratory computer until someone at the laboratory deletes them or restores an older backup. Drive snapshots are reduced to about 30 copies. Uninstalling the program does not, by itself, delete `C:\ProgramData\LabProX`.

## Security

The laboratory is responsible for Windows sign-in, who can open the PC, and who receives a Lab ProX password. A Google Drive backup is only as private as the Google account that holds it. That account should use a strong password and Google’s two-step verification.

## Children

Lab ProX is a tool for laboratory staff. It is not a website or app for children. A laboratory may record a child as a patient. The laboratory is responsible for having a proper reason to keep that record.

## Changes

If this policy changes, the effective date at the top will change and the new text will be published on this page. Questions about this policy can be sent to [labproox@gmail.com](mailto:labproox@gmail.com).
