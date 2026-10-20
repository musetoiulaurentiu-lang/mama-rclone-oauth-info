---
title: Privacy Policy
---

# Privacy Policy — MAMA-RCLONE-BACKUP

**Last updated: October 20, 2026**

## 1. Purpose

MAMA-RCLONE-BACKUP is a personal, non-commercial utility that uses rclone to create, upload, download, and verify encrypted backups in the owner's Google Drive account.

It is intended for the account owner's personal use and is not offered as a public service.

## 2. Google Drive access

The application uses the Google Drive OAuth scope `https://www.googleapis.com/auth/drive`.

This scope grants broad access to files in the authorized Google Drive account, including permission to view, create, edit, and delete files. The utility is intended to use that access for backup and recovery operations.

## 3. Data handling and storage

Backup content is encrypted locally using rclone crypt before being uploaded to Google Drive. The encrypted backup files are stored in the owner's Google Drive account.

OAuth credentials and tokens are stored in the owner's local rclone configuration. They are not intentionally published to GitHub.

Google processes and stores backup data in accordance with its own applicable policies.

## 4. Data sharing

The utility is not designed to sell Google user data, use it for advertising, or disclose it to unrelated third parties.

Google Drive is used as the storage provider for encrypted backups. GitHub Pages hosts this public informational website; it does not host the private backup archive.

## 5. Retention and deletion

The account owner controls the Google Drive backup files and can delete them from the account.

Automated database backups may use rotating storage slots. Separately created historical backups may remain until the owner deletes them.

The owner can revoke the application's Google Drive access through Google Account security settings.

## 6. Security

The utility uses local encryption for backup content and relies on Google OAuth for authorized access to Google Drive.

No security mechanism eliminates every risk. The account owner is responsible for protecting local devices, credentials, and encryption configuration.

## 7. Contact

Questions about this personal utility can be submitted through the GitHub repository:

https://github.com/musetoiulaurentiu-lang/mama-rclone-oauth-info
