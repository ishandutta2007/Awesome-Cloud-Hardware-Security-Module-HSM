# Awesome-Cloud-Hardware-Security-Module-HSM

# Awesome-Cloud-Hardware-Security-Module-HSM 🔐 🏛️

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Cloud Hardware Security Module HSM Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Hardware-Security-Module-HSM"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Cloud-Hardware-Security-Module-HSM?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Hardware-Security-Module-HSM/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Cloud-Hardware-Security-Module-HSM?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Hardware-Security-Module-HSM/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Cloud-Hardware-Security-Module-HSM?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Cloud Hardware Security Module (HSM) Ecosystem

**Curated List of Commercial HSM Platforms & Open-Source Cryptographic Key Management Tools**  
*Focused on Key Management as a Service, PKCS#11 Integration, Post-Quantum Cryptography, Payment HSM & Self-Hosted Software HSMs*  

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **cloud hardware security modules**, **open-source PKCS#11 tools**, and **cryptographic key management frameworks**. The HSM-as-a-Service market is growing rapidly due to **technological improvements in encryption**, **increasing cybersecurity threats**, **cloud adoption**, and **regulatory pressure** (GDPR, HIPAA, PCI DSS). Whether you are looking for enterprise-grade commercial solutions (such as *AWS CloudHSM*, *Azure Dedicated HSM*, and *Thales CipherTrust*), or self-hostable open-source alternatives (like *SoftHSMv2*, *FreeHSM-C*, and *BouncyHsm*), this list covers category leaders, PKCS#11 integrations, and privacy-respecting cryptographic infrastructure.

