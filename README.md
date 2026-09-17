<h1 align="center">Omri Elcharizi</h1>

<p align="center">
  <a href="https://omrielcharizi.com"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=3A9BC7&center=true&vCenter=true&width=620&lines=System+Administrator+%C2%B7+Active+Directory%2C+VMware%2C+Linux;Three+years+keeping+24%2F7+operational+systems+available;I+maintain+the+server+and+write+the+UI+that+talks+to+it" alt="typing tagline"></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/omri-elcharizi-sysadmin"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:omri7779@gmail.com"><img src="https://img.shields.io/badge/Email-omri7779%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://omrielcharizi.com"><img src="https://img.shields.io/badge/Portfolio-omrielcharizi.com-3a9bc7?style=flat&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://omrielcharizi.com"><img src="https://img.shields.io/badge/CV-Download-1a7f37?style=flat&logo=googledocs&logoColor=white" alt="Download CV"></a>
</p>

---

System administrator and team lead of four. Three years keeping operational systems, and the simulator and training environments that mirror them, available across multiple sites staffed around the clock. Active Directory, Windows Server, VMware vSphere and Red Hat over SSH. Every fault diagnosed on site, at the console.

I maintain the servers and I write the interfaces that talk to them, so I debug the whole stack, not just my half of it.

Based in Ashdod, Israel. Available now.

## Experience

**System Administrator, Reserve Duty &#183; Infrastructure and front-end** &#183; Israeli Air Force &#183; Apr 2026 to Sep 2026 (completed)
Continued the technical role and redesigned the screens of an internal system in daily use: HTML, CSS and scripting, working directly with the operators who use it.

**System Administrator &#183; Team Lead** &#183; Israeli Air Force &#183; Aug 2023 to Apr 2026
Led four technicians on systems staffed 24/7: task allocation, training, shift handover, phone on-call. Certified inspector, authorised to sign off other technicians' work.

- Kept the simulator and training environment available for scheduled exercises. Reproduced a fault from a second station to tell a station fault from a system fault, restarted the application tier, ran the vendor's script to clear a hung scenario.
- Took over a recording subsystem that had no owner and no written procedure: corrected its address mapping, consolidated per-station state into one status view, recovered it after a drive failure by migrating to a backed-up drive, then traced the remaining dark stations to a shared control unit and a display cable. Wrote the runbook that had never existed and trained a backup technician on it.
- Built about 20 operator workstations from boot media: domain join, manual MAC and asset registration, and the security team's endpoint check before release.
- Administered Active Directory: users, groups, permissions and the password-reset workflow.
- Operated VMware vSphere day to day and wrote the vCenter startup procedure the team uses, including the order the domain controllers come up in.
- Ran Red Hat servers over SSH: service status, systemctl restarts of the Tomcat tier, vendor scripts, log triage. Helped institute a weekly maintenance window with version and checksum verification, then patching one machine at a time.

## Education

- Practical Engineer (P.E.) Diploma, Electronics and Computers &#183; Makif Alef Technological College, Ashdod &#183; 2021&ndash;2023
- Inspector Qualification Course &#183; Israeli Air Force

## Stack

**Systems and identity**
<p>
  <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat&logo=windows&logoColor=white" alt="Windows Server">
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=flat&logo=microsoftazure&logoColor=white" alt="Active Directory">
  <img src="https://img.shields.io/badge/Red_Hat-EE0000?style=flat&logo=redhat&logoColor=white" alt="Red Hat">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux">
</p>

**Virtualization**
<p>
  <img src="https://img.shields.io/badge/VMware_vSphere-607078?style=flat&logo=vmware&logoColor=white" alt="VMware vSphere">
  <img src="https://img.shields.io/badge/Proxmox_VE-E57000?style=flat&logo=proxmox&logoColor=white" alt="Proxmox VE">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Portainer-13BEF9?style=flat&logo=portainer&logoColor=white" alt="Portainer">
</p>

**Networking and scripting**
<p>
  <img src="https://img.shields.io/badge/TCP%2FIP-005571?style=flat" alt="TCP/IP">
  <img src="https://img.shields.io/badge/DNS_%2F_DHCP-4B8BBE?style=flat" alt="DNS and DHCP">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" alt="n8n">
</p>

## Home lab

A single Proxmox VE node running 24 LXC containers and Docker stacks managed in Portainer. Every service sits behind a reverse proxy, backups are scheduled and the restores are tested, uptime is monitored with alerts, and an RTX 3060 is passed through to a dedicated container for local language-model inference. I operate it daily and rebuild it from documented steps.

Write-ups and incident postmortems &mdash; driver and userland version mismatches, a cold-load stall after a disk migration, a volume shadowing a bundled database &mdash; are at [omrielcharizi.com](https://omrielcharizi.com).

## Projects

**[mail-classifier](https://github.com/OmriTGM/mail-classifier)**
n8n polls Gmail every 15 minutes, sends each new message to a local model (qwen3:14b) on an RTX 3060, and applies a matching label. The classify request retries twice with a five-second gap and continues on failure, so one bad response does not stall the queue. No API cost, and no mail leaves the LAN.

## Looking for

A System Administrator or IT infrastructure role in the centre or south of Israel: Windows Server and Active Directory, VMware or another hypervisor, Linux, and a team where I can own something end to end and be on call for it.
