# MAMA-RCLONE-BACKUP

MAMA-RCLONE-BACKUP is a personal, non-commercial backup utility.

The application uses rclone and Google Drive to store encrypted backups of files and a local SQLite memory database.

## How it works

The utility runs on the owner's computer. It creates local backup snapshots, encrypts backup content using rclone crypt, and transfers the encrypted files to the owner's Google Drive account.

Google Drive authorization is used exclusively to perform and verify backup operations, including uploading and downloading encrypted backup files.

The application is intended for personal use and is not offered as a public service.

## Data access

Google Drive access is authorized by the account owner. The application does not sell user data or use Google Drive data for advertising.

## Privacy

Read the [Privacy Policy](privacy.md) for information about data access, storage, and protection.
