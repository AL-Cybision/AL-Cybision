<div align="center">

### 👨🏻‍💼 **Muhammad Noman Ilyas (AL-Cybision)**  
🛡️ *Application Security & Vulnerability Researcher*  

[![GitHub Followers](https://img.shields.io/github/followers/AL-Cybision?style=social)](https://github.com/AL-Cybision)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-noman-ilyas-alcybision/)

<br>

<img src="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/181324772" alt="OSWE Badge" width="120">

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
| [**CVE-2025-11157**](https://nvd.nist.gov/vuln/detail/CVE-2025-11157) | 🔴 **7.8 High** | 🍽️ [**Feast**](https://github.com/feast-dev/feast) | Unsafe PyYAML deserialization in Kubernetes materializer enables arbitrary code execution | [Fix PR #5643](https://github.com/feast-dev/feast/pull/5643) / [Huntr](https://huntr.com/bounties/46d4d585-b968-4a76-80ce-872bc5525564) |
| [**CVE-2025-59420**](https://nvd.nist.gov/vuln/detail/CVE-2025-59420) | 🔴 **7.5 High** | 🔐 [**Authlib**](https://github.com/authlib/authlib) | JWT/JWS accepts unknown `crit` headers → possible authz bypass | [GHSA-9ggr-2464-2j32](https://github.com/advisories/GHSA-9ggr-2464-2j32) |
| [**CVE-2025-61920**](https://nvd.nist.gov/vuln/detail/CVE-2025-61920) | 🔴 **7.5 High** | 🔐 [**Authlib**](https://github.com/authlib/authlib) | DoS via oversized JOSE segments | [GHSA-pq5p-34cr-23v9](https://github.com/advisories/GHSA-pq5p-34cr-23v9) |
| [**CVE-2025-62706**](https://nvd.nist.gov/vuln/detail/CVE-2025-62706) | 🟡 **6.5 Medium** | 🔐 [**Authlib**](https://github.com/authlib/authlib) | `zip=DEF` decompression bomb enables DoS | [GHSA-g7f3-828f-7h7m](https://github.com/advisories/GHSA-g7f3-828f-7h7m) |

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
