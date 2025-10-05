# Vulnerability Research

This repository contains information and proofs of concept (PoCs) for the CVEs I have found.

### 1. [EasyVirt](https://www.easyvirt.com/)
| CVE ID       | Vulnerabilty           | Product               |
|--------------|------------------------|-----------------------|
| [CVE-2024-53354](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2024-53354.md)| Multiple SQL Injection | DCScope <= 8.6.0 / Co2Scope <= 1.3.0 |
| [CVE-2024-53355](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2024-53355.md)| Broken Access Control | DCScope <= 8.6.0 / Co2Scope <= 1.3.0 |
| [CVE-2024-53356](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2024-53356.md)| Weak JWT Secret | DCScope <= 8.6.0 / Co2Scope <= 1.3.0 |
| [CVE-2024-53357](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2024-53357.md)| Sensitive Data Exposure | DCScope <= 8.6.0 / Co2Scope <= 1.3.0 |
| [CVE-2024-55062](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2024-55062.md)| Remote Code Execution (Unauthenticated) | DCScope <= 8.6.0 / Co2Scope <= 1.3.0 |
| [CVE-2024-57587](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2024-57587.md)| Multiple SQL Injection (Unauthenticated) | DCScope <= 8.6.0 / Co2Scope <= 1.3.0 |
| [CVE-2024-55064](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2024-55064.md)| Multiple Stored XSS | DC NetScope <= 8.6.4 |
| [CVE-2025-28076](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2025-28076.md)| Multiple SQL Injection | DCScope <= 8.6.4 / Co2Scope <= 1.3.4 |
| [CVE-2024-55063](https://github.com/Elymaro/CVE/blob/main/EasyVirt/CVE-2024-55063.md)| Multiple Remote Code Execution | DC NetScope <= 8.7.0 |


### 2. [GreaterWMS](https://github.com/GreaterWMS/GreaterWMS)
| CVE ID       | Vulnerabilty           | Product               |
|--------------|------------------------|-----------------------|
| [CVE-2025-26201](https://github.com/Elymaro/CVE/blob/main/GreaterWMS/CVE-2025-26201.md)| Authentication Bypass via Credential Disclosure  | GreaterWMS <= 2.1.49 |

### 3. [Wordpress](https://wordpress.org/)
| CVE ID       | Vulnerabilty           | Product               |
|--------------|------------------------|-----------------------|
| [CVE-2025-6716](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/contest-gallery/contest-gallery-2608-authenticated-author-stored-cross-site-scripting)| Stored XSS (Author+) | (plugin) [contest-gallery](https://wordpress.org/plugins/contest-gallery/) <= 26.0.8 |
| [CVE-2025-6717](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/b1-accounting/b1lt-for-woocommerce-2256-authenticated-subscriber-sql-injection)| SQL Injection (Subscriber+) | (plugin) [b1-accounting](https://wordpress.org/plugins/b1-accounting/) <= 2.2.56 |
| [CVE-2025-6718](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/b1-accounting/b1lt-for-woocommerce-2256-missing-authorization-to-authenticated-subscriber-arbitrary-sql-injection)| Broken Access Control + SQL Injection (Subscriber+) | (plugin) [b1-accounting](https://wordpress.org/plugins/b1-accounting/) <= 2.2.56 |
| [CVE-2025-6719](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/contest-gallery/contest-gallery-2608-authenticated-author-stored-cross-site-scripting)| Stored XSS (Admin+) | (plugin) [terms-descriptions](https://wordpress.org/plugins/terms-descriptions/) <= 3.4.8 |
| [CVE-2025-6722](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/bitfire/bitfire-45-unauthenticated-information-exposure)| Unauthenticated Information Exposure - WAF configuration | (plugin) [BitFire](https://wordpress.org/plugins/bitfire/) <= 4.5 |
| [CVE-2025-10380](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/acf-views/advanced-views-display-posts-custom-fields-and-more-3719-authenticated-author-remote-code-execution-via-ssti)| SSTI (Author+) | (plugin) [Advanced Views](https://wordpress.org/plugins/acf-views/) <= 3.7.19 |
| [CVE-2025-10490](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/zephyr-project-manager/zephyr-project-manager-33202-authenticated-admin-stored-cross-site-scripting)| Stored XSS (Admin+) | (plugin) [zephyr-project-manager](https://wordpress.org/plugins/zephyr-project-manager) <= 3.3.202 |
| [CVE-2025-10744](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/softdiscover-db-file-manager/file-manager-code-editor-backup-by-managefy-161-unauthenticated-information-exposure)| Unauthenticated Information Exposure - Database exfiltration | (plugin) [softdiscover-db-file-manager](https://wordpress.org/plugins/softdiscover-db-file-manager) <= 1.6.1 |
| [CVE-2025-10383](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/contest-gallery/contest-gallery-upload-vote-sell-with-paypal-and-stripe-2702-authenticated-author-stored-cross-site-scripting)| Stored XSS (Author+) | (plugin) [contest-gallery](https://wordpress.org/plugins/contest-gallery) <= 27.0.2 |
