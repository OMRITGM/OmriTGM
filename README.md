<h1 align="center">Omri Elcharizi</h1>

<p align="center">
  <a href="https://omrielcharizi.com"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=3A9BC7&center=true&vCenter=true&width=640&lines=System+Administrator+%C2%B7+Windows+Server%2C+Active+Directory%2C+VMware%2C+Linux;Three+years+keeping+24%2F7+operational+systems+available;Team+lead+of+four+technicians+in+the+Israeli+Air+Force" alt="tagline"></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/omri-elcharizi-sysadmin"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:omri7779@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://omrielcharizi.com"><img src="https://img.shields.io/badge/Portfolio-3a9bc7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
</p>

<table align="center">
  <tr>
    <td align="center"><b>3 yrs</b><br><sub>24/7 operational systems</sub></td>
    <td align="center"><b>4</b><br><sub>technicians led</sub></td>
    <td align="center"><b>~20</b><br><sub>workstations built by hand</sub></td>
    <td align="center"><b>19</b><br><sub>LXC containers at home</sub></td>
  </tr>
</table>

System administrator and team lead. Three years keeping operational air-defence systems, and the simulator, training and recording environments around them, available across several sites staffed around the clock. Active Directory, Windows Server, VMware vSphere and Red Hat Linux in production. Based in Ashdod, Israel. Available now.

## 🛠 Stack

**Systems and identity** &nbsp;
<img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows Server">
<img src="https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Active Directory">
<img src="https://img.shields.io/badge/Red_Hat-EE0000?style=flat-square&logo=redhat&logoColor=white" alt="Red Hat">
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu">

**Virtualization and containers** &nbsp;
<img src="https://img.shields.io/badge/VMware_vSphere-607078?style=flat-square&logo=vmware&logoColor=white" alt="VMware vSphere">
<img src="https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox VE">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Portainer-13BEF9?style=flat-square&logo=portainer&logoColor=white" alt="Portainer">

**Networking, scripting, automation** &nbsp;
<img src="https://img.shields.io/badge/TCP%2FIP_·_DNS_·_DHCP-005571?style=flat-square" alt="Networking">
<img src="https://img.shields.io/badge/Palo_Alto_(log_analysis)-FA582D?style=flat-square&logo=paloaltonetworks&logoColor=white" alt="Palo Alto">
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n">
<img src="https://img.shields.io/badge/Uptime_Kuma-5CDD8B?style=flat-square&logo=uptimekuma&logoColor=black" alt="Uptime Kuma">

## 💼 Experience

**Communications & IT Systems Technician, Team Lead** · Israeli Air Force · Aug 2023 – Apr 2026

- Led four technicians on systems staffed 24/7: shift planning, task allocation, on-the-job training, phone on-call. Certified maintenance inspector, signing off other technicians' work before a system returned to service.
- Active Directory: users, groups, permissions and the password-reset workflow.
- Built about 20 operator workstations from boot media: domain join, MAC and asset registration, endpoint check before release. Patch campaigns in a weekly maintenance window.
- VMware vSphere day to day, and wrote the vCenter startup procedure the team adopted.
- Red Hat servers over SSH: service status, systemctl restarts of the Tomcat tier, vendor scripts, log analysis.
- Took over a recording subsystem nobody owned: fixed its IP address mapping, restored it after a drive failure, traced the stations that would not come up to a shared control unit and a cable, wrote the runbook, trained a backup technician.

**Systems Technician, Reserve Duty** · Israeli Air Force · Apr 2026 – Sep 2026 (completed)
Same technical role; redesigned the screens of an internal system in daily use (HTML, CSS, scripting) with its operators.

## 🏠 Home lab

One Proxmox VE node, 19 LXC containers plus Docker stacks in Portainer. Nightly `vzdump` backups with a weekly off-site copy, and the restore is tested: a container comes back on a new ID and boots in about a minute. Uptime Kuma watches everything and alerts. An RTX 3060 is passed through to a container serving local language models with Ollama; n8n runs the automation.

Incident write-ups (driver and userland version mismatch, a cold-load stall after a disk migration, a volume shadowing a bundled database) are at [omrielcharizi.com](https://omrielcharizi.com).

## 🚀 Projects

| | |
|---|---|
| **[mail-classifier](https://github.com/OmriTGM/mail-classifier)** | n8n polls Gmail every 15 minutes, sends each new message to a local model on the RTX 3060 and applies a matching label. Retries with backoff, continues on failure, no API cost, no mail leaves the LAN. |
| **[preset-porter](https://github.com/OmriTGM/preset-porter)** | Fixes "Unsupported" Bambu Studio filament presets after switching printers. Runs entirely in the browser, hosted on Cloudflare Workers. [Live](https://3d.omrielcharizi.com/porter) |

## 🎓 Education

- Practical Engineer Diploma (Handesai), Electronics & Computers · Makif Alef Technological College, Ashdod · 2021–2023
- Maintenance Inspector Course · Israeli Air Force

## 🎯 Looking for

System Administrator or IT infrastructure, central or southern Israel: Windows Server and Active Directory, VMware or another hypervisor, Linux, and a team where I can own something end to end and be on call for it.
