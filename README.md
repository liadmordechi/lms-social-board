# lms-social-board

Public host for the LMS Academy social content agent.

- `media/` — post assets, served over HTTPS so Telegram and the Instagram Graph API can fetch them. Both require a publicly reachable URL; neither accepts a local file.
- The weekly content board will live here as a StatiCrypt-encrypted page. Encrypted content is not readable without the password.

No credentials, no tokens, and no passwords are ever stored in this repository.
