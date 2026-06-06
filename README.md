# Still-Cracking-WPA2-Prevalence-and-Password-Weakness-in-2026
Still Cracking: WPA2 Prevalence and Password Weakness in 2026 BSIDES


**BSides Buffalo — June 2026**
**Presenter:** Dimitri Weaver


This repository accompanies the BSides Buffalo 2026 presentation on WPA2
prevalence, password weakness, and the PMKID attack vector. It serves as
a public reference index for sources cited or consulted during research
and talk preparation.

---

## Legal Framework

The following references cover the federal and state legal landscape
relevant to wireless security research in the United States.

- **Department of Justice — Computer Fraud and Abuse Act (CFAA) Policy**
  https://www.justice.gov/jm/jm-9-48000-computer-fraud

- **New York Penal Law § 156 — Computer Crimes**
  https://newyork.public.law/laws/n.y._penal_law_section_156.00

---

## The Vulnerability

References covering the PMKID attack discovery, technical disclosure,
and vendor response.

- **Fortinet PSIRT Advisory FG-IR-18-199**
  https://www.fortiguard.com/psirt/FG-IR-18-199

- **Hackers-Arise — Wi-Fi Hacking Part 11: The PMKID Attack**
  https://hackers-arise.com/wi-fi-hacking-part-11-the-pmkid-attack/

- **Cisco Meraki — Protecting Your Networks from the WPA1/WPA2 PSK Vulnerability (2018)**
  https://meraki.cisco.com/blog/2018/08/protecting-your-networks-from-the-latest-wpa1-wpa2-psk-vulnerability/

- **GIAC GSEC Paper — Wireless Security and IEEE 802.11 Standards**
  https://www.giac.org/paper/gsec/4214/wireless-security-ieee-80211-standards/106760

---

## PMKID — Technical References

References covering what PMKID is, how it is derived, and how it is
used within the 802.11i standard.

- **Cisco — PMKID and 802.11 Key Management Technical Note**
  https://www.cisco.com/c/en/us/support/docs/wireless-mobility/wireless-lan-wlan/116493-technote-technology-00.html

- **Cisco — Wireless Controller 7.6 Configuration Guide: Key Management**
  https://www.cisco.com/c/en/us/td/docs/wireless/controller/7-6/configuration-guide/b_cg76/b_cg76_chapter_01001111.html

- **CWNP — 802.11i Key Management (PDF)**
  https://www.cwnp.com/uploads/802-11i_key_management.pdf

- **CWNP — 802.11 RSN Fast Transition (PDF)**
  https://www.cwnp.com/uploads/802-11_rsn_ft.pdf

- **PMKSA Derivation and Storage in 802.11i**
  http://lets-start-to-learn.blogspot.com/2014/08/pmksa-derivation-and-storage-in-80211i.html

- **MDPI Electronics — WPA2 Security Analysis**
  https://www.mdpi.com/2079-9292/7/11/284

---

## Password Weakness Research

- **Lim et al. — "A False Sense of Security on Protected Wi-Fi Networks" (arXiv, January 2025)**
  https://arxiv.org/abs/2501.13363
  https://arxiv.org/html/2501.13363v1
  https://www.arxiv.org/pdf/2501.13363

---

## Attack Tooling and Methodology References

Included for educational and research documentation purposes only.

- **Null Byte — Cracking WPA2 Passwords Using the New PMKID Hashcat Attack**
  https://null-byte.wonderhowto.com/how-to/hack-wi-fi-cracking-wpa2-passwords-using-new-pmkid-hashcat-attack-0189379/

- **Hacking Articles — Wireless Penetration Testing: PMKID Attack**
  https://www.hackingarticles.in/wireless-penetration-testing-pmkid-attack/

- **DeepWiki — Wi-Fi Pentesting Guide: PMKID Attack**
  https://deepwiki.com/ricardojoserf/wifi-pentesting-guide/5.3-pmkid-attack

- **Scribd — Cracking WPA2 Passwords Using the PMKID Hashcat Attack**
  https://www.scribd.com/document/442568073/How-to-Hack-Wi-Fi-Cracking-WPA2-Passwords-Using-the-New-PMKID-Hashcat-Attack

---

## Phase 2 Research Path

This talk covers Phase 1 — passive beacon frame collection — only.
Phase 2 (active PMKID collection) requires institutional IRB sponsorship
and legal review.

---

## Responsible Use

All research described in this talk was conducted in compliance with
applicable federal and state law. Phase 1 passive collection is legally
equivalent to receiving a publicly broadcast radio signal. No network
access, payload capture, or PMKID collection was performed against
networks without authorization.

Tooling referenced in this repository is documented for research and
educational purposes. Do not capture or crack hashes from networks you
do not own or have explicit written authorization to test.

---

*Last updated: June 2026*
