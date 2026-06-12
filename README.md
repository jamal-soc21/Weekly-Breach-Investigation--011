# Weekly-Breach-Investigation--011
Weekly Breach Investigation
Breach: ShinyHunters — Oracle PeopleSoft Zero‑Day
Analyst: Jamal Mahmoad
Date: 2026-06-12

📌 Summary
ShinyHunters exploited a zero‑day (CVE‑2026‑35273) in Oracle PeopleSoft to gain remote access and steal sensitive data.
The flaw exposed servers running PSEMHUB over HTTP, and universities were the main victims, with hundreds of thousands of student records leaked.

🔎 Attack Flow
Vulnerable endpoints exposed.

Malicious agents deployed.

Lateral movement via SSH.

Data compressed and exfiltrated.

⚙️ MITRE ATT&CK
Execution: Remote Exploitation (T1190)

Persistence: Web Shells (T1505)

Exfiltration: SSH Data Theft (T1048)

🛡️ Mitigation
Disable/remove PSEMHUB.

Block external access to risky endpoints.

Apply Oracle’s patch when available.

Monitor for unusual files and outbound traffic.

📝 Analyst Notes
This incident shows the high risk of ERP zero‑days in education.
ShinyHunters escalated from SaaS token theft to direct ERP exploitation, marking a dangerous shift in tactics
