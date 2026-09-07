# Auditing & Accountability

Evidence demonstrating security audit configuration and attributable activity within the ELOHO Active Directory lab.
## Credential Validation Auditing

Credential validation auditing was configured to record both successful and failed authentication activity.

![Credential Validation Auditing](AUD-003-Credential-Validation-Success-Failure.png)
## File Share Auditing

File-share auditing was configured to record both successful and failed access activity.

![File Share Auditing](AUD-004-File-Share-Auditing-Success-Failure.png)
## Attributable Finance Share Activity

A successful file-share access event was recorded for `ELOHO\ada.okafor` accessing the Finance share, linking the activity to a specific authenticated identity.

![Ada Finance File Share Audit](AUD-005-Ada-Finance-File-Share-Audit-5145.png)
## Attributable Operations Share Activity

A successful file-share access event was recorded for `ELOHO\david.menser` accessing the Operations share, linking the activity to a specific authenticated identity.

![David Operations File Share Audit](AUD-006-David-Operations-File-Share-Audit-5145.png)
