# Paydae Desktop — Beta Downloads

Paydae Desktop is a payroll workspace for preparing, reviewing and keeping payroll records. This repository distributes official beta installers and release notes.

**Paydae is proprietary software. The beta is available at no software licence charge for a limited period. This repository does not publish the application's source code or grant an open-source licence.**

> Draft for publication: replace all bracketed fields and verify the links and supported requirements before publishing.

## Download

**[Download Paydae Desktop 0.1.0 for Windows (x64)](https://github.com/tapiwax/paydae-downloads/releases/download/v0.1.0-beta/Paydae-Desktop-Setup-0.1.0-x64.exe)**

- [Official website](https://paydae.co/)
- [Release history and release notes](https://github.com/tapiwax/paydae-downloads/releases)
- [Beta Licence Agreement](./LICENSE.md)
- [Privacy Policy](https://paydae.co/privacy-policy/)
- [Support centre](https://support.paydae.co/)

The Windows x64 installer is `Paydae-Desktop-Setup-0.1.0-x64.exe` (75,314,241 bytes). The link targets the `v0.1.0-beta` pre-release directly. Update this link and its label when publishing a new version.

SHA-256: `56ed5818f7613b4e02b4b0a1863da1b1342d1937af4a90725f6f8437de7b8f55`.

## Beta availability and pricing

The beta licence expires on **31 December 2026 at 23:59 (UTC+02:00), inclusive through the end of that minute**, unless extended in writing. The application may stop allowing normal use after expiry. Export required records and make recoverable workspace backups before then; continued read-only access is not promised.

Future versions or continued use after the beta may require a paid licence. There is no automatic charge or paid subscription: any paid offer requires your separate express agreement. Beta access does not guarantee permanent free access or a future discount.

## System requirements

- Operating system: **64-bit Windows 10 version 1903 (build 18362) or later**, as specified in the installation guide.
- Processor architecture: **x64 (Intel/AMD 64-bit)** for the documented Windows package. ARM64 support has not been established.
- Memory: **8 GB RAM recommended**, with more memory for large payrolls or when running other business applications alongside Paydae.
- Storage: **allow at least 2 GB of free disk space for installation, prerequisites and updates**, plus additional space for payroll workspaces, generated documents and retained backups. An SSD is recommended.
- Application runtime: the documented Windows package includes self-contained local .NET hosts; a separate .NET installation is not required for those hosts.
- Additional prerequisites: **Microsoft Edge WebView2 Runtime**. The current installer configuration uses Tauri's default mode, which downloads and runs the WebView2 installer if the runtime is missing. Internet access is required for that step; on an offline computer, arrange installation of WebView2 beforehand.
- Display: allow space for an application window of at least **1024 × 680 pixels**, plus Windows window controls and taskbar. A **1366 × 768 display or larger at 100% scaling** is recommended; higher display scaling may require a higher resolution.
- Installation permissions: permission to install applications for your Windows user account and write to your selected workspace and backup folders. Managed computers may require IT approval for prerequisite installation.
- Connectivity: local operation and offline licence validation are documented; continuous internet access is not required for ordinary local operation. Confirm the activation path for the beta release before installation. Downloading the installer, obtaining updates and installing a missing WebView2 runtime require an internet-connected device.

The memory and storage figures above are provisional planning recommendations based on the packaged desktop application, local payroll processing and backup needs; they are not benchmark-validated minimums or a guarantee for every payroll size. The window size and prerequisite behaviour come from the current application configuration. See [Tauri's WebView2 installation documentation](https://v2.tauri.app/distribute/windows-installer/#webview2-installation-options) and check the release notes for requirements and known limitations specific to your version.

## Install or update

1. Read the release notes, known issues and [Beta Licence Agreement](./LICENSE.md).
2. Before updating an existing installation, make a recoverable workspace backup using the supported backup procedure.
3. Download the installer from the link above or the release's attached assets. The automatically generated source archives are not installers.
4. Run the installer, review the agreement and accept it only if you agree. Follow the installation and activation instructions for your release.
5. Verify the installed version and review your payroll settings before use.

If Windows displays a security or publisher warning, verify the file's origin and contact **hello@paydae.co** if unsure. Do not disable security protection to complete installation. Where a release provides a SHA-256 checksum, compare it with the downloaded file to check integrity; a checksum alone does not establish publisher identity.

## Important beta limitations

This is pre-release software. Features, formats and behaviour may change, and bugs may affect calculations, exports or availability. Independently check payroll results before finalisation, filing, distribution or payment, and keep a reliable fallback process for payroll deadlines.

Use synthetic or anonymised records for evaluation where practical. If using live employee or client records, ensure you have the necessary authority and safeguards. Maintain recoverable backups; exported reports do not replace workspace backups. Review the licence's warranty and liability provisions before accepting.

## Feedback and support

Send feedback or support requests to **[hello@paydae.co](mailto:hello@paydae.co)**, or consult the [support centre](https://support.paydae.co/). Include the Paydae version, Windows version, steps to reproduce the problem and any error message, with sensitive details removed.

**Do not publish payroll files, employee details, bank information, credentials or licence keys in public GitHub issues.** Request a private support channel before sharing sensitive material. Beta support is subject to availability unless separately agreed.

## Licence and ownership

Copyright © 2026 **Paydae Pvt Ltd**. All rights reserved, subject to the [Beta Licence Agreement](./LICENSE.md) and applicable third-party licences.

The beta agreement permits authorised use, including client payroll work within your agreed licence limits. It does not grant permission to resell, sublicense or publicly mirror the installer. You may share links to the official download page and lawfully retain and share payroll outputs as described in the agreement.

Third-party software notices: **[THIRD_PARTY_NOTICES_LOCATION]**.
