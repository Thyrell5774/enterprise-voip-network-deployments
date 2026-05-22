# Enterprise VoIP & Network Deployments — 20+ Clients

![FreePBX](https://img.shields.io/badge/FreePBX-Multi--Site-FF6600?style=flat-square)

![Grandstream](https://img.shields.io/badge/Grandstream-UCM-0066CC?style=flat-square)

![MikroTik](https://img.shields.io/badge/MikroTik-RouterOS-CC0000?style=flat-square)

![UniFi](https://img.shields.io/badge/UniFi-Wireless-0059C1?style=flat-square)

![SIP](https://img.shields.io/badge/SIP-Trunking-4CAF50?style=flat-square)


**Role:** VoIP & Network Engineer  
**Scale:** 20+ clients · 5–20 branches per client · 10+ users per branch  
**Type:** Mixed — FreePBX hosted & on-site · Grandstream UCM · MikroTik VPN  
**Status:** Delivered and maintained across all clients  

---

## Overview

This repository documents a track record of 20+ enterprise VoIP and 
network deployments delivered for clients across South Africa. Each 
deployment was scoped, designed, physically installed, and configured 
end-to-end — from structured cabling and cabinet builds through to 
full PBX configuration, VPN setup, and user training.

Clients ranged from small businesses with a single site to enterprises 
with 20 branches. Some were new site builds, some were office moves, 
and some were upgrades from legacy phone systems. No two were identical — 
each required its own design based on the client's connectivity, 
hardware, and call flow requirements.

---

## Deployment Profile

| Factor | Range |
|---|---|
| Total clients delivered | 20+ |
| Branches per client | 5 — 20 |
| Users per deployment | 10+ per branch |
| PBX platforms used | FreePBX (hosted & on-site) · Grandstream UCM |
| Branch routers | MikroTik hEX |
| Phones | Yealink · Grandstream · Softphones · Mix |
| Connectivity | VPN · Public IP · Both |
| Cabling | Full structured cabling on new sites and moves |
| Wireless | UniFi APs · Cabinet switches on all sites |

---

## What Each Deployment Typically Included

### Physical Installation
- ✅ Structured cabling — all cable runs personally installed 
  on new sites and office moves
- ✅ Network cabinet builds — patch panels, switches, routers, 
  UPS, cable management
- ✅ UniFi access point mounting and cabling throughout site
- ✅ PoE switch installation and uplink configuration
- ✅ Full cable testing before any device goes live

### Network Configuration
- ✅ MikroTik hEX router setup and internet connectivity
- ✅ Site-to-site VPN configuration back to head office or 
  hosted PBX
- ✅ Public IP SIP configuration where VPN was not available
- ✅ NAT rules for remote device access
- ✅ QoS configuration — VoIP traffic prioritised over data
- ✅ Firewall rules and basic network security
- ✅ UniFi wireless deployment and SSID configuration

### VoIP Configuration
- ✅ FreePBX or Grandstream UCM — full system setup per client
- ✅ Extension deployment per user across all branches
- ✅ SIP trunk configuration and testing
- ✅ IVR menus with custom voice recordings per client
- ✅ Ring groups and call queues per branch
- ✅ Inbound DID routing per branch or department
- ✅ Outbound routes with correct caller ID per site
- ✅ Call recording where required
- ✅ Music on hold per client
- ✅ Time-based routing — business hours and after-hours
- ✅ Phone auto-provisioning via EPM or UCM Zero Config
- ✅ Softphone deployment for remote and mobile users

---

## Deployment Types

### New Site Builds
Full end-to-end installation from empty office to live network 
and phones — cabling, cabinets, switching, wireless, router, 
VPN, and full PBX configuration. Client goes from nothing to 
a complete working system in a single engagement.

### Office Moves
Decommission existing site, relocate and rebuild cabinet, 
re-run all cabling in new premises, reconfigure network and 
VPN to match new layout, and restore full VoIP service with 
minimal downtime.

### System Upgrades
Replace legacy analogue or on-premise phone systems with 
hosted or on-site IP PBX. Migrate existing numbers, rebuild 
call flows, deploy new IP phones, and train staff on the 
new system.

### Branch Additions
Add new branches to an existing client's PBX — VPN or public 
IP connectivity, extension allocation, IVR and ring group 
updates, phone provisioning, and testing.

---

## Common Challenges & Solutions

**Challenge:** On new site builds, long cable runs through 
ceilings, walls, and conduit frequently resulted in damaged 
cables or continuity faults discovered only after installation.  
**Solution:** Every run tested with a cable tester before 
termination and patching. Faults identified and re-pulled 
before the cabinet was built — no faulty runs made it to 
the live network.

---

**Challenge:** Public IP branch phones frequently experienced 
SIP registration drops and one-way audio due to NAT traversal 
issues on varied ISP connections.  
**Solution:** SIP keepalive enabled on all remote phones, 
NAT traversal configured on the PBX, and STUN enabled for 
softphone clients — registration and audio issues resolved 
consistently across all deployments.

---

**Challenge:** Delivering consistent VoIP call quality across 
clients with varying internet link quality — some branches 
on lower-bandwidth connections experienced call degradation 
during peak usage.  
**Solution:** QoS configured on all MikroTik routers using 
DSCP EF marking — VoIP packets prioritised at the router 
level so voice traffic is never queued behind data regardless 
of link congestion.

---

**Challenge:** Auto-provisioning a mix of Yealink, Grandstream, 
and softphone clients across large deployments would be 
unmanageable if done manually per device.  
**Solution:** FreePBX EPM and Grandstream UCM Zero Config 
used on all deployments — MAC addresses registered, templates 
built per phone model, and config pushed automatically on 
first boot. Large deployments completed without manual 
programming on any device.

---

**Challenge:** Office moves required full VoIP service to be 
restored in the new premises as quickly as possible to minimise 
business disruption.  
**Solution:** New site cabled and cabinet pre-built before 
move day where possible. VPN and PBX config prepared in 
advance — on move day, hardware connected and tested, 
phones online and registered within hours.

---

## Key Outcomes Across All Deployments

- **20+ clients** delivered end-to-end — scoped, cabled, 
  configured, and handed over
- **Zero legacy analogue systems** remaining on any upgraded 
  client — all moved to IP PBX
- **Consistent call quality** across all sites via MikroTik 
  QoS on every deployment
- **Minimal downtime** on office moves through advance 
  preparation and structured process
- **No manual phone programming** on any deployment — 
  all devices auto-provisioned via EPM or Zero Config
- **Full structured cabling** personally installed on all 
  new builds and moves

---

## Related Projects

| Project | Scale | Stack |
|---|---|---|
| 🔧 [FreePBX Enterprise Multi-Site VoIP](https://github.com/Thyrell5774/freepbx-enterprise-multisite) | 11 branches · 180+ users | FreePBX · MikroTik · SIP |
| 🔧 [MikroTik Multi-Site VPN Network](https://github.com/Thyrell5774/mikrotik-vpn-multisite) | 11 sites · 165+ users | MikroTik · L2TP · QoS |
| 🔧 [Grandstream UCM Enterprise Deployment](https://github.com/Thyrell5774/grandstream-ucm-enterprise) | 10 branches · 150+ users | Grandstream UCM · MikroTik · SIP |
| 🔧 [UniFi Hotel Enterprise Network](https://github.com/Thyrell5774/unifi-hotel-enterprise-network) | 2 blocks · 3 floors · 22 APs | UniFi · UDM-SE · Grandstream |
| 🔧 [Multi-Tenant FreePBX — Business Group](https://github.com/Thyrell5774/multitenant-freepbx-business-group) | 5 tenants · 75+ users | FreePBX · VPN · DID |

---

## About

**Thyrell Naidoo** — Senior Network & VoIP Engineer, Johannesburg SA  
7+ years managing enterprise VoIP and networking infrastructure across South Africa.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-thyrellnaidoo-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/thyrellnaidoo)

[![Credly](https://img.shields.io/badge/Credly-Certifications-FF6B00?style=flat-square&logo=credly)](https://credly.com/users/thyrell-naidoo)

[![Email](https://img.shields.io/badge/Email-Thyrell.naidoo@gmail.com-D14836?style=flat-square&logo=gmail)](mailto:Thyrell.naidoo@gmail.com)
