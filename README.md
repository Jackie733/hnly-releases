# hnly desktop downloads

An independent Hacker News reader for macOS and Windows.

This repository contains installers, release notes, third-party notices and signed update files. Application source code is maintained in a separate private repository.

## Download and install

Get installers from [Releases](https://github.com/Jackie733/hnly-releases/releases). Choose the file matching your operating system and processor. Only published targets are available; a missing Windows installer means that the local Windows build has not been published yet.

- **Mac, Apple Silicon:** open the `darwin-aarch64.dmg` file, then drag hnly into Applications. Start the installed application from Applications, rather than from the mounted disk image.
- **Windows x64, when available:** open the `windows-x86_64.exe` installer. The default installs hnly for the current user.

This is independent distribution. Mac releases are not notarized by Apple; Windows releases do not currently carry a trusted publisher certificate. Your system may display a trust prompt or block opening. Only proceed if you trust the source and your system permits an exception for this application. See [Apple's instructions](https://support.apple.com/en-us/102445). Do not disable system-wide protection or ignore a malware detection.

## Update an installed copy

Open **About hnly → Software updates**. On Mac, **hnly → Check for Updates…** is also available. Download the offered update, then choose **Install and reopen**. Reading records and reply drafts are kept on the device. Finish active account and translation tasks before installing. You can turn off automatic checks.

Copies predating application updates need one manual installation of a current installer. Downloading the `.app.tar.gz` file is not the normal Mac installation flow; it is consumed by the updater.

## Verification and privacy

The application verifies update packages against an embedded release key and checks the signed version before installation. Update signatures are separate from Apple / Microsoft publisher approval. Public verification keys and third-party notices are provided with releases. Checks and downloads contact GitHub; they do not send HN or ChatGPT credentials. Privacy and service terms are available inside the application.

This repository does not contain signing private keys, application credentials, user data or source archives from the private repository. GitHub's automatically generated source archives contain only this distribution repository's public documents.
