# Update 2026-06-16
## CVE-2026-53787
 Amasty Order Attributes for Magento 2 before version 4.0.0 contains an unauthenticated arbitrary file upload vulnerability that allows unauthenticated attackers to write arbitrary files to the store's media directory by submitting files of any type or name to the upload endpoint without authentication, session validation, or cart context. Attackers can upload PHP files to achieve remote code execution on servers where the media directory permits PHP execution, or alternatively enable malware hosting, stored cross-site scripting via HTML or SVG uploads, and path traversal to write files outside the intended upload directory.

- [https://github.com/webshellseo8/CVE-2026-53787-POC-](https://github.com/webshellseo8/CVE-2026-53787-POC-) :  ![starts](https://img.shields.io/github/stars/webshellseo8/CVE-2026-53787-POC-.svg) ![forks](https://img.shields.io/github/forks/webshellseo8/CVE-2026-53787-POC-.svg)


## CVE-2026-42945
 NGINX Plus and NGINX Open Source have a vulnerability in the ngx_http_rewrite_module module. This vulnerability exists when the rewrite directive is followed by a rewrite, if, or set directive and an unnamed Perl-Compatible Regular Expression (PCRE) capture (for example, $1, $2) with a replacement string that includes a question mark (?). An unauthenticated attacker along with conditions beyond its control can exploit this vulnerability by sending crafted HTTP requests. This may cause a heap buffer overflow in the NGINX worker process leading to a restart. Additionally, attackers can execute code on systems with Address Space Layout Randomization (ASLR) disabled or when the attacker can bypass ASLR.  Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

- [https://github.com/sec-sys/CVE-2026-42945-Reverse-Shell-POC](https://github.com/sec-sys/CVE-2026-42945-Reverse-Shell-POC) :  ![starts](https://img.shields.io/github/stars/sec-sys/CVE-2026-42945-Reverse-Shell-POC.svg) ![forks](https://img.shields.io/github/forks/sec-sys/CVE-2026-42945-Reverse-Shell-POC.svg)


## CVE-2026-27212
 Swiper is a free and mobile touch slider with hardware accelerated transitions and native behavior. Versions 6.5.1 through 12.1.1 have a Prototype pollution vulnerability. The vulnerability resides in line 94 of shared/utils.mjs, where the indexOf() function is used to check whether user provided input contain forbidden strings. Despite a previous fix that attempted to mitigate prototype pollution by checking whether user input contained a forbidden key, it is still possible to pollute Object.prototype via a crafted input using Array.prototype. The exploit works across Windows and Linux and on Node and Bun runtimes.  Any application that processes attacker-controlled input using this package may be affected  by the following: Authentication Bypass, Denial of Service and RCE. This issue is fixed in version 12.1.2.

- [https://github.com/stealth-engine/resize-image-before-upload-secure](https://github.com/stealth-engine/resize-image-before-upload-secure) :  ![starts](https://img.shields.io/github/stars/stealth-engine/resize-image-before-upload-secure.svg) ![forks](https://img.shields.io/github/forks/stealth-engine/resize-image-before-upload-secure.svg)


## CVE-2026-23947
 Orval generates type-safe JS clients (TypeScript) from any valid OpenAPI v3 or Swagger v2 specification. Versions prior to 7.19.0 until 8.0.2 are vulnerable to arbitrary code execution in environments consuming generated clients. This issue is similar in nature to CVE-2026-22785, but affects a different code path in @orval/core that was not addressed by CVE-2026-22785's fix. The vulnerability allows untrusted OpenAPI specifications to inject arbitrary TypeScript/JavaScript code into generated clients via the x-enumDescriptions field, which is embedded without proper escaping in getEnumImplementation(). I have confirmed that the injection occurs during const enum generation and results in executable code within the generated schema files. Orval 7.19.0 and 8.0.2 contain a fix for the issue.

- [https://github.com/ibreakthingsforaliving/CVE-2026-23947-PoC](https://github.com/ibreakthingsforaliving/CVE-2026-23947-PoC) :  ![starts](https://img.shields.io/github/stars/ibreakthingsforaliving/CVE-2026-23947-PoC.svg) ![forks](https://img.shields.io/github/forks/ibreakthingsforaliving/CVE-2026-23947-PoC.svg)


## CVE-2026-23744
 MCPJam inspector is the local-first development platform for MCP servers. Versions 1.4.2 and earlier are vulnerable to remote code execution (RCE) vulnerability, which allows an attacker to send a crafted HTTP request that triggers the installation of an MCP server, leading to RCE. Since MCPJam inspector by default listens on 0.0.0.0 instead of 127.0.0.1, an attacker can trigger the RCE remotely via a simple HTTP request. Version 1.4.3 contains a patch.

- [https://github.com/ibreakthingsforaliving/CVE-2026-23744-PoC](https://github.com/ibreakthingsforaliving/CVE-2026-23744-PoC) :  ![starts](https://img.shields.io/github/stars/ibreakthingsforaliving/CVE-2026-23744-PoC.svg) ![forks](https://img.shields.io/github/forks/ibreakthingsforaliving/CVE-2026-23744-PoC.svg)
- [https://github.com/rohit-sundar/cve-2026-23744](https://github.com/rohit-sundar/cve-2026-23744) :  ![starts](https://img.shields.io/github/stars/rohit-sundar/cve-2026-23744.svg) ![forks](https://img.shields.io/github/forks/rohit-sundar/cve-2026-23744.svg)


## CVE-2026-21962
 Vulnerability in the Oracle HTTP Server, Oracle Weblogic Server Proxy Plug-in product of Oracle Fusion Middleware (component: Weblogic Server Proxy Plug-in for Apache HTTP Server, Weblogic Server Proxy Plug-in for IIS).  Supported versions that are affected are 12.2.1.4.0, 14.1.1.0.0 and  14.1.2.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle HTTP Server, Oracle Weblogic Server Proxy Plug-in.  While the vulnerability is in Oracle HTTP Server, Oracle Weblogic Server Proxy Plug-in, attacks may significantly impact additional products (scope change).  Successful attacks of this vulnerability can result in  unauthorized creation, deletion or modification access to critical data or all Oracle HTTP Server, Oracle Weblogic Server Proxy Plug-in accessible data as well as  unauthorized access to critical data or complete access to all Oracle HTTP Server, Oracle Weblogic Server Proxy Plug-in accessible data. Note: Affected version for Weblogic Server Proxy Plug-in for IIS is 12.2.1.4.0 only. CVSS 3.1 Base Score 10.0 (Confidentiality and Integrity impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:N).

- [https://github.com/ibreakthingsforaliving/Ashwesker-CVE-2026-21962](https://github.com/ibreakthingsforaliving/Ashwesker-CVE-2026-21962) :  ![starts](https://img.shields.io/github/stars/ibreakthingsforaliving/Ashwesker-CVE-2026-21962.svg) ![forks](https://img.shields.io/github/forks/ibreakthingsforaliving/Ashwesker-CVE-2026-21962.svg)


## CVE-2026-20253
 In Splunk Enterprise versions below 10.2.4 and 10.0.7, and Splunk Cloud Platform versions below 10.4.2604.3 and 10.2.2510.14, an unauthenticated user could create or truncate arbitrary files through a PostgreSQL sidecar service endpoint.brbrThe vulnerability exists because the PostgreSQL sidecar service endpoint lacks authentication controls, allowing any network-reachable user to invoke file operations without credentials.

- [https://github.com/HORKimhab/CVE-2026-20253](https://github.com/HORKimhab/CVE-2026-20253) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-20253.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-20253.svg)


## CVE-2026-20245
Cisco recommends that customers upgrade to the fixed software that is documented in the  that was published on May 14, 2026, and verify the configuration of the edge devices.

- [https://github.com/0xBlackash/CVE-2026-20245](https://github.com/0xBlackash/CVE-2026-20245) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-20245.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-20245.svg)


## CVE-2026-20127
This vulnerability exists because the peering authentication mechanism in an affected system is not working properly. An attacker could exploit this vulnerability by sending crafted requests to an affected system. A successful exploit could allow the attacker to log in to an affected Cisco Catalyst SD-WAN Controller as an internal, high-privileged, non-root&nbsp;user account. Using this account, the attacker could access NETCONF, which would then allow the attacker to manipulate network configuration for the SD-WAN fabric.&nbsp;

- [https://github.com/0xBlackash/CVE-2026-20127](https://github.com/0xBlackash/CVE-2026-20127) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-20127.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-20127.svg)


## CVE-2026-5513
 The Online Scheduling and Appointment Booking System – Bookly plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'bookly-customer-full-name' cookie in versions up to, and including, 27.2 due to insufficient input sanitization and output escaping. This makes it possible for unauthenticated attackers to inject arbitrary web scripts in pages that will execute whenever a user accesses an injected page. Exploitation requires 'Remember personal information in cookies' setting to be enabled (disabled by default).

- [https://github.com/87achrafg-stack/CVE-2026-5513](https://github.com/87achrafg-stack/CVE-2026-5513) :  ![starts](https://img.shields.io/github/stars/87achrafg-stack/CVE-2026-5513.svg) ![forks](https://img.shields.io/github/forks/87achrafg-stack/CVE-2026-5513.svg)
- [https://github.com/Xaanziu/CVE-2026-5513](https://github.com/Xaanziu/CVE-2026-5513) :  ![starts](https://img.shields.io/github/stars/Xaanziu/CVE-2026-5513.svg) ![forks](https://img.shields.io/github/forks/Xaanziu/CVE-2026-5513.svg)


## CVE-2026-3682
 A security vulnerability has been detected in welovemedia FFmate up to 2.0.15. This vulnerability affects the function Execute of the file /internal/service/ffmpeg/ffmpeg.go. The manipulation leads to argument injection. The attack may be initiated remotely. The exploit has been disclosed publicly and may be used. The vendor was contacted early about this disclosure but did not respond in any way.

- [https://github.com/Forklit/CVE-2026-36826](https://github.com/Forklit/CVE-2026-36826) :  ![starts](https://img.shields.io/github/stars/Forklit/CVE-2026-36826.svg) ![forks](https://img.shields.io/github/forks/Forklit/CVE-2026-36826.svg)


## CVE-2025-61686
 React Router is a router for React. In @react-router/node versions 7.0.0 through 7.9.3, @remix-run/deno prior to version 2.17.2, and @remix-run/node prior to version 2.17.2, if createFileSessionStorage() is being used from @react-router/node (or @remix-run/node/@remix-run/deno in Remix v2) with an unsigned cookie, it is possible for an attacker to cause the session to try to read/write from a location outside the specified session file directory. The success of the attack would depend on the permissions of the web server process to access those files. Read files cannot be returned directly to the attacker. Session file reads would only succeed if the file matched the expected session file format. If the file matched the session file format, the data would be populated into the server side session but not directly returned to the attacker unless the application logic returned specific session information. This issue has been patched in @react-router/node version 7.9.4, @remix-run/deno version 2.17.2, and @remix-run/node version 2.17.2.

- [https://github.com/ibreakthingsforaliving/CVE-2025-61686-PoC](https://github.com/ibreakthingsforaliving/CVE-2025-61686-PoC) :  ![starts](https://img.shields.io/github/stars/ibreakthingsforaliving/CVE-2025-61686-PoC.svg) ![forks](https://img.shields.io/github/forks/ibreakthingsforaliving/CVE-2025-61686-PoC.svg)


## CVE-2025-59057
 React Router is a router for React. In @remix-run/react versions 1.15.0 through 2.17.0. and react-router versions 7.0.0 through 7.8.2, a XSS vulnerability exists in in React Router's meta()/Meta APIs in Framework Mode when generating script:ld+json tags which could allow arbitrary JavaScript execution during SSR if untrusted content is used to generate the tag. There is no impact if the application is being used in Declarative Mode (BrowserRouter) or Data Mode (createBrowserRouter/RouterProvider). This issue has been patched in @remix-run/react version 2.17.1 and react-router version 7.9.0.

- [https://github.com/ibreakthingsforaliving/CVE-2025-59057-PoC](https://github.com/ibreakthingsforaliving/CVE-2025-59057-PoC) :  ![starts](https://img.shields.io/github/stars/ibreakthingsforaliving/CVE-2025-59057-PoC.svg) ![forks](https://img.shields.io/github/forks/ibreakthingsforaliving/CVE-2025-59057-PoC.svg)


## CVE-2025-53024
 Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.1.10. Easily exploitable vulnerability allows high privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox.  While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products (scope change).  Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.1 Base Score 8.2 (Confidentiality, Integrity and Availability impacts).  CVSS Vector: (CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H).

- [https://github.com/minq0x1412/CVE-2025-53024](https://github.com/minq0x1412/CVE-2025-53024) :  ![starts](https://img.shields.io/github/stars/minq0x1412/CVE-2025-53024.svg) ![forks](https://img.shields.io/github/forks/minq0x1412/CVE-2025-53024.svg)


## CVE-2025-14847
 Mismatched length fields in Zlib compressed protocol headers may allow a read of uninitialized heap memory by an unauthenticated client. This issue affects all MongoDB Server v7.0 prior to 7.0.28 versions, MongoDB Server v8.0 versions prior to 8.0.17, MongoDB Server v8.2 versions prior to 8.2.3, MongoDB Server v6.0 versions prior to 6.0.27, MongoDB Server v5.0 versions prior to 5.0.32, MongoDB Server v4.4 versions prior to 4.4.30, MongoDB Server v4.2 versions greater than or equal to 4.2.0, MongoDB Server v4.0 versions greater than or equal to 4.0.0, and MongoDB Server v3.6 versions greater than or equal to 3.6.0.

- [https://github.com/shokribardiya/CVE-2025-14847-mongobleed](https://github.com/shokribardiya/CVE-2025-14847-mongobleed) :  ![starts](https://img.shields.io/github/stars/shokribardiya/CVE-2025-14847-mongobleed.svg) ![forks](https://img.shields.io/github/forks/shokribardiya/CVE-2025-14847-mongobleed.svg)


## CVE-2025-11953
 The Metro Development Server, which is opened by the React Native Community CLI, binds to external interfaces by default. The server exposes an endpoint that is vulnerable to OS command injection. This allows unauthenticated network attackers to send a POST request to the server and run arbitrary executables. On Windows, the attackers can also execute arbitrary shell commands with fully controlled arguments.

- [https://github.com/ibreakthingsforaliving/CVE-2025-11953-PoC](https://github.com/ibreakthingsforaliving/CVE-2025-11953-PoC) :  ![starts](https://img.shields.io/github/stars/ibreakthingsforaliving/CVE-2025-11953-PoC.svg) ![forks](https://img.shields.io/github/forks/ibreakthingsforaliving/CVE-2025-11953-PoC.svg)


## CVE-2024-3094
Through a series of complex obfuscations, the liblzma build process extracts a prebuilt object file from a disguised test file existing in the source code, which is then used to modify specific functions in the liblzma code. This results in a modified liblzma library that can be used by any software linked against this library, intercepting and modifying the data interaction with this library.

- [https://github.com/nnatsopoulos/xz-backdoor-research](https://github.com/nnatsopoulos/xz-backdoor-research) :  ![starts](https://img.shields.io/github/stars/nnatsopoulos/xz-backdoor-research.svg) ![forks](https://img.shields.io/github/forks/nnatsopoulos/xz-backdoor-research.svg)


## CVE-2023-28303
 Windows Snipping Tool Information Disclosure Vulnerability

- [https://github.com/iqbaalilmii/acropalypse-reconstructor](https://github.com/iqbaalilmii/acropalypse-reconstructor) :  ![starts](https://img.shields.io/github/stars/iqbaalilmii/acropalypse-reconstructor.svg) ![forks](https://img.shields.io/github/forks/iqbaalilmii/acropalypse-reconstructor.svg)


## CVE-2023-21036
 In BitmapExport.java, there is a possible failure to truncate images due to a logic error in the code.Product: AndroidVersions: Android kernelAndroid ID: A-264261868References: N/A

- [https://github.com/iqbaalilmii/acropalypse-reconstructor](https://github.com/iqbaalilmii/acropalypse-reconstructor) :  ![starts](https://img.shields.io/github/stars/iqbaalilmii/acropalypse-reconstructor.svg) ![forks](https://img.shields.io/github/forks/iqbaalilmii/acropalypse-reconstructor.svg)


## CVE-2022-38691
 In BootROM, there is a possible missing validation for Certificate Type 0. This could lead to local escalation of privilege with no additional execution privileges needed.

- [https://github.com/mutur4/CVE-2022-38691](https://github.com/mutur4/CVE-2022-38691) :  ![starts](https://img.shields.io/github/stars/mutur4/CVE-2022-38691.svg) ![forks](https://img.shields.io/github/forks/mutur4/CVE-2022-38691.svg)


## CVE-2022-30190
Please see the MSRC Blog Entry for important information about steps you can take to protect your system from this vulnerability.

- [https://github.com/kaleth4/CVE-2022-30190](https://github.com/kaleth4/CVE-2022-30190) :  ![starts](https://img.shields.io/github/stars/kaleth4/CVE-2022-30190.svg) ![forks](https://img.shields.io/github/forks/kaleth4/CVE-2022-30190.svg)


## CVE-2021-24160
 In the Reponsive Menu (free and Pro) WordPress plugins before 4.0.4, subscribers could upload zip archives containing malicious PHP files that would get extracted to the /rmp-menu/ directory. These files could then be accessed via the front end of the site to trigger remote code execution and ultimately allow an attacker to execute commands to further infect a WordPress site.

- [https://github.com/likeww/Exploit-CVE-2021-24160](https://github.com/likeww/Exploit-CVE-2021-24160) :  ![starts](https://img.shields.io/github/stars/likeww/Exploit-CVE-2021-24160.svg) ![forks](https://img.shields.io/github/forks/likeww/Exploit-CVE-2021-24160.svg)


## CVE-2020-11898
 The Treck TCP/IP stack before 6.0.1.66 improperly handles an IPv4/ICMPv4 Length Parameter Inconsistency, which might allow remote attackers to trigger an information leak.

- [https://github.com/Ransc0rp1on/Ripple20](https://github.com/Ransc0rp1on/Ripple20) :  ![starts](https://img.shields.io/github/stars/Ransc0rp1on/Ripple20.svg) ![forks](https://img.shields.io/github/forks/Ransc0rp1on/Ripple20.svg)


## CVE-2017-2026
 DO NOT USE THIS CANDIDATE NUMBER.  ConsultIDs: none.  Reason: This candidate was in a CNA pool that was not assigned to any issues during 2017.  Notes: none

- [https://github.com/arbabDeveolperEnterpuner/Aether](https://github.com/arbabDeveolperEnterpuner/Aether) :  ![starts](https://img.shields.io/github/stars/arbabDeveolperEnterpuner/Aether.svg) ![forks](https://img.shields.io/github/forks/arbabDeveolperEnterpuner/Aether.svg)

