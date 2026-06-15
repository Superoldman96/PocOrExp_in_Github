# Update 2026-06-15
## CVE-2026-49975
This issue affects Apache HTTP Server: from 2.4.17 through 2.4.67.

- [https://github.com/adminlove520/http2-bomb-detector](https://github.com/adminlove520/http2-bomb-detector) :  ![starts](https://img.shields.io/github/stars/adminlove520/http2-bomb-detector.svg) ![forks](https://img.shields.io/github/forks/adminlove520/http2-bomb-detector.svg)
- [https://github.com/minc-nice-100/http2-bomb-analysis-paper](https://github.com/minc-nice-100/http2-bomb-analysis-paper) :  ![starts](https://img.shields.io/github/stars/minc-nice-100/http2-bomb-analysis-paper.svg) ![forks](https://img.shields.io/github/forks/minc-nice-100/http2-bomb-analysis-paper.svg)
- [https://github.com/razureink/cve-2026-49975-http2bomb_reproduction](https://github.com/razureink/cve-2026-49975-http2bomb_reproduction) :  ![starts](https://img.shields.io/github/stars/razureink/cve-2026-49975-http2bomb_reproduction.svg) ![forks](https://img.shields.io/github/forks/razureink/cve-2026-49975-http2bomb_reproduction.svg)


## CVE-2026-48907
 A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

- [https://github.com/87achrafg-stack/CVE-2026-48907](https://github.com/87achrafg-stack/CVE-2026-48907) :  ![starts](https://img.shields.io/github/stars/87achrafg-stack/CVE-2026-48907.svg) ![forks](https://img.shields.io/github/forks/87achrafg-stack/CVE-2026-48907.svg)


## CVE-2026-48611
 Improper authentication checks in the OAuth implementation allow account hijacking even when OAuth is not configured or enabled leading to unauthorized access in default installations.

- [https://github.com/citruscitruscitruscitruscitrusci/CVE-2026-48611-poc](https://github.com/citruscitruscitruscitruscitrusci/CVE-2026-48611-poc) :  ![starts](https://img.shields.io/github/stars/citruscitruscitruscitruscitrusci/CVE-2026-48611-poc.svg) ![forks](https://img.shields.io/github/forks/citruscitruscitruscitruscitrusci/CVE-2026-48611-poc.svg)


## CVE-2026-45447
issue, as the affected code is outside the OpenSSL FIPS module boundary.

- [https://github.com/0xBlackash/CVE-2026-45447](https://github.com/0xBlackash/CVE-2026-45447) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-45447.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-45447.svg)


## CVE-2026-42647
This issue affects JoomSport: from n/a through 5.7.7.

- [https://github.com/rootdirective-sec/CVE-2026-42647-Lab](https://github.com/rootdirective-sec/CVE-2026-42647-Lab) :  ![starts](https://img.shields.io/github/stars/rootdirective-sec/CVE-2026-42647-Lab.svg) ![forks](https://img.shields.io/github/forks/rootdirective-sec/CVE-2026-42647-Lab.svg)


## CVE-2026-41490
 Dagster is an orchestration platform for the development, production, and observation of data assets. Prior to Dagster Core version 1.13.1 and prior to Dagster libraries version 0.29.1, the DuckDB, Snowflake, BigQuery, and DeltaLake I/O managers constructed SQL WHERE clauses by interpolating dynamic partition key values into queries without escaping. A user with the Add Dynamic Partitions permission could create a partition key that injects arbitrary SQL, which would execute against the target database backend under the I/O manager's credentials. Only deployments that use dynamic partitions are affected. Pipelines using static or time-window partitions are not impacted. This issue has been patched in Dagster Core version 1.13.1 and Dagster libraries version 0.29.1.

- [https://github.com/romain-deperne/CVE-2026-41490](https://github.com/romain-deperne/CVE-2026-41490) :  ![starts](https://img.shields.io/github/stars/romain-deperne/CVE-2026-41490.svg) ![forks](https://img.shields.io/github/forks/romain-deperne/CVE-2026-41490.svg)


## CVE-2026-40864
 JupyterHub is software that allows users to create a multi-user server for Jupyter notebooks. In versions 4.1.0 through 5.4.4, XSRF protection (updated in 4.1.0) inappropriately treated requests with Sec-Fetch-Mode: no-cors as same-origin requests, bypassing XSRF checks. The JSON API is not affected, only HTTP form endpoints, such as /hub/spawn and /hub/accept-share, meaning attackers could trigger server spawn (but not access the server) and if the attacker is a JupyterHub user permitted to share access to their server, cause a user to accept a share and have access to the attacker's server. This issue has been fixed in version 5.4.5. If developers are unable to immediately upgrade, they can temporarily mitigate this issue by dropping requests to JupyterHub with Sec-Fetch-Mode: no-cors if they are using a reverse proxy.

- [https://github.com/romain-deperne/CVE-2026-40864](https://github.com/romain-deperne/CVE-2026-40864) :  ![starts](https://img.shields.io/github/stars/romain-deperne/CVE-2026-40864.svg) ![forks](https://img.shields.io/github/forks/romain-deperne/CVE-2026-40864.svg)


## CVE-2026-35273
 Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Updates Environment Management). Supported versions that are affected are 8.61 and 8.62. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise PeopleSoft Enterprise PeopleTools. Successful attacks of this vulnerability can result in takeover of PeopleSoft Enterprise PeopleTools. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

- [https://github.com/ekomsSavior/POC_cve_2026_35273](https://github.com/ekomsSavior/POC_cve_2026_35273) :  ![starts](https://img.shields.io/github/stars/ekomsSavior/POC_cve_2026_35273.svg) ![forks](https://img.shields.io/github/forks/ekomsSavior/POC_cve_2026_35273.svg)


## CVE-2026-27212
 Swiper is a free and mobile touch slider with hardware accelerated transitions and native behavior. Versions 6.5.1 through 12.1.1 have a Prototype pollution vulnerability. The vulnerability resides in line 94 of shared/utils.mjs, where the indexOf() function is used to check whether user provided input contain forbidden strings. Despite a previous fix that attempted to mitigate prototype pollution by checking whether user input contained a forbidden key, it is still possible to pollute Object.prototype via a crafted input using Array.prototype. The exploit works across Windows and Linux and on Node and Bun runtimes.  Any application that processes attacker-controlled input using this package may be affected  by the following: Authentication Bypass, Denial of Service and RCE. This issue is fixed in version 12.1.2.

- [https://github.com/stealth-src/resize-image-before-upload-secure](https://github.com/stealth-src/resize-image-before-upload-secure) :  ![starts](https://img.shields.io/github/stars/stealth-src/resize-image-before-upload-secure.svg) ![forks](https://img.shields.io/github/forks/stealth-src/resize-image-before-upload-secure.svg)


## CVE-2026-22356
 Improper Control of Filename for Include/Require Statement in PHP Program ('PHP Remote File Inclusion') vulnerability in Automattic Jetpack CRM zero-bs-crm allows PHP Local File Inclusion.This issue affects Jetpack CRM: from n/a through = 6.7.0.

- [https://github.com/xxconi/CVE-2026-22356](https://github.com/xxconi/CVE-2026-22356) :  ![starts](https://img.shields.io/github/stars/xxconi/CVE-2026-22356.svg) ![forks](https://img.shields.io/github/forks/xxconi/CVE-2026-22356.svg)


## CVE-2026-20253
 In Splunk Enterprise versions below 10.2.4 and 10.0.7, and Splunk Cloud Platform versions below 10.4.2604.3 and 10.2.2510.14, an unauthenticated user could create or truncate arbitrary files through a PostgreSQL sidecar service endpoint.brbrThe vulnerability exists because the PostgreSQL sidecar service endpoint lacks authentication controls, allowing any network-reachable user to invoke file operations without credentials.

- [https://github.com/0xBlackash/CVE-2026-20253](https://github.com/0xBlackash/CVE-2026-20253) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-20253.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-20253.svg)


## CVE-2026-11450
 A vulnerability was detected in GL.iNet GL-MT3000 4.4.5. This affects the function dlopen in the library /usr/lib/oui-httpd/rpc/ of the component Path Normalization Handler. Performing a manipulation of the argument dev_name results in command injection. It is possible to initiate the attack remotely. Upgrading to version 4.7 mitigates this issue. It is advisable to upgrade the affected component. The vendor confirms: " From version 4.7 onward, we have enabled method‑level validation at the HTTP /rpc layer. nas‑web.eject_disk is no longer in the whitelist of allowed methods. Consequently, directly calling eject_disk through the default /rpc endpoint returns Invalid params, preventing entry into subsequent dangerous functions and blocking the remote exploit chain described in the report."

- [https://github.com/Hunt-Benito/glinet-beryl-ax-triple-rce-cve-2026-11450-11451-11452-unauthenticated-root-on-travel-router](https://github.com/Hunt-Benito/glinet-beryl-ax-triple-rce-cve-2026-11450-11451-11452-unauthenticated-root-on-travel-router) :  ![starts](https://img.shields.io/github/stars/Hunt-Benito/glinet-beryl-ax-triple-rce-cve-2026-11450-11451-11452-unauthenticated-root-on-travel-router.svg) ![forks](https://img.shields.io/github/forks/Hunt-Benito/glinet-beryl-ax-triple-rce-cve-2026-11450-11451-11452-unauthenticated-root-on-travel-router.svg)


## CVE-2026-11417
To remediate this issue, users should upgrade to aws-cdk-lib 2.245.0 (2.246.0 on Windows) or later.

- [https://github.com/HeshamASH/CVE-2026-11417-AWS-CDK-RCE](https://github.com/HeshamASH/CVE-2026-11417-AWS-CDK-RCE) :  ![starts](https://img.shields.io/github/stars/HeshamASH/CVE-2026-11417-AWS-CDK-RCE.svg) ![forks](https://img.shields.io/github/forks/HeshamASH/CVE-2026-11417-AWS-CDK-RCE.svg)


## CVE-2026-6279
 The Avada Builder (fusion-builder) plugin for WordPress is vulnerable to Unauthenticated Remote Code Execution via PHP Function Injection in versions up to and including 3.15.2. This is due to the `wp_conditional_tags` case in `Fusion_Builder_Conditional_Render_Helper::get_value()` passing attacker-controlled values from a base64-decoded JSON blob directly to `call_user_func()` without any allowlist validation. This is exploitable by unauthenticated attackers through the `fusion_get_widget_markup` AJAX endpoint, which is registered for non-privileged (unauthenticated) users via `wp_ajax_nopriv_fusion_get_widget_markup`. The endpoint is protected only by a nonce (`fusion_load_nonce`), but this nonce is generated for user ID 0 and is deterministically exposed in the JavaScript output of any public-facing page containing a Post Cards (`[fusion_post_cards]`) or Table of Contents (`[fusion_table_of_contents]`) element. This makes it possible for unauthenticated attackers to execute arbitrary code on affected sites.

- [https://github.com/87achrafg-stack/CVE-2026-6279.py](https://github.com/87achrafg-stack/CVE-2026-6279.py) :  ![starts](https://img.shields.io/github/stars/87achrafg-stack/CVE-2026-6279.py.svg) ![forks](https://img.shields.io/github/forks/87achrafg-stack/CVE-2026-6279.py.svg)
- [https://github.com/87achrafg-stack/CVE-2026-6279](https://github.com/87achrafg-stack/CVE-2026-6279) :  ![starts](https://img.shields.io/github/stars/87achrafg-stack/CVE-2026-6279.svg) ![forks](https://img.shields.io/github/forks/87achrafg-stack/CVE-2026-6279.svg)


## CVE-2026-6130
 A flaw has been found in chatboxai chatbox up to 1.20.0. This impacts the function StdioClientTransport of the file src/main/mcp/ipc-stdio-transport.ts of the component Model Context Protocol Server Management System. Executing a manipulation of the argument args/env can lead to os command injection. The attack can be launched remotely. The exploit has been published and may be used. The project was informed of the problem early through an issue report but has not responded yet.

- [https://github.com/fan-67/local-mcp](https://github.com/fan-67/local-mcp) :  ![starts](https://img.shields.io/github/stars/fan-67/local-mcp.svg) ![forks](https://img.shields.io/github/forks/fan-67/local-mcp.svg)


## CVE-2026-5950
This issue affects BIND 9 versions 9.18.36 through 9.18.48, 9.20.8 through 9.20.22, 9.21.7 through 9.21.21, 9.18.36-S1 through 9.18.48-S1, and 9.20.9-S1 through 9.20.22-S1.

- [https://github.com/billybaraja/cve-2026-5950-bind9-resolver-dos](https://github.com/billybaraja/cve-2026-5950-bind9-resolver-dos) :  ![starts](https://img.shields.io/github/stars/billybaraja/cve-2026-5950-bind9-resolver-dos.svg) ![forks](https://img.shields.io/github/forks/billybaraja/cve-2026-5950-bind9-resolver-dos.svg)


## CVE-2026-4801
 The Page Builder Gutenberg Blocks – CoBlocks plugin for WordPress is vulnerable to Stored Cross-Site Scripting via external iCal feed data in all versions up to, and including, 3.1.16 due to insufficient output escaping of event titles, descriptions, and locations fetched from external iCal feeds in the Events block rendering function. This makes it possible for authenticated attackers, with Contributor-level access and above, to inject arbitrary web scripts in pages that will execute whenever a user accesses an injected page.

- [https://github.com/romain-deperne/CVE-2026-48017](https://github.com/romain-deperne/CVE-2026-48017) :  ![starts](https://img.shields.io/github/stars/romain-deperne/CVE-2026-48017.svg) ![forks](https://img.shields.io/github/forks/romain-deperne/CVE-2026-48017.svg)


## CVE-2026-4525
 If a Vault auth mount is configured to pass through the "Authorization" header, and the "Authorization" header is used to authenticate to Vault, Vault forwarded the Vault token to the auth plugin backend. Fixed in 2.0.0, 1.21.5, 1.20.10, and 1.19.16.

- [https://github.com/Yayoi-cs/CVE-2026-45258_1day_LPE_exploit](https://github.com/Yayoi-cs/CVE-2026-45258_1day_LPE_exploit) :  ![starts](https://img.shields.io/github/stars/Yayoi-cs/CVE-2026-45258_1day_LPE_exploit.svg) ![forks](https://img.shields.io/github/forks/Yayoi-cs/CVE-2026-45258_1day_LPE_exploit.svg)


## CVE-2026-4524
 GitLab has remediated an issue in GitLab CE/EE affecting all versions from 18.9.1 before 18.9.7, 18.10 before 18.10.6, and 18.11 before 18.11.3 that could have allowed an authenticated user to access confidential issue content in public projects without proper authorization due to improper authorization checks.

- [https://github.com/CyruxSec/CVE-2026-4524](https://github.com/CyruxSec/CVE-2026-4524) :  ![starts](https://img.shields.io/github/stars/CyruxSec/CVE-2026-4524.svg) ![forks](https://img.shields.io/github/forks/CyruxSec/CVE-2026-4524.svg)


## CVE-2026-3719
 A vulnerability was identified in Tsinghua Unigroup Electronic Archives System 3.2.210802(62532). This issue affects some unknown processing of the file /System/Cms/downLoad. The manipulation of the argument path leads to path traversal. The attack can be initiated remotely. The exploit is publicly available and might be used. The vendor was contacted early about this disclosure but did not respond in any way.

- [https://github.com/Pavanvootla-sec/CVE-2026-37197](https://github.com/Pavanvootla-sec/CVE-2026-37197) :  ![starts](https://img.shields.io/github/stars/Pavanvootla-sec/CVE-2026-37197.svg) ![forks](https://img.shields.io/github/forks/Pavanvootla-sec/CVE-2026-37197.svg)


## CVE-2026-1555
 The WebStack theme for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the io_img_upload() function in all versions up to, and including, 1.2024. This makes it possible for unauthenticated attackers to upload arbitrary files on the affected site's server which may make remote code execution possible.

- [https://github.com/webshellseo8/CVE-2026-1555-POC](https://github.com/webshellseo8/CVE-2026-1555-POC) :  ![starts](https://img.shields.io/github/stars/webshellseo8/CVE-2026-1555-POC.svg) ![forks](https://img.shields.io/github/forks/webshellseo8/CVE-2026-1555-POC.svg)


## CVE-2025-67511
 Cybersecurity AI (CAI) is an open-source framework for building and deploying AI-powered offensive and defensive automation. Versions 0.5.9 and below are vulnerable to Command Injection through the run_ssh_command_with_credentials() function, which is  available to AI agents. Only password and command inputs are escaped in run_ssh_command_with_credentials to prevent shell injection; while username, host and port values are injectable. This issue does not have a fix at the time of publication.

- [https://github.com/edoardottt/CVE-2025-67511](https://github.com/edoardottt/CVE-2025-67511) :  ![starts](https://img.shields.io/github/stars/edoardottt/CVE-2025-67511.svg) ![forks](https://img.shields.io/github/forks/edoardottt/CVE-2025-67511.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive.svg)


## CVE-2025-52691
 Successful exploitation of the vulnerability could allow an unauthenticated attacker to upload arbitrary files to any location on the mail server, potentially enabling remote code execution.

- [https://github.com/Udyz/CVE-2025-52691](https://github.com/Udyz/CVE-2025-52691) :  ![starts](https://img.shields.io/github/stars/Udyz/CVE-2025-52691.svg) ![forks](https://img.shields.io/github/forks/Udyz/CVE-2025-52691.svg)


## CVE-2025-32711
 Ai command injection in M365 Copilot allows an unauthorized attacker to disclose information over a network.

- [https://github.com/Danielossai12/aisecplus-week01-danielossai](https://github.com/Danielossai12/aisecplus-week01-danielossai) :  ![starts](https://img.shields.io/github/stars/Danielossai12/aisecplus-week01-danielossai.svg) ![forks](https://img.shields.io/github/forks/Danielossai12/aisecplus-week01-danielossai.svg)


## CVE-2024-26170
 Windows Composite Image File System (CimFS) Elevation of Privilege Vulnerability

- [https://github.com/ProbNotAnExploiter/CVE-2024-26170-extended](https://github.com/ProbNotAnExploiter/CVE-2024-26170-extended) :  ![starts](https://img.shields.io/github/stars/ProbNotAnExploiter/CVE-2024-26170-extended.svg) ![forks](https://img.shields.io/github/forks/ProbNotAnExploiter/CVE-2024-26170-extended.svg)


## CVE-2024-5717
The specific flaw exists within the implementation of the HTTP API. The issue results from the lack of proper validation of a user-supplied string before using it to execute a system call. An attacker can leverage this vulnerability to execute code in the context of root. Was ZDI-CAN-24165.

- [https://github.com/byjanke/logsign-rce](https://github.com/byjanke/logsign-rce) :  ![starts](https://img.shields.io/github/stars/byjanke/logsign-rce.svg) ![forks](https://img.shields.io/github/forks/byjanke/logsign-rce.svg)


## CVE-2024-5716
The specific flaw exists within the password reset mechanism. The issue results from the lack of restriction of excessive authentication attempts. An attacker can leverage this vulnerability to reset a user's password and bypass authentication on the system. Was ZDI-CAN-24164.

- [https://github.com/byjanke/logsign-rce](https://github.com/byjanke/logsign-rce) :  ![starts](https://img.shields.io/github/stars/byjanke/logsign-rce.svg) ![forks](https://img.shields.io/github/forks/byjanke/logsign-rce.svg)


## CVE-2024-4367
 A type check was missing when handling fonts in PDF.js, which would allow arbitrary JavaScript execution in the PDF.js context. This vulnerability affects Firefox  126, Firefox ESR  115.11, and Thunderbird  115.11.

- [https://github.com/J1nKsC/CVE-2024-4367_test](https://github.com/J1nKsC/CVE-2024-4367_test) :  ![starts](https://img.shields.io/github/stars/J1nKsC/CVE-2024-4367_test.svg) ![forks](https://img.shields.io/github/forks/J1nKsC/CVE-2024-4367_test.svg)


## CVE-2024-3094
Through a series of complex obfuscations, the liblzma build process extracts a prebuilt object file from a disguised test file existing in the source code, which is then used to modify specific functions in the liblzma code. This results in a modified liblzma library that can be used by any software linked against this library, intercepting and modifying the data interaction with this library.

- [https://github.com/stevehenderson/lab_xz_backdoor](https://github.com/stevehenderson/lab_xz_backdoor) :  ![starts](https://img.shields.io/github/stars/stevehenderson/lab_xz_backdoor.svg) ![forks](https://img.shields.io/github/forks/stevehenderson/lab_xz_backdoor.svg)


## CVE-2023-38646
 Metabase open source before 0.46.6.1 and Metabase Enterprise before 1.46.6.1 allow attackers to execute arbitrary commands on the server, at the server's privilege level. Authentication is not required for exploitation. The other fixed versions are 0.45.4.1, 1.45.4.1, 0.44.7.1, 1.44.7.1, 0.43.7.2, and 1.43.7.2.

- [https://github.com/NosrevytsNg/Metabase-Pre-Auth-RCE-POC](https://github.com/NosrevytsNg/Metabase-Pre-Auth-RCE-POC) :  ![starts](https://img.shields.io/github/stars/NosrevytsNg/Metabase-Pre-Auth-RCE-POC.svg) ![forks](https://img.shields.io/github/forks/NosrevytsNg/Metabase-Pre-Auth-RCE-POC.svg)


## CVE-2022-35252
 When curl is used to retrieve and parse cookies from a HTTP(S) server, itaccepts cookies using control codes that when later are sent back to a HTTPserver might make the server return 400 responses. Effectively allowing a"sister site" to deny service to all siblings.

- [https://github.com/hieudzpro2k10-svg/CVE_2022_352526](https://github.com/hieudzpro2k10-svg/CVE_2022_352526) :  ![starts](https://img.shields.io/github/stars/hieudzpro2k10-svg/CVE_2022_352526.svg) ![forks](https://img.shields.io/github/forks/hieudzpro2k10-svg/CVE_2022_352526.svg)


## CVE-2018-19134
 In Artifex Ghostscript through 9.25, the setpattern operator did not properly validate certain types. A specially crafted PostScript document could exploit this to crash Ghostscript or, possibly, execute arbitrary code in the context of the Ghostscript process. This is a type confusion issue because of failure to check whether the Implementation of a pattern dictionary was a structure type.

- [https://github.com/w0ot-net/cve_2018_19134_ghostscript_arbitrary_rw_demo](https://github.com/w0ot-net/cve_2018_19134_ghostscript_arbitrary_rw_demo) :  ![starts](https://img.shields.io/github/stars/w0ot-net/cve_2018_19134_ghostscript_arbitrary_rw_demo.svg) ![forks](https://img.shields.io/github/forks/w0ot-net/cve_2018_19134_ghostscript_arbitrary_rw_demo.svg)


## CVE-2017-13077
 Wi-Fi Protected Access (WPA and WPA2) allows reinstallation of the Pairwise Transient Key (PTK) Temporal Key (TK) during the four-way handshake, allowing an attacker within radio range to replay, decrypt, or spoof frames.

- [https://github.com/mugheeskhan5/wpa2-zero-hardware-krack-lab](https://github.com/mugheeskhan5/wpa2-zero-hardware-krack-lab) :  ![starts](https://img.shields.io/github/stars/mugheeskhan5/wpa2-zero-hardware-krack-lab.svg) ![forks](https://img.shields.io/github/forks/mugheeskhan5/wpa2-zero-hardware-krack-lab.svg)


## CVE-2017-0144
 The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0145, CVE-2017-0146, and CVE-2017-0148.

- [https://github.com/0xBlackash/CVE-2017-0144](https://github.com/0xBlackash/CVE-2017-0144) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2017-0144.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2017-0144.svg)

