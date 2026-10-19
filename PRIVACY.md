# Kinwell Privacy Policy

Updated October 19, 2026 · Policy version 2026-10-19.1

## Operator and scope

Kinwell is a personal family wellness website operated by Matthew Christensen. Contact mattchristensen503@gmail.com for privacy questions, access, correction, export or deletion requests. This policy describes Kinwell's WHOOP, Oura, sleep dashboard and registered-profile features. Oura data is collected only after its integration is configured and you authorize your account. Installing an update or registering a developer app does not authorize a family member's wearable account.

## Information and purposes

Account information includes your name, email address, salted password hash, family membership, invitation records, sharing preferences, and registration date where recorded. Session records and a necessary cookie support sign-in. The server processes connection information such as IP addresses for requests and temporary login throttling. Kinwell requires your birthday when creating an account, or once when completing an existing account. It stores the date in your account record and calculates your age group on each sleep date to adjust the sleep-duration reference automatically. You can correct your birthday in Connections & privacy; this recalculates imported sleep scores. Your birthday is not displayed to family members or in the site-owner Profiles list. The current Oura integration does not save or use the age returned by Oura.

WHOOP access verifies your provider account ID. Kinwell requests profile, sleep, recovery, cycle and workout access and renewable authorization. It stores selected scored sleep dates, bedtime/wake time, timezone offset, duration, time in bed, missing-data duration and nap status; recovery score, resting heart rate and HRV; and cycle/workout strain, average heart rate, times and sport. Record IDs and update timestamps support import handling. WHOOP profile names and email addresses are discarded. Kinwell does not request WHOOP body measurements, even if the developer dashboard allows that scope.

Oura access verifies your provider account ID and retrieves sleep records using personal and daily permissions. Kinwell stores selected main-sleep dates, bedtime/wake time, timezone offsets, duration, time in bed and a completeness indicator derived from the returned totals and battery flag. Other personal profile fields and unrelated measurements returned by Oura are discarded. Provider responses are processed in memory; full raw responses are not saved by Kinwell.

Provider access and refresh tokens allow imports without repeatedly signing in to the provider. Kinwell never receives your WHOOP or Oura password. Old manual check-in records may remain in storage and backups; manual entry is disabled and these records are excluded from the dashboard and scoring.

## Sleep estimates and family sharing

Kinwell uses imported readings for personal sleep history, charts and an experimental age-adjusted sleep score. If both devices have a main sleep on the same date, Oura takes priority and WHOOP fills dates without Oura. Readings are not added together. The score is a Kinwell estimate, not a provider score or medical assessment. It cannot establish who is healthiest or remove differences between device measurements.

Your name and whether sharing is available are visible to your family. Calculated-score sharing and each provider's sleep-duration sharing are separate choices and start off. When enabled, scores share dates, source, formula version and scores; durations share dates, source and hours asleep. Family members can see resulting rankings and averages. Birthday, age group, detailed timing, efficiency and consistency components remain private through family-facing application responses. WHOOP recovery and activity details are not shared with family members by this edition.

Turning sharing off prevents later access through the family dashboard. It cannot recall screenshots or copies someone already made. Sharing is voluntary; family members should not redistribute another person's readings without permission. An invitation permits joining a family, not access to a private wearable account.

## Site-owner access

The locally appointed site owner can view a read-only list of all registered accounts, including names, emails, family memberships and recorded creation dates. This list does not include birthdays, age groups, private health readings, passwords or provider tokens. Separately, the operator controls the computer and can technically access its database, configuration, keys and backups. Family privacy controls do not prevent that administrative access. This is not end-to-end encryption between family members.

## Storage, security and providers

Application records are stored on the operator's ThinkPad. Public website traffic passes through an ngrok HTTPS tunnel. WHOOP and Oura receive authorization and API requests. GitHub hosts the public policy documents; the public policy repository contains no Kinwell accounts, health records or credentials. These providers may process connection and technical information under their own policies:

- WHOOP: https://www.whoop.com/us/en/privacy/
- Oura: https://ouraring.com/privacy-policy
- ngrok: https://ngrok.com/legal/privacy
- GitHub: https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement

Passwords are salted and hashed. Provider tokens are encrypted with AES-256-GCM. The database itself is not encrypted by Kinwell. Encryption keys and developer secrets are kept on the server; anyone able to read the database and matching keys can decrypt tokens. Security also depends on computer access controls, device protection and protected backups. No system guarantees absolute security.

Kinwell does not sell personal information, include advertising or analytics trackers, or send wearable readings to AI services. The necessary sign-in cookie normally lasts seven days; signing out ends the current session. There is no marketing-cookie feature in this edition. Third-party services have their own cookie and retention practices.

## Retention, disconnecting and requests

Sync is initiated with a button. A successful sync replaces that provider's active imported snapshot with approximately the last 30 days; a failed sync keeps the previous snapshot. If you do not sync again, the last snapshot remains until disconnected or administratively deleted. A display window is not an automatic deletion schedule.

Disconnecting a wearable deletes that provider's active imported records, credentials and connection/sharing records from Kinwell, and attempts to revoke provider access. If revocation cannot be confirmed, Kinwell tells you to revoke access in the provider account. Disconnecting does not delete your Kinwell account, family membership, birthday, other provider's data, or records held by the provider itself.

Accounts, preferences and legacy manual records remain until administratively removed. The update helper creates local backups containing the data folder, which can include health records, credentials and keys. Backups are not automatically erased by disconnecting or deletion in the active database; there is currently no automatic backup-expiration schedule. Contact the operator to request removal from active storage and retained backup copies and to confirm what has been removed. Kinwell has no self-service account-deletion or export workflow yet. The operator may need to verify that a request concerns your account without asking for your password or provider secret. Rights and response requirements under applicable law remain available.

## Children and participation

Kinwell does not implement a verified parental-consent workflow. Providing a birthday is not proof of eligibility or parental consent. A parent or guardian should contact the operator before a child participates, and applicable privacy requirements and each wearable provider's account rules must be satisfied. Do not create an account or connect data for someone else without appropriate authority. If you believe a child's information was collected improperly, contact the operator for review and removal.

## Changes

The version and update date identify this notice. Material changes to collection, use or sharing should be communicated to affected members before new uses are enabled. A policy update alone does not turn sharing on or authorize a new provider connection. See the companion Terms of Service for use of Kinwell.