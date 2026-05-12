<div align="center">

### 👨🏻‍💼 **Muhammad Noman Ilyas (AL-Cybision)**  
🛡️ *Application Security & Vulnerability Researcher*  

[![GitHub Followers](https://img.shields.io/github/followers/AL-Cybision?style=social)](https://github.com/AL-Cybision)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-noman-ilyas-alcybision/)

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

| CVE ID | Advisory | CVSS | Project | Summary | MITRE / NVD |
|---------|-----------|-------|----------|----------|--------------|
| **CVE-2025-11157** | [Fix PR #5643](https://github.com/feast-dev/feast/pull/5643) | ![CVSS 7.8](https://img.shields.io/badge/7.8-High-orange?style=flat-square) | [![Feast](https://img.shields.io/badge/Feast-purple?logo=python&style=flat-square)](https://github.com/feast-dev/feast) | Unsafe PyYAML deserialization in Kubernetes materializer enables arbitrary code execution | [nvd.nist.gov/vuln/detail/CVE-2025-11157](https://nvd.nist.gov/vuln/detail/CVE-2025-11157) |
| **CVE-2025-59420** | [GHSA-9ggr-2464-2j32](https://github.com/advisories/GHSA-9ggr-2464-2j32) | ![CVSS 7.5](https://img.shields.io/badge/7.5-High-orange?style=flat-square) | [![Authlib](https://img.shields.io/badge/Authlib-green?logo=python&style=flat-square)](https://github.com/authlib/authlib) | JWT/JWS accepts unknown `crit` headers → possible authz bypass | [nvd.nist.gov/vuln/detail/CVE-2025-59420](https://nvd.nist.gov/vuln/detail/CVE-2025-59420) |
| **CVE-2025-61920** | [GHSA-pq5p-34cr-23v9](https://github.com/advisories/GHSA-pq5p-34cr-23v9) | ![CVSS 7.5](https://img.shields.io/badge/7.5-High-orange?style=flat-square) | [![Authlib](https://img.shields.io/badge/Authlib-green?logo=python&style=flat-square)](https://github.com/authlib/authlib) | DoS via oversized JOSE segments | [nvd.nist.gov/vuln/detail/CVE-2025-61920](https://nvd.nist.gov/vuln/detail/CVE-2025-61920) |
| **CVE-2025-62706** | [GHSA-g7f3-828f-7h7m](https://github.com/advisories/GHSA-g7f3-828f-7h7m) | ![CVSS 6.5](https://img.shields.io/badge/6.5-Medium-yellow?style=flat-square) | [![Authlib](https://img.shields.io/badge/Authlib-green?logo=python&style=flat-square)](https://github.com/authlib/authlib) | `zip=DEF` decompression bomb enables DoS | [nvd.nist.gov/vuln/detail/CVE-2025-62706](https://nvd.nist.gov/vuln/detail/CVE-2025-62706) |

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
