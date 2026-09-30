# Privacy Policy — Hermes Personal Automation

_Last updated: 30 September 2026_

**Hermes Personal Automation** is a private, single-user application. It exists so that its owner can
read their own Google data from their own computer.

## Who uses it

Exactly one person: the owner of the Google Account that authorises it (`avielfreilich@gmail.com`).
There are no other users, no sign-up, and no third parties. The application is not distributed,
published or offered as a service to anyone else.

## What it accesses, and why

Access is granted by the owner through Google's own OAuth consent screen, and only for these scopes:

| Scope | Why it is requested |
|---|---|
| `gmail.readonly` | Read the owner's own messages (e.g. bills and statements) when the owner asks for them. It cannot send, delete or modify mail. |
| `drive.readonly` | Find and read the owner's own files in Google Drive. |
| `spreadsheets` | Read, and write summaries into, the owner's own spreadsheets. |
| `documents` | Read, and write into, the owner's own documents. |

## What happens to the data

- Data is processed **locally**, on the owner's own computer. It is not sent to any third-party
  service, server or analytics provider.
- Data is **not sold, shared, rented or disclosed** to anyone.
- Extracted information (for example a spending summary) is written to files on the owner's own
  machine and, when the owner asks, to the owner's own Google Drive.
- No data is used for advertising or to train machine-learning models.
- No data is retained by the application beyond the owner's own files, which the owner can delete at
  any time.

## Credentials

The OAuth refresh token issued by Google is stored **only** on the owner's own computer, in a file
readable only by the owner's user account (mode `600`, inside a `700` directory). No credential is
transmitted anywhere except to Google's own OAuth endpoints when refreshing access.

## Revoking access

The owner can revoke this application's access at any time at
<https://myaccount.google.com/permissions>. Revocation takes effect immediately; the stored token
then stops working.

## Contact

Questions about this policy: open an issue on this repository.
