<div align="center">

### 👨🏻‍💼 **Muhammad Noman Ilyas (AL-Cybision)**  
🛡️ *Application Security & Vulnerability Researcher*  
🔗 *Huntr Profile : https://huntr.com/users/al-cybision*
🔗 *HackerOne Profile : https://hackerone.com/al_cybision*

[![GitHub Followers](https://img.shields.io/github/followers/AL-Cybision?style=social)](https://github.com/AL-Cybision)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-noman-ilyas-alcybision/)

<br>
<a href="https://www.credential.net/0e714f8e-bc27-4762-9b68-1e92d80f34ca#acc.cXCy3awt">
  <img src="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/181324772" alt="OSWE Badge" width="120">
</a>
<br>

<div align="center">

<b style="background-color:#f3f4f6; padding:6px 10px; border-radius:6px;">🔍 SECURE CODE REVIEW</b>
&nbsp;&nbsp;
<b style="background-color:#f3f4f6; padding:6px 10px; border-radius:6px;">🛡️ VULNERABILITY RESEARCH</b>
&nbsp;&nbsp;
<b style="background-color:#f3f4f6; padding:6px 10px; border-radius:6px;">🤖 AI/ML MODEL FILE VULNS</b>

</div>


</div>

---

### **Highlights**

#### 🪲 Vulnerabilities Discovered

| CVE ID | CVSS | Project | Summary | References |
|--------|------|---------|---------|------------|
| [**CVE-2026-6691**](https://www.cve.org/cverecord?id=CVE-2026-6691) | 🔴 **8.6 High** | 🍃 [**MongoDB C Driver**](https://github.com/mongodb/mongo-c-driver) | Cyrus SASL username canonicalization heap buffer overflow via unsafe string copy leads to RCE & DoS | [CDRIVER-6134](https://jira.mongodb.org/browse/CDRIVER-6134) |
| [**CVE-2025-11157**](https://nvd.nist.gov/vuln/detail/CVE-2025-11157) | 🔴 **7.8 High** | 🍽️ [**Feast**](https://github.com/feast-dev/feast) | Unsafe PyYAML deserialization in Kubernetes materializer enables arbitrary code execution | [Fix PR #5643](https://github.com/feast-dev/feast/pull/5643) / [Huntr Report](https://huntr.com/bounties/46d4d585-b968-4a76-80ce-872bc5525564) |
| [**CVE-2025-59420**](https://nvd.nist.gov/vuln/detail/CVE-2025-59420) | 🔴 **7.5 High** | 🔐 [**Authlib**](https://github.com/authlib/authlib) | JWT/JWS accepts unknown `crit` headers → possible authz bypass | [GHSA-9ggr-2464-2j32](https://github.com/advisories/GHSA-9ggr-2464-2j32) |
| [**CVE-2025-61920**](https://nvd.nist.gov/vuln/detail/CVE-2025-61920) | 🔴 **7.5 High** | 🔐 [**Authlib**](https://github.com/authlib/authlib) | DoS via oversized JOSE segments | [GHSA-pq5p-34cr-23v9](https://github.com/advisories/GHSA-pq5p-34cr-23v9) |
| [**CVE-2025-62706**](https://nvd.nist.gov/vuln/detail/CVE-2025-62706) | 🟡 **6.5 Medium** | 🔐 [**Authlib**](https://github.com/authlib/authlib) | `zip=DEF` decompression bomb enables DoS | [GHSA-g7f3-828f-7h7m](https://github.com/advisories/GHSA-g7f3-828f-7h7m) |

#### 🌐 Independent Recognition & Security References

Public references below document upstream reporter credits, vendor security responses, and independent vulnerability listings.

| Organization / source | Vulnerability | Type of reference | Public record |
|---|---|---|---|
| **IBM — Instana OnPrem** | CVE-2026-6691 | Enterprise product security bulletin | [View reference](https://www.ibm.com/support/pages/node/7280794) |
| **IBM — watsonx.data** | CVE-2025-61920 | Dedicated product security bulletin | [View reference](https://www.ibm.com/support/pages/node/7260258) |
| **IBM — watsonx Orchestrate** | CVE-2025-59420 | Developer Edition security bulletin | [View reference](https://www.ibm.com/support/pages/security-bulletin-multiple-vulnerabilities-ibm-watsonx-orchestrate-developer-edition-2) |
| **IBM — watsonx Orchestrate** | CVE-2025-61920, CVE-2025-62706 | Developer Edition security bulletin | [View reference](https://www.ibm.com/support/pages/node/7259416) |
| **IBM — watsonx Code Assistant** | CVE-2025-59420, CVE-2025-61920 | On-premises product security bulletin | [View reference](https://www.ibm.com/support/pages/security-bulletin-multiple-vulnerabilities-ibm-watsonx-code-assistant-prem-2) |
| **IBM — watsonx Code Assistant** | CVE-2025-61920, CVE-2025-62706 | Official release notes listing security fixes | [View reference](https://www.ibm.com/docs/en/software-hub/5.3.x?topic=new-watsonx-code-assistant) |
| **Red Hat — OpenShift AI** | CVE-2025-11157 | Enterprise security advisory RHSA-2026:10184 | [View reference](https://access.redhat.com/errata/RHSA-2026:10184) |
| **Red Hat — Security Response** | CVE-2025-11157 | Public vulnerability tracking issue | [View reference](https://bugzilla.redhat.com/show_bug.cgi?id=2426574) |
| **Snyk** | CVE-2025-11157 | **Names Muhammad Noman Ilyas in researcher credit** | [View reference](https://security.snyk.io/vuln/SNYK-PYTHON-FEAST-14830622) |
| **Authlib (upstream)** | CVE-2025-59420 | **Credits AL-Cybision as reporter** | [View reference](https://github.com/authlib/authlib/security/advisories/GHSA-9ggr-2464-2j32) |
| **Authlib (upstream)** | CVE-2025-61920 | **Credits AL-Cybision as reporter** | [View reference](https://github.com/authlib/authlib/security/advisories/GHSA-pq5p-34cr-23v9) |
| **Authlib (upstream)** | CVE-2025-62706 | **Credits AL-Cybision as reporter** | [View reference](https://github.com/authlib/authlib/security/advisories/GHSA-g7f3-828f-7h7m) |
| **go-jose (upstream)** | JOSE `b64` header issue (non-CVE) | **Credits Muhammad Noman Ilyas as reporter** in merged fix | [View reference](https://github.com/go-jose/go-jose/pull/210) |
| **SUSE Linux Enterprise** | CVE-2025-62706 | Security update and fixed `python-Authlib` packages | [View reference](https://www.suse.com/security/cve/CVE-2025-62706.html) |
| **Ubuntu / Canonical** | CVE-2026-6691 | Distribution vulnerability tracking | [View reference](https://ubuntu.com/security/CVE-2026-6691) |
| **Debian Security Tracker** | CVE-2026-6691 | Distribution package status and fixes | [View reference](https://security-tracker.debian.org/tracker/CVE-2026-6691) |
| **Debian Security Tracker** | CVE-2025-59420 | Distribution package status and fixes | [View reference](https://security-tracker.debian.org/tracker/CVE-2025-59420) |
| **Debian Security Tracker** | CVE-2025-61920 | Distribution package status and fixes | [View reference](https://security-tracker.debian.org/tracker/CVE-2025-61920) |
| **Debian Security Tracker** | CVE-2025-62706 | Distribution package status and fixes | [View reference](https://security-tracker.debian.org/tracker/CVE-2025-62706) |
| **INCIBE-CERT (Spain)** | CVE-2026-6691 | National cybersecurity vulnerability entry | [View reference](https://www.incibe.es/en/incibe-cert/early-warning/vulnerabilities/cve-2026-6691) |
| **INCIBE-CERT (Spain)** | CVE-2025-11157 | National cybersecurity vulnerability entry | [View reference](https://www.incibe.es/en/incibe-cert/early-warning/vulnerabilities/cve-2025-11157) |
| **GitHub Advisory Database** | CVE-2025-11157 | Reviewed Feast package security advisory | [View reference](https://github.com/advisories/GHSA-34wm-4hw7-qfjv) |
| **GitLab Advisory Database** | CVE-2025-59420, CVE-2025-61920, CVE-2025-62706 | Published Authlib package advisories | [View reference](https://advisories.gitlab.com/pkg/pypi/authlib/) |
| **Tenable** | CVE-2025-62706 | SUSE package-security detection advisory | [View reference](https://www.tenable.com/plugins/nessus/271948) |
| **NIST National Vulnerability Database** | CVE-2025-11157 | National vulnerability record for Feast | [View reference](https://nvd.nist.gov/vuln/detail/CVE-2025-11157) |

#### 🔒 Private Validated Findings

| Status | Area | Public-safe summary |
|---------|------|---------------------|
| **Private / Validated** | joblib model-file security | Load-time model artifact deserialization issue leading to code-execution risk and scanner-evasion behavior. Technical details withheld until disclosure. |
| **Private / Validated** | Keras `.keras` model-file security | Safe-mode model-loading bypass class involving model configuration/data-loading behavior, aligned with later public Keras CVE-2025-12058 research. Technical details withheld until disclosure. |

---

### 🤝 **Contributions**

| Project | Description | Version | Link |
|----------|--------------|----------|------|
| [![Go-Jose](https://img.shields.io/badge/Go-Jose-blue?logo=go&style=flat-square)](https://github.com/go-jose/go-jose) | Fixed bug: `b64` header ignored in unprotected header (now rejected). | ![v4.1.3](https://img.shields.io/badge/v4.1.3-success?style=flat-square) | [PR #210](https://github.com/go-jose/go-jose/pull/210#pullrequestreview-3315913843) |
| [![Authlib](https://img.shields.io/badge/Authlib-green?logo=python&style=flat-square)](https://github.com/authlib/authlib) | Collaborated on patch for critical header validation bypass. | ![v1.6.4](https://img.shields.io/badge/v1.6.4-success?style=flat-square) | [PR #823](https://github.com/authlib/authlib/pull/823) |

---
