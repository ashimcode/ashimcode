<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050510,45:071b2e,75:00d9ff,100:ff1b72&height=210&section=header&text=ASHIM%20JOHN&fontSize=52&fontColor=00f3ff&fontAlignY=36&animation=fadeIn&desc=CYBERSECURITY%20%2F%20SYSTEMS%20%2F%20THE%20GRID&descSize=16&descColor=ffffff&descAlignY=61" alt="ashes cyber grid banner" />

![Grid status](https://img.shields.io/badge/GRID_STATUS-ONLINE-00f3ff?style=for-the-badge&logo=probot&logoColor=00f3ff&color=080b14)
![Focus](https://img.shields.io/badge/FOCUS-CYBER%20%7C%20INFRA%20%7C%20AUTOMATION-ff1b72?style=for-the-badge&logo=shield&logoColor=ffffff&color=080b14)
![Build mode](https://img.shields.io/badge/BUILD_MODE-HANDS--ON-7c5cff?style=for-the-badge&logo=github&logoColor=ffffff&color=080b14)

<br />

`SECURITY ANALYST IN TRAINING` · `GRID OPERATOR` · `INFRASTRUCTURE BUILDER`

</div>

<div align="center">

> I build practical cybersecurity environments, investigate the signals they produce, and turn complex systems into something observable, testable, and secure.

</div>

## ⚡ The Grid Tooling Matrix

| Sector | Capabilities and tools |
| :--- | :--- |
| **SIEM and telemetry** | Splunk HEC boundary validation · log collection · detection documentation · Graphiti memory |
| **Network defense** | Wireshark · packet capture analysis · TCP/IP · VLANs · ARP · ICMP |
| **Infrastructure** | Docker · Linux · WSL2 · Hyper-V host boundary · isolated-lab planning |
| **Automation and code** | Python · Bash · TypeScript · Node.js · Git · GitHub |
| **Memory and agents** | Graphiti · FalkorDB · Ollama · OpenClaw · permission-aware workflows |

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,bash,typescript,nodejs,docker,linux,git" alt="Python Bash TypeScript Node Docker Linux Git" />
</p>

## 🛡️ Executed Simulations and Investigations

### Local SIEM boundary and detection engineering

- Document a local Home SIEM architecture with explicit data boundaries and safe evidence handling.
- Verify a loopback Splunk HEC receiver with a labeled synthetic event; the Windows/Sysmon endpoint path remains an open prerequisite.
- Test a narrow suspicious-PowerShell detection against positive and negative synthetic fixtures before live telemetry validation.

### Network segmentation and packet analysis

- Inspect sanitized packet captures to validate 802.1Q VLAN tags, ARP behavior, and same-VLAN ICMP reachability.
- Troubleshoot a Guest wireless bridge VLAN mismatch and verify the minimal correction in a disposable GNS3 copy.
- Translate packet-level evidence into clear troubleshooting notes, hardening recommendations, and interview explanations.

### System hardening and isolated-lab design

- Apply public-repository hygiene checks, secret/path scanning, and sanitized evidence review.
- Document virtualization and telemetry boundaries before introducing endpoint collection or simulations.
- Prefer isolated, repeatable test environments before changing a live system.

## ◇ Infrastructure Outside the Screen

- Install and manage long-run Cat 6 Ethernet cabling, including 100-foot runs.
- Configure TP-Link and MadPower extenders as access points with wired backhaul.
- Diagnose the boundary between physical cabling, wireless topology, and endpoint behavior.

## 🚧 Current Builds

### Public cybersecurity portfolio

- [CYBR Projects](https://github.com/ashimcode/cybr-projects) — a sequential portfolio of home-SIEM investigation, network defense, incident response, cloud security, detection engineering, and security automation projects. The current Home SIEM work has a verified local Splunk HEC boundary and a documented Windows/Sysmon prerequisite gate; it does not claim endpoint telemetry completion yet.
- [Enterprise LAN Segmentation and Wireless Bridging Lab](https://github.com/ashimcode/ethernet-switching-wireless-bridging-lab) — a GNS3 proof of concept for VLAN isolation, 802.1Q trunking, wireless Layer 2 bridging, ARP and ICMP analysis, and future firewall enforcement. The repository documents the Guest-wireless VLAN mismatch, the minimal correction, five-reply runtime validation in both VLANs, MAC-learning evidence, an [interview walkthrough](https://github.com/ashimcode/ethernet-switching-wireless-bridging-lab/blob/main/docs/interview-walkthrough.md), and a [runtime validation record](https://github.com/ashimcode/ethernet-switching-wireless-bridging-lab/blob/main/docs/runtime-validation.md).
- [CarMechanicOS public snapshot](https://github.com/ashimcode/carmechanicos-public) — a sanitized browser-first mechanic-empire simulation built with vanilla HTML, CSS, and JavaScript, with local-first persistence, an optional authenticated Supabase boundary, and a documented public-release security workflow. Private development history and runtime credentials are intentionally excluded.

Public claims follow the same workflow as the projects: **Build → Verify → Capture evidence → Sanitize → Review → Publish**.

### Atlas personal AI brain

A local-first agent platform that combines structured behavior events, temporal Graphiti memory, FalkorDB, local Ollama inference, explicit permissions, human approvals, and a visual system graph. Atlas is designed to learn useful routines without confusing confidence or repeated approval with authority.

### Browser-based car mechanic tycoon

A collaborative browser game built with Rif, using node-based design maps to model systems, progression, and player decisions. The current CarMechanicOS prototype combines a desktop-style operating system shell with repair orders, inventory, logistics, global locations, factions, player progression, and risk systems.

#### CarMechanicOS toolchain

| Layer | Tools used | How it connects |
| :--- | :--- | :--- |
| **Game client** | HTML5 · Vanilla CSS · ES6+ JavaScript | Runs the desktop shell, simulation engines, windows, maps, CRM, inventory, and save/load state in the browser. |
| **Local runtime** | Node.js static server · Windows batch launchers | Serves the browser game locally on port `5501` for repeatable development. |
| **Public delivery** | Cloudflare Tunnel · `carmechanicos.com` | Routes the public HTTPS hostname to the local game server at `127.0.0.1:5501`. |
| **Cloud persistence** | Supabase · REST API · PostgreSQL · Row Level Security | Optional `backend.js` adapter upserts player snapshots into `public.player_saves`; localStorage remains the fallback. |
| **Source and delivery** | Git · GitHub | Stores the game source, documentation, screenshots, launch scripts, and architecture history. |
| **Future intelligence boundary** | Atlas · Graphiti · FalkorDB · OpenClaw · Ollama | Can observe project status and structured events through explicit interfaces without receiving private game or hosting credentials. |

```text
CarMechanicOS browser
  ├─ localStorage ─────────────── local save fallback
  └─ backend.js ── HTTPS ─────── Supabase player_saves

Cloudflare Tunnel ─────────────── carmechanicos.com → localhost:5501

Git/GitHub ───────────────────── source, docs, screenshots, release history
Atlas / Graphiti / FalkorDB ─── optional structured memory and project context
```

Supabase is prepared but intentionally requires a browser-safe Publishable/anon key in the ignored local `backend-config.js`. Secret and service-role keys are never placed in the frontend or committed to Git.

### Hardware analysis

Hands-on PlayStation 5 maintenance and teardown work, including analysis of internal air-pressure sensor mechanics in compact electronics.

## 🧭 Operating Principles

- **Infrastructure first:** understand the environment before automating it.
- **Evidence over assumption:** prefer logs, packets, hashes, test results, and reproducible observations.
- **Isolation by default:** use containers, virtual machines, and sandboxes for risky experiments.
- **Clear boundaries:** separate read, prepare, write, delete, and execute capabilities.
- **Professional focus:** technical profiles emphasize cybersecurity, systems, cabling, and practical projects.
- **Active ownership:** manage hosting, project operations, academic requirements, and department communications directly.

</div>

<div align="center">

`╔════════════════════════════════════════════════════════════╗`  
`║  OBSERVE  →  MODEL  →  TEST  →  HARDEN  →  BUILD AGAIN  ║`  
`╚════════════════════════════════════════════════════════════╝`

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff1b72,45:7c5cff,100:050510&height=110&section=footer" alt="Neon grid footer" />

</div>
