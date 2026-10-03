# Chava Suite

A Windows desktop app for managing a concert season: subscribers, registrations,
reviewed seat bookings, ticket PDFs, balances and email draft preparation.

## Download and install

**[Download Chava Suite for Windows](https://github.com/amirtqa9/ChavaSuite-Releases/releases/latest)**

1. Open the download page above.
2. Under **Assets**, download the file named `ChavaSuite-…-Setup.exe`.
3. Open the downloaded installer and follow its steps.
4. Launch **Chava Suite** from the Start menu or desktop shortcut.

No GitHub account or token is needed. Python and the browser needed by the app are
included. Use a Windows computer that supports 64-bit apps. Microsoft Word is
needed for the ticket workflow that exports a Word document to PDF.

Windows may show an unsigned-publisher warning. This app does not currently have
a Windows publisher certificate. Download only from this repository; do not
turn off Windows security settings.

## Getting started

Enter your own site/email details in **Settings**. If you have an older Chava
installation, the first launch offers to copy its saved data while keeping the
original. Each computer saves its own data; installing the same app on another
computer does not automatically share customer records.

For **Ask Chava**, click **Connect ChatGPT** and sign into your own account in the
browser. You do not need a local AI model or an API key. Your account's access and
usage limits apply. Questions can include app/customer context shown in the app's
sharing preview; that context goes to the connected cloud helper when you ask.

The app prepares email drafts for human review. It does not send emails
automatically. Booking and cancellation workflows retain their confirmation steps.

## Updating

Chava checks for a newer version shortly after opening. You can also open
**Updates → Check for updates**.

Read the release notes, click **Download update**, then **Restart to install**.
Finish current tasks and save profile edits first. Installation needs your
confirmation. Chava verifies signed update metadata and the installer checksum,
then backs up your saved data locally before updating.

Subscriber records, booking history, settings and this computer's helper sign-in
stay in your Windows user folder, separate from installed code. Backups stay on
your computer. Uninstalling the app keeps that saved user data.

If an update fails, keep your data and contact the developer before restoring a
backup. Do not upload customer records, passwords or account sessions to issues.

## Manuals and help

Open **Help** inside Chava for the **User Guide** and **Subscriber Emails Manual**.
The manuals are included with the installer, and can also be downloaded here:

- [User Guide (PDF)](https://github.com/amirtqa9/ChavaSuite-Releases/releases/latest/download/Chava_User_Guide.pdf)
- [Subscriber Emails Manual (PDF)](https://github.com/amirtqa9/ChavaSuite-Releases/releases/latest/download/Chava_Email_Manual.pdf)

Release notes explain changes in each
version. Suspected bugs found through Ask Chava are saved locally for developer
review; they are not automatically published here.

## Sharing

Send this link to another person:

**https://github.com/amirtqa9/ChavaSuite-Releases/releases/latest**

It always opens the latest published installer release. Everyone downloads the
same clean app; each person enters their own accounts and manages their own data.

This public repository contains download information and release files. The
source repository remains private. No customer databases, credentials, builder
account sessions or private development history are distributed here. The
installer contains the application code and its runtime dependencies.
