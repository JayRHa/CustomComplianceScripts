<!-- jr-brand:start -->
<div align="center">
  <a href="https://jannikreinhard.com/">
    <img src="https://raw.githubusercontent.com/JayRHa/.github/main/assets/readme/collection.svg" alt="Jannik Reinhard — AI, Cloud and Endpoint Management" width="100%">
  </a>
  <h1>Custom Compliance Scripts</h1>
  <p><strong>PowerShell scripts for Microsoft Intune Custom Compliance policies and device configuration checks.</strong></p>
  <p>
  <a href="https://jannikreinhard.com/"><img src="https://img.shields.io/badge/Website-0A5FC0?style=flat-square&amp;logo=wordpress&amp;logoColor=white" alt="Website"></a>
  <a href="https://github.com/JayRHa"><img src="https://img.shields.io/badge/GitHub-081427?style=flat-square&amp;logo=github&amp;logoColor=white" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/jannik-r/"><img src="https://img.shields.io/badge/LinkedIn-0795FF?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/jannik_reinhard"><img src="https://img.shields.io/badge/X-081427?style=flat-square&amp;logo=x&amp;logoColor=white" alt="X"></a>
  <a href="https://www.youtube.com/@ModernDevMgmt/featured"><img src="https://img.shields.io/badge/YouTube-0A5FC0?style=flat-square&amp;logo=youtube&amp;logoColor=white" alt="YouTube"></a>
</p>
  <p><sub>Open-Source Collection · PowerShell · Practical by design</sub></p>
</div>
<!-- jr-brand:end -->

## Overview

This repository contains Microsoft Intune custom compliance discovery scripts and their matching JSON definitions. Each folder covers one practical Windows compliance check.

## Available Checks

| Check | Purpose |
| --- | --- |
| `Check-AvEnabled` | Confirm that antivirus protection is enabled |
| `Check-FirewallEnabled` | Confirm that Windows Firewall is enabled |
| `Check-FreeStorage` | Check available storage |
| `Check-IfAppIsInstalled` | Detect whether a required application is installed |
| `Check-IfDeviceIsEncrypted` | Check device encryption |
| `Check-IfDeviceIsUpToDate` | Check the Windows update state |
| `Check-IfUnathorizedLocalAdmins` | Detect unexpected local administrators |

## Quickstart

1. Open the folder for the check you want to use.
2. Review and test the PowerShell discovery script on a test device.
3. In the Microsoft Intune admin center, create a custom compliance policy.
4. Upload the `.ps1` discovery script and import the matching `.json` definition.
5. Assign the policy to a test group before a wider rollout.

> **Note:** Always review the expected values in the JSON file. Adjust them to match your own compliance requirements.

## License

This project is available under the terms in [LICENSE](LICENSE).

<!-- jr-brand-footer:start -->

---

<div align="center">
  <p><sub>Built and maintained by <a href="https://jannikreinhard.com/">Jannik Reinhard</a> · Microsoft MVP for Security and AI Platform.</sub></p>
  <p><a href="https://www.buymeacoffee.com/jannikreinf">Support the open-source work</a></p>
  <p><strong>Stay healthy, Cheers Jannik</strong></p>
</div>

<!-- jr-brand-footer:end -->