**Key Market Drivers & Trends:**
- **Post-Quantum Cryptography (PQC) readiness** is a major procurement consideration. Vendors like Thales and Utimaco have committed to PQC-capable firmware updates, with **PQC-ready vs PQC-legacy tiers** already influencing buying decisions in European financial institutions and US federal agencies.
- **Embedded HSM integration** is expanding into IoT, automotive, and industrial automation, driven by regulations like the **EU Cyber Resilience Act** and GSMA IoT Security Guidelines.
- **Blockchain and digital asset security** is a fast-growing demand vector, with institutional custodians and CBDC programs standardizing on HSMs for private key storage and transaction signing.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The HSM-as-a-Service market is dominated by established hardware security vendors and cloud hyperscalers. Key players include **Entrust, Utimaco, IBM, Thales, Futurex, Fortanix, and Atos**. The market is evolving from **hardware-centric to service-centric paradigms**, driven by cloud adoption, remote HSM management, and multi-tenant architectures.

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[AWS CloudHSM](https://aws.amazon.com/cloudhsm/)** ☁️ | Amazon | ~$2.0 Trillion | **$1.45/hour per HSM instance** | **30-day free trial for new customers** | **AWS-native dedicated HSM** — Single-tenant, FIPS 140-2 Level 3 validated. **PKCS#11, JCE, and CNG** interfaces. Customer-controlled keys with no AWS visibility. |
| **[Azure Dedicated HSM](https://azure.microsoft.com/en-us/services/hsm/)** 🔷 | Microsoft | ~$3.90 Trillion | **Custom enterprise pricing** | **Trial available** | **Azure-native dedicated HSM** — FIPS 140-2 Level 3. **Thales SafeNet Luna Network HSM 7** appliance. Dedicated to a single customer. |
| **[Google Cloud HSM](https://cloud.google.com/kms/docs/hsm)** 🌐 | Google (Alphabet) | ~$2.0 Trillion | **$1.60/HSM key version/month** (Cloud KMS HSM tier) | **$300 free credits** for new customers | **GCP-native HSM-backed keys** — FIPS 140-2 Level 3. Integrated into **Cloud KMS** for seamless key management. **Multi-tenant but key-isolated**. |
| **[Thales CipherTrust Cloud Key Manager](https://cpl.thalesgroup.com/)** 🏛️ | Thales Group | ~$3 Billion | **Custom enterprise pricing** | **Demo available** | **Enterprise key lifecycle management** — Centralized control across multi-cloud (AWS, Azure, GCP). **Luna Network HSM 7** and **payShield 10K** platforms. **PQC-capable firmware updates** for future-proofing. |
| **[Fortanix DSM](https://www.fortanix.com/)** 🛡️ | Fortanix | Private | **Custom enterprise pricing** | **Free trial available** | **Data Security Manager** — Multi-cloud HSM-as-a-Service. **FIPS 140-2 Level 3**. **REST API**, PKCS#11, and JCE interfaces. **Confidential computing** support. |
| **[Utimaco HSM](https://utimaco.com/)** 🔵 | Utimaco | Private | **Custom enterprise pricing** | **Demo available** | **Enterprise HSM platform** — **CryptoServer Se-Series** with native **ML-KEM and ML-DSA** (PQC) support. Used in defense, banking, and government sectors. |
| **[Futurex](https://www.futurex.com/)** 🟢 | Futurex | Private | **Custom enterprise pricing** | **Demo available** | **Enterprise HSM and key management** — **Vectera Plus** and **KMES Series 3**. FIPS 140-2 Level 3. **Payment HSM** for PCI DSS compliance. |
| **[Entrust nShield as a Service](https://www.entrust.com/)** 🔐 | Entrust | ~$1 Billion | **Custom enterprise pricing** | **Demo available** | **Cloud HSM service** — **nShield Connect** hardware and **nShield as a Service** cloud option. FIPS 140-2 Level 3. **CodeSafe** secure execution environment. |
| **[Securosys CloudHSM](https://www.securosys.com/)** 🏔️ | Securosys | Private | **Custom enterprise pricing** | **Demo available** | **Swiss-made HSM platform** — **Primus HSM** with FIPS 140-2 Level 3 and **Swiss banking-grade** security. **HashiCorp Vault integration** via REST-based plugin. |
| **[Marvell LiquidSecurity](https://www.marvell.com/)** ⚙️ | Marvell | ~$50 Billion | **Custom enterprise pricing** | **Demo available** | **Cloud-optimized HSM** — **LiquidSecurity** network HSM appliances for cloud and data center. **Multi-tenant architecture** for service providers. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[SoftHSMv2](https://github.com/softhsm/SoftHSMv2)** [![Stars](https://img.shields.io/github/stars/softhsm/SoftHSMv2?style=social&color=white)](https://github.com/softhsm/SoftHSMv2/stargazers)  
  **Software implementation of a generic cryptographic device with a PKCS#11 interface**, BSD-2-Clause licensed. **790+ stars**. **The reference open-source SoftHSM** — designed to meet OpenDNSSEC requirements but works with any PKCS#11-compatible product. **Supports PKCS#11 v2.40**. **Used for testing, development, and lightweight production scenarios** where dedicated hardware is not required. **Available in Fedora, Debian, and Ubuntu repositories**. 🏛️

- **[FreeHSM-C](https://github.com/afchine1337/freehsm-c)** [![Stars](https://img.shields.io/github/stars/afchine1337/freehsm-c?style=social&color=white)](https://github.com/afchine1337/freehsm-c/stargazers)  
  **Native C11 re-implementation of the FreeHSM PKCS#11 v3.2 Soft HSM**, Apache-2.0 licensed. **Designed to pass FIPS 140-3 Level 1 evaluation** and **augmented Common Criteria EAL4+ certification (ALC_FLR.2 + AVA_VAN.5)**. **PKCS#11 module for YubiKey PIV applet**. **Newly accepted into Debian unstable** (June 2026). **The most certification-focused open-source HSM implementation** — aimed at regulated environments. 🎯

- **[BouncyHsm](https://github.com/harrison314/BouncyHsm)** [![Stars](https://img.shields.io/github/stars/harrison314/BouncyHsm?style=social&color=white)](https://github.com/harrison314/BouncyHsm/stargazers)  
  **Software simulator of HSM and smartcard simulator with HTML UI, REST API and PKCS#11 interface**, MIT licensed. **.NET-based** HSM simulator with web management interface. **PKCS#11 v2.40 interface**. **REST API for programmatic control**. **Ideal for development, testing, and CI/CD pipelines** where a software HSM is sufficient. 🎮

- **[pkcs11-provider (OpenSSL 3.0+)](https://github.com/latchset/pkcs11-provider)** [![Stars](https://img.shields.io/github/stars/latchset/pkcs11-provider?style=social&color=white)](https://github.com/latchset/pkcs11-provider/stargazers)  
  **A PKCS#11 provider for OpenSSL 3.0+**, Apache-2.0 licensed. **Enables OpenSSL 3.x to use PKCS#11 tokens (HSMs, smartcards) as cryptographic providers**. **Bridges the gap between modern OpenSSL and HSM hardware**. **Essential for applications migrating to OpenSSL 3.x** while requiring HSM-backed keys. 🔗

- **[pkcs11mod](https://github.com/namecoin/pkcs11mod)** [![Stars](https://img.shields.io/github/stars/namecoin/pkcs11mod?style=social&color=white)](https://github.com/namecoin/pkcs11mod/stargazers)  
  **Go library for creating PKCS#11 modules**, MIT licensed. **Enables writing PKCS#11 modules in Go**. **Bridges Go applications with HSM hardware** without CGO complexity. **Used by Namecoin for cryptographic operations**. 🦫

- **[pkcs11-helper](https://github.com/OpenSC/pkcs11-helper)** [![Stars](https://img.shields.io/github/stars/OpenSC/pkcs11-helper?style=social&color=white)](https://github.com/OpenSC/pkcs11-helper/stargazers)  
  **Library that simplifies the interaction with PKCS#11 providers**, GPL-2.0 licensed. **Abstracts PKCS#11 complexity** for applications. **Used by OpenVPN, OpenSC, and other security tools**. **The standard helper library for PKCS#11 integration**. 🛠️

- **[pkcs11-tools](https://github.com/opendnssec/pkcs11-tools)** [![Stars](https://img.shields.io/github/stars/opendnssec/pkcs11-tools?style=social&color=white)](https://github.com/opendnssec/pkcs11-tools/stargazers)  
  **A set of tools to manage objects on PKCS#11 cryptographic tokens**, BSD-2-Clause licensed. **162+ stars**. **Compatible with many PKCS#11 libraries** including major HSM brands, NSS, and SoftHSM. **Command-line utilities for key and certificate management**. **The Swiss army knife for PKCS#11 token administration**. 🧰

- **[pkcs11-proxy](https://github.com/SUNET/pkcs11-proxy)** [![Stars](https://img.shields.io/github/stars/SUNET/pkcs11-proxy?style=social&color=white)](https://github.com/SUNET/pkcs11-proxy/stargazers)  
  **Network proxy for a PKCS#11 library**, BSD-2-Clause licensed. **Enables remote access to PKCS#11 tokens** over the network. **Client-server architecture** for distributed HSM access. **Used in Docker/Kubernetes environments** where HSM hardware is centralized. 🌐

- **[hsmwiz](https://github.com/johndoe31415/hsmwiz)** [![Stars](https://img.shields.io/github/stars/johndoe31415/hsmwiz?style=social&color=white)](https://github.com/johndoe31415/hsmwiz/stargazers)  
  **Frontend for OpenSC, pkcs11tool and pkcs15tool**, GPL-3.0 licensed. **Simplifies handling of HSM smartcards**. **Wraps complex PKCS#11 commands** into intuitive operations. **Useful for Nitrokey HSM and similar devices**. 🪄

- **[Vault PKCS#11 Plugin](https://github.com/mode51software/vaultplugin-hsmpki)** [![Stars](https://img.shields.io/github/stars/mode51software/vaultplugin-hsmpki?style=social&color=white)](https://github.com/mode51software/vaultplugin-hsmpki/stargazers)  
  **HashiCorp Vault PKI plugin with HSM support**, MIT licensed. **Overlays the built-in PKI plugin** to enable certificate signing using a Hardware Security Module via PKCS#11. **Bridges Vault's PKI engine with HSM-backed keys**. **Essential for zero-trust architectures requiring hardware-rooted certificate authorities**. 🔐

- **[Securosys hcvault-plugin-secrets-engine](https://github.com/securosys-com/hcvault-plugin-secrets-engine)** [![Stars](https://img.shields.io/github/stars/securosys-com/hcvault-plugin-secrets-engine?style=social&color=white)](https://github.com/securosys-com/hcvault-plugin-secrets-engine/stargazers)  
  **HashiCorp Vault Secrets Engine plugin for REST-based Securosys HSM and CloudsHSM integration**, Apache-2.0 licensed. **Enhanced features: ECIES, multi-authorization**. **Enables Vault to use Securosys HSM for secrets encryption and key management**. **Production-proven integration** for Swiss banking-grade security. 🇨🇭

- **[pkcs11-key-wrap](https://github.com/smallstep/pkcs11-key-wrap)** [![Stars](https://img.shields.io/github/stars/smallstep/pkcs11-key-wrap?style=social&color=white)](https://github.com/smallstep/pkcs11-key-wrap/stargazers)  
  **Wrap keys from HSM using CKM_RSA_AES_KEY_WRAP step by step**, Apache-2.0 licensed. **Demonstrates secure key export/import from HSM**. **CKM_RSA_AES_KEY_WRAP mechanism implementation**. **Essential for key escrow, backup, and migration scenarios**. 📦

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new HSM platforms or open-source cryptographic software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Cloud-Hardware-Security-Module-HSM&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Cloud-Hardware-Security-Module-HSM&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this HSM repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow security engineers, cryptographers, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **HSM-as-a-Service market challenges**: High initial costs, complexity of integration with legacy systems, and regulatory variations across regions can limit adoption. **Data sovereignty concerns** and **vendor lock-in** remain significant barriers in regulated industries.
- **PQC readiness is critical**: HSMs that are not certified or firmware-upgradeable to support **ML-KEM and ML-DSA** will reach **functional obsolescence** as government and regulated enterprise customers align procurement to new standards. **Thales, Utimaco, and IBM** have committed to PQC-ready platforms.
- **SoftHSMv2 is a software implementation** — it provides PKCS#11 interface compatibility but **does not offer the physical tamper-resistance** of hardware HSMs. **Use for development, testing, or non-critical scenarios** where FIPS 140-2 Level 3 validation is not required.
- **FreeHSM-C is newly accepted into Debian** — it aims for **FIPS 140-3 Level 1** and **Common Criteria EAL4+** certification, but **certification is pending**. **Verify certification status** before relying on it for compliance-critical deployments.
- **Open-source PKCS#11 tools (pkcs11-tools, pkcs11-helper, hsmwiz) simplify HSM integration** but **do not replace the need for proper key lifecycle management**. **Always implement secure key backup, rotation, and destruction procedures** regardless of the HSM platform. 🔐

---

<p align="center">
  <b>Made with ❤️ for security engineers, cryptographers, and open-source HSM advocates.</b>
</p>
