# UTAX AI — Account and Data Deletion

This page applies to the UTAX AI app for Android and iOS, published under the app identifier `ai.humblebee.utax`.

## Request account deletion

Starting with UTAX AI 1.0.7, while signed in, open **Settings → Account → Delete
account**, read the warning, type **DELETE**, and confirm. Once the server accepts
the request, your account is disabled and the app signs you out. Automatic
background cleanup then removes the associated live-service data described below.
An **account deletion started** message means the request was accepted, not that
cleanup has already finished. Cleanup retries if a service is temporarily
unavailable; no fixed completion deadline is promised.

If you use an older version, cannot sign in, or cannot confirm the request, use
the email route below. Contact support to check deletion progress.

Email [support@utax.uz](mailto:support@utax.uz?subject=UTAX%20AI%20account%20deletion).
Use the subject **UTAX AI account deletion** and state that you want your UTAX AI
account and its associated data deleted. For Google Sign-In accounts, use the
associated email address where possible. For Telegram Sign-In accounts, include
your Telegram username or account identifier so support can verify the request.

You do not need to install or sign in to the app to submit this request. Do not
send passwords, authentication tokens, sign-in codes, or sensitive documents.
We may ask for information needed to verify that the request belongs to you.

## Data covered by the request

The request covers your UTAX AI account/profile and identifiers, server-side chat
history (including previously soft-deleted chats), messages, uploaded attachments,
and associated extracted text, inference history and AI/vector-index copies.
It does not delete your Google or Telegram account or data held independently
by those providers.
Removing an account row alone does not constitute deletion of all this data.

After an accepted in-app deletion, the app clears the account's local chat and
attachment cache and sign-in credentials. The app may also store preferences on
your device. Uninstall UTAX AI to remove its remaining local app storage. Removing
the app alone does not delete your server-side account or data.

## Retention

In-app requests are authenticated through your signed-in account and processed
automatically. Email requests require identity verification and fulfillment by
the support team. Deletion is not immediate. Completion is confirmed only after
cleanup across the live account database, uploaded-file storage, AI memory and
user-specific vector indexes succeeds. Limited content-free technical records
may remain to prevent deleted data from being restored by pending operations.
Backups and independent provider logs are not immediately erased by this process
and remain subject to their applicable retention requirements. Limited records
may need to be retained to comply with applicable legal obligations, resolve disputes, or
protect the service from abuse, as described in our privacy policy. Support should
explain the affected data, reason and applicable retention period, including any
backup retention, before marking your request completed. No fixed deletion
deadline is promised on this page.

## Delete chat or attachment data without deleting your account

You can also email support@utax.uz to request deletion of specific server-side chats or attachments while keeping your account. Include the approximate chat date or other non-sensitive identifying information.

For more information, see the [UTAX AI Privacy Policy](https://github.com/wakil-ai/privayc-policies/blob/main/privacy-policy-utax-ai.md).
