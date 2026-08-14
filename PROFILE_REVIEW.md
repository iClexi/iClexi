# iClexi Profile Review

## Positioning

Recommended public positioning:

**Cybersecurity / Network Security / Infrastructure**

Do not lead with a generic "hacker" title. The visual identity can be hacker/terminal styled, but your repository evidence is stronger and more employable when presented as infrastructure + network security + security operations.

## Repositories with the strongest employment value

### Tier S — Feature prominently

1. **Proxmox**
   - Real homelab infrastructure documentation.
   - Proxmox, pfSense, TrueNAS, Wazuh, Cloudflare Tunnel, Docker, PostgreSQL and HA.
   - Strong evidence of infrastructure ownership and operations.

2. **Fortigate-Corporate-Policies**
   - Segmentation, firewall policies, WAF, Application Control, DNS filtering, DoS/scanner detection and logs.
   - Strong enterprise security signal.

3. **RDP-RemoteApp-NPS-Radius-Cisco-AAA-WindowsServer2025**
   - Windows Server 2025, AD DS, DNS, RDS, RemoteApp, RD Gateway, NPS/RADIUS and Cisco AAA.
   - Excellent cross-domain infrastructure + identity + networking project.

4. **DMVP-Hub-Spoke-IKEv2-Phase-3**
   - DMVPN Phase 3, IKEv2, IPsec, mGRE, NHRP and EIGRP.
   - Advanced networking and secure WAN signal.

5. **VPN-Fortigate-Site-To-Site**
   - Enterprise-relevant FortiGate IPsec design.
   - Good proof of firewall/VPN implementation and validation.

6. **VPN-Fortigate-WindowsClient-To-Site**
   - FortiGate + FortiClient remote access.
   - Strong practical remote-access security project.

### Tier A — Strong supporting evidence

7. **ARP-MITM-Attack**
   - Python-assisted ARP MitM lab plus DAI mitigation.
   - Stronger than a pure attack demo because it documents defensive control.

8. **DNS-Poisoning-Spoofing**
   - Python/Scapy, DNS manipulation and network-layer mitigation.
   - Good offensive/defensive protocol knowledge.

9. **Laboratorio-9-Adrian-Alcantara**
   - Terraform + Ansible + DigitalOcean.
   - Very useful for infrastructure/DevSecOps roles.

10. **Laboratorio-6-Adrian-Alcantara**
    - GnuPG, iptables/UFW, Snort and 2FA/PAM.
    - Good Linux security evidence.

11. **Laboratorio-5-Adrian-Alcantara**
    - Rsync, Heartbeat, Keepalived and Apache HA.
    - Good availability and Linux operations evidence.

12. **file-metadata-inspector**
    - Secure upload handling, PostgreSQL, ExifTool, session handling and secret hygiene.
    - Useful if applying to AppSec, secure development or general security engineering.

### Tier B — Useful as grouped series, not front-page cards

- VPN-IKEv1-Policy-Based
- VPN-IKEv1-Route-Based
- VPN-IKEv1-Tunnel-GRE
- VPN-IKEv2-Policy-Based
- VPN-IKEv2-Route-Based
- VPN-IKEv2-Tunnel-GRE
- DMVP-Hub-Spoke-IKEv1-Phase-2
- VPN-L2TP-LinuxClient-IKEv1-IPSec
- CDP-Attack
- DHCP-Spoofing-Attack
- DHCP-Starvation-Attack
- MAC-Flooding-Attack
- STP-Claim-Root-Attack
- VTP-Attack
- DTP-VLAN-Hopping

These are valuable collectively because they show breadth. Presenting every one as a featured project would make the profile feel repetitive, so the README groups them into **VPN Engineering** and **Network Attack / Defense Labs**.

### Tier C — Keep public, but do not feature

- Laboratorio-1 through Laboratorio-4: useful Linux foundation evidence, but too introductory for the first screen.
- Laboratorio-7: Samba/NFS/AD DC is useful, but your Windows Server + AAA and Proxmox repos are stronger.
- Laboratorio-8: Docker/Portainer/WordPress is useful foundation, but your Proxmox and deployed apps already prove more.
- Laboratorio-10: Issabel/Rocky Linux/DigitalOcean is useful niche infrastructure evidence, but not top-six material for a cybersecurity profile.
- COMANDOS-ESENCIALES
- Login
- Cifrado-Cesar

### Development projects

- **ritmohub** is technically strong and production-style, but it shifts the first impression toward full-stack development. Keep it visible through `iclexi.tech` or feature it when targeting security engineering/AppSec roles.
- **Portfolio** should be linked prominently as `iclexi.tech`, but the repository itself does not need to consume a featured card.
- **AgroD**, **PPT-Del-terror**, **videodrop**, **linksgood** and similar application projects show breadth, but are secondary for a network-security/infrastructure job profile.

## Recommended six GitHub pins

For cybersecurity / network-security / infrastructure applications:

1. Proxmox
2. Fortigate-Corporate-Policies
3. RDP-RemoteApp-NPS-Radius-Cisco-AAA-WindowsServer2025
4. DMVP-Hub-Spoke-IKEv2-Phase-3
5. VPN-Fortigate-WindowsClient-To-Site
6. ARP-MITM-Attack

Alternative:
Replace ARP-MITM-Attack with Laboratorio-9-Adrian-Alcantara when applying to infrastructure, cloud, DevOps or DevSecOps positions.

## Security hygiene before recruiters review the profile

Some lab READMEs currently contain literal lab passwords, pre-shared keys or example credentials.

Even when credentials are intentionally non-production, a recruiter can read this as weak secret-handling hygiene. Replace literal values with placeholders such as:

```text
<LAB_PSK>
<LAB_PASSWORD>
<DEMO_USER>
```

Then add a note such as:

> Credentials shown in this repository are sanitized placeholders for an isolated training environment.

Prioritize reviewing:
- RDP-RemoteApp-NPS-Radius-Cisco-AAA-WindowsServer2025
- VPN-Fortigate-Site-To-Site
- VPN-L2TP-LinuxClient-IKEv1-IPSec
- DMVPN/VPN repositories that display PSKs

## Naming cleanup

The `DMVP-*` repository names appear to intend `DMVPN-*`. Renaming them would improve searchability and polish if existing links/dependencies can be updated safely.

The `Laboratorio-X-Adrian-Alcantara` naming does not communicate what each repository contains. Long term, descriptive names would look more professional, for example:

- `linux-security-snort-2fa-lab`
- `linux-ha-keepalived-lab`
- `terraform-ansible-digitalocean-lab`

Do not rename everything at once if external links or coursework depend on the existing names.

## Public headline

Recommended:

**Cybersecurity | Network Security | Infrastructure**

Supporting line:

**Fortinet · Cisco · Linux · Windows Server · Proxmox**

Website:

**https://iclexi.tech**
