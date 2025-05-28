🔍 Active Directory Recon Lab — Walkthrough

💡 Goal
To simulate reconnaissance of a Windows domain environment using open-source red team tools like BloodHound and SharpHound.

🛠️ Setup
- Windows Server 2019 as Domain Controller
- Windows 10 client (joined to domain)
- Kali Linux attacker box

🔧 Tools Used
- SharpHound (collector)
- BloodHound + Neo4j (visualization)

🧪 Steps
1. Deployed SharpHound on Windows client
2. Collected recon data using "All" collection method
3. Imported JSON into BloodHound on Kali
4. Mapped out Domain Admin attack paths

🧠 What I Learned
- BloodHound shows the *exact* privilege escalation routes
- Even non-admin users can reveal dangerous misconfigs
- Knowing what’s exploitable = knowing what to secure

📎 Screenshots
Coming soon...

Return to [Home](https://neppsypepsi.github.io/RedTeam-Summer-Lab-2025/)
