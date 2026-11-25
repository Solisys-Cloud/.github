<p align="center">
  <img src="assets/banner.svg" alt="Solisys - Design, secure and automate your Microsoft cloud" width="100%">
</p>

<p align="center">
  <a href="https://www.solisys.be"><img src="https://img.shields.io/badge/Website-solisys.be-0078D4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://www.solisys.be/blog/"><img src="https://img.shields.io/badge/Blog-Articles-0B3563?style=for-the-badge&logo=rss&logoColor=white" alt="Blog"></a>
  <a href="https://www.linkedin.com/in/olivier-lumeau-34402214/"><img src="https://img.shields.io/badge/LinkedIn-Olivier%20Lumeau-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Based%20in-Belgium-071528?style=for-the-badge" alt="Based in Belgium">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform">
  <img src="https://img.shields.io/badge/Bicep-0078D4?style=flat-square" alt="Bicep">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square" alt="Azure DevOps">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

---

## About this repository

This repository powers the public profile of the **Solisys-Cloud** organization.
The page displayed on [github.com/Solisys-Cloud](https://github.com/Solisys-Cloud) is built from [`profile/README.md`](profile/README.md).

**Solisys** is the Belgian consultancy of **Olivier Lumeau**, Senior Azure and Microsoft 365 Architect and Security Engineer.
The blog explains the why. These repositories show the how, in code you can run in your own tenant.

## Six themes, one standard

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Azure</h3>
      Landing zones, networking and governance, written as code.<br><br>
      <img src="https://img.shields.io/badge/status-available-2EA043?style=flat-square" alt="Available">
    </td>
    <td width="33%" valign="top">
      <h3>Microsoft 365</h3>
      Tenant hardening, Exchange and secure collaboration.<br><br>
      <img src="https://img.shields.io/badge/status-coming%20soon-8B949E?style=flat-square" alt="Coming soon">
    </td>
    <td width="33%" valign="top">
      <h3>Entra ID</h3>
      Identity, tokens, sign-in flows and Conditional Access.<br><br>
      <img src="https://img.shields.io/badge/status-available-2EA043?style=flat-square" alt="Available">
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h3>DevOps</h3>
      Terraform, Bicep and pipelines that deploy without stored secrets.<br><br>
      <img src="https://img.shields.io/badge/status-available-2EA043?style=flat-square" alt="Available">
    </td>
    <td width="33%" valign="top">
      <h3>Cybersecurity</h3>
      Protocols explained, exposure checks and Zero Trust in practice.<br><br>
      <img src="https://img.shields.io/badge/status-available-2EA043?style=flat-square" alt="Available">
    </td>
    <td width="33%" valign="top">
      <h3>AI</h3>
      Artificial Intelligence on Azure: AI Search, AI Foundry and RAG (Retrieval-Augmented Generation) patterns.<br><br>
      <img src="https://img.shields.io/badge/status-coming%20soon-8B949E?style=flat-square" alt="Coming soon">
    </td>
  </tr>
</table>

## How the content fits together

```mermaid
flowchart LR
    A["Blog article<br/>explains why"] --> B["Hands-on lab<br/>shows how"]
    B --> C["Reusable module<br/>makes it repeatable"]
    C --> D["Pipeline<br/>deploys it safely"]
    classDef step fill:#0B3563,stroke:#50B4FF,color:#FFFFFF,stroke-width:2px;
    classDef last fill:#0078D4,stroke:#50E6FF,color:#FFFFFF,stroke-width:2px;
    class A,B,C step;
    class D last;
```

## Principles behind every repository

| Principle | In practice |
|---|---|
| **Reproducible** | Every lab deploys in your own subscription and is removed with a single command. |
| **Secure by default** | No secrets in code, workload identity federation for pipelines, no Terraform state in Git. |
| **Step by step** | Short guides, architecture diagrams and a validation workflow on each change. |
| **Versioned** | Reusable modules are released with Git tags, so every environment pins a known version. |
| **Open** | Labs and modules are published under the MIT licence. |

## Repository layout

```text
.github/
├── assets/
│   └── banner.svg      # Banner used in this README
├── profile/
│   └── README.md       # Organization profile page
└── README.md           # This file
```

---

<p align="center">
  <sub>Maintained by Olivier Lumeau · Solisys srl · Belgium</sub>
</p>
