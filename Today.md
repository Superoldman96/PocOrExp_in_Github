# Update 2026-06-30
## CVE-2026-49048
 The Joomla extension JoomCCK exposes a front-end controller task, that builds two SQL statements by directly concatenating a user-supplied request parameter into the query string without escaping or parameterisation.

- [https://github.com/KARA-git/CVE-2026-49048-JoomCCK-SQLi](https://github.com/KARA-git/CVE-2026-49048-JoomCCK-SQLi) :  ![starts](https://img.shields.io/github/stars/KARA-git/CVE-2026-49048-JoomCCK-SQLi.svg) ![forks](https://img.shields.io/github/forks/KARA-git/CVE-2026-49048-JoomCCK-SQLi.svg)


## CVE-2026-46331
offset_valid() against INT_MIN, where negation is undefined.

- [https://github.com/vulnquest58/dirtyclone-exploit](https://github.com/vulnquest58/dirtyclone-exploit) :  ![starts](https://img.shields.io/github/stars/vulnquest58/dirtyclone-exploit.svg) ![forks](https://img.shields.io/github/forks/vulnquest58/dirtyclone-exploit.svg)


## CVE-2026-43503
so segments drawing frags from frag_list members carry the marker.

- [https://github.com/gl1tch0x1/DirtyClone](https://github.com/gl1tch0x1/DirtyClone) :  ![starts](https://img.shields.io/github/stars/gl1tch0x1/DirtyClone.svg) ![forks](https://img.shields.io/github/forks/gl1tch0x1/DirtyClone.svg)


## CVE-2026-41940
 cPanel and WHM versions after 11.40 contain an authentication bypass vulnerability in the login flow that allows unauthenticated remote attackers to gain unauthorized access to the control panel.

- [https://github.com/aquace/CVE-2026-41940-PoC](https://github.com/aquace/CVE-2026-41940-PoC) :  ![starts](https://img.shields.io/github/stars/aquace/CVE-2026-41940-PoC.svg) ![forks](https://img.shields.io/github/forks/aquace/CVE-2026-41940-PoC.svg)


## CVE-2026-41179
 Rclone is a command-line program to sync files and directories to and from different cloud storage providers. Starting in version 1.48.0 and prior to version 1.73.5, the RC endpoint `operations/fsinfo` is exposed without `AuthRequired: true` and accepts attacker-controlled `fs` input. Because `rc.GetFs(...)` supports inline backend definitions, an unauthenticated attacker can instantiate an attacker-controlled backend on demand. For the WebDAV backend, `bearer_token_command` is executed during backend initialization, making single-request unauthenticated local command execution possible on reachable RC deployments without global HTTP authentication. Version 1.73.5 patches the issue.

- [https://github.com/pssec-io/CVE-2026-41179](https://github.com/pssec-io/CVE-2026-41179) :  ![starts](https://img.shields.io/github/stars/pssec-io/CVE-2026-41179.svg) ![forks](https://img.shields.io/github/forks/pssec-io/CVE-2026-41179.svg)


## CVE-2026-38751
 OpenSTAManager version 2.10 and earlier contains an arbitrary file upload vulnerability in the module update functionality (modules/aggiornamenti/upload_modules.php)

- [https://github.com/Why-Shell/CVE-2026-38751](https://github.com/Why-Shell/CVE-2026-38751) :  ![starts](https://img.shields.io/github/stars/Why-Shell/CVE-2026-38751.svg) ![forks](https://img.shields.io/github/forks/Why-Shell/CVE-2026-38751.svg)


## CVE-2026-32202
 Protection mechanism failure in Windows Shell allows an unauthorized attacker to perform spoofing over a network.

- [https://github.com/1fox23/CVE-2026-32202](https://github.com/1fox23/CVE-2026-32202) :  ![starts](https://img.shields.io/github/stars/1fox23/CVE-2026-32202.svg) ![forks](https://img.shields.io/github/forks/1fox23/CVE-2026-32202.svg)


## CVE-2026-27654
 NGINX Open Source and NGINX Plus have a vulnerability in the ngx_http_dav_module module that might allow an attacker to trigger a buffer overflow to the NGINX worker process; this vulnerability may result in termination of the NGINX worker process or modification of source or destination file names outside the document root. This issue affects NGINX Open Source and NGINX Plus when the configuration file uses DAV module MOVE or COPY methods, prefix location (nonregular expression location configuration), and alias directives. The integrity impact is constrained because the NGINX worker process user has low privileges and does not have access to the entire system. Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

- [https://github.com/dead-lamer/CVE-2026-27654](https://github.com/dead-lamer/CVE-2026-27654) :  ![starts](https://img.shields.io/github/stars/dead-lamer/CVE-2026-27654.svg) ![forks](https://img.shields.io/github/forks/dead-lamer/CVE-2026-27654.svg)


## CVE-2026-24418
 OpenSTAManager is an open source management software for technical assistance and invoicing. OpenSTAManager v2.9.8 and earlier contain a critical Error-Based SQL Injection vulnerability in the bulk operations handler for the Scadenzario (Payment Schedule) module. The application fails to validate that elements of the id_records array are integers before using them in an SQL IN() clause, allowing attackers to inject arbitrary SQL commands and extract sensitive data through XPATH error messages.

- [https://github.com/BridgerAlderson/CVE-2026-24418](https://github.com/BridgerAlderson/CVE-2026-24418) :  ![starts](https://img.shields.io/github/stars/BridgerAlderson/CVE-2026-24418.svg) ![forks](https://img.shields.io/github/forks/BridgerAlderson/CVE-2026-24418.svg)


## CVE-2026-23918
Users are recommended to upgrade to version 2.4.67, which fixes the issue.

- [https://github.com/gagaltotal/CVE-2026-23918-Double-free-Apache-httpd-mod_http2](https://github.com/gagaltotal/CVE-2026-23918-Double-free-Apache-httpd-mod_http2) :  ![starts](https://img.shields.io/github/stars/gagaltotal/CVE-2026-23918-Double-free-Apache-httpd-mod_http2.svg) ![forks](https://img.shields.io/github/forks/gagaltotal/CVE-2026-23918-Double-free-Apache-httpd-mod_http2.svg)


## CVE-2026-23744
 MCPJam inspector is the local-first development platform for MCP servers. Versions 1.4.2 and earlier are vulnerable to remote code execution (RCE) vulnerability, which allows an attacker to send a crafted HTTP request that triggers the installation of an MCP server, leading to RCE. Since MCPJam inspector by default listens on 0.0.0.0 instead of 127.0.0.1, an attacker can trigger the RCE remotely via a simple HTTP request. Version 1.4.3 contains a patch.

- [https://github.com/timgad794/DevHub-HTB-Walkthrough](https://github.com/timgad794/DevHub-HTB-Walkthrough) :  ![starts](https://img.shields.io/github/stars/timgad794/DevHub-HTB-Walkthrough.svg) ![forks](https://img.shields.io/github/forks/timgad794/DevHub-HTB-Walkthrough.svg)


## CVE-2026-12485
      memcpy(&reply_buf[36], g_network_config-ip_addr, v3);

- [https://github.com/0xBlackash/CVE-2026-12485](https://github.com/0xBlackash/CVE-2026-12485) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-12485.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-12485.svg)


## CVE-2026-6921
 Race in GPU in Google Chrome on Windows prior to 147.0.7727.117 allowed a remote attacker to potentially perform a sandbox escape via a crafted video file. (Chromium security severity: Medium)

- [https://github.com/c0gnit00/CVE-2026-69212](https://github.com/c0gnit00/CVE-2026-69212) :  ![starts](https://img.shields.io/github/stars/c0gnit00/CVE-2026-69212.svg) ![forks](https://img.shields.io/github/forks/c0gnit00/CVE-2026-69212.svg)


## CVE-2026-3437
 An improper restriction of operations within the bounds of a memory buffer vulnerability in Portwell Engineering Toolkits version 4.8.2 could allow a local authenticated attacker to read and write to arbitrary memory via the Portwell Engineering Toolkits driver. Successful exploitation of this vulnerability could result in escalation of privileges or cause a denial-of-service condition.

- [https://github.com/tihomirocrew/portwell-lpe](https://github.com/tihomirocrew/portwell-lpe) :  ![starts](https://img.shields.io/github/stars/tihomirocrew/portwell-lpe.svg) ![forks](https://img.shields.io/github/forks/tihomirocrew/portwell-lpe.svg)


## CVE-2025-66680
 An issue in the WiseDelfile64.sys component of WiseCleaner Wise Force Deleter 7.3.2 and earlier allows attackers to delete arbitrary files via a crafted request.

- [https://github.com/skimask1690/WiseDelete](https://github.com/skimask1690/WiseDelete) :  ![starts](https://img.shields.io/github/stars/skimask1690/WiseDelete.svg) ![forks](https://img.shields.io/github/forks/skimask1690/WiseDelete.svg)


## CVE-2025-56399
 alexusmai laravel-file-manager 3.3.1 and before allows an authenticated attacker to achieve Remote Code Execution (RCE) through a crafted file upload. A file with a '.png` extension containing PHP code can be uploaded via the file manager interface. Although the upload appears to fail client-side validation, the file is still saved on the server. The attacker can then use the rename API to change the file extension to `.php`, and upon accessing it via a public URL, the server executes the embedded code.

- [https://github.com/Jenderal92/laravel-filemanager-unrestricted-upload](https://github.com/Jenderal92/laravel-filemanager-unrestricted-upload) :  ![starts](https://img.shields.io/github/stars/Jenderal92/laravel-filemanager-unrestricted-upload.svg) ![forks](https://img.shields.io/github/forks/Jenderal92/laravel-filemanager-unrestricted-upload.svg)


## CVE-2025-55182
 A pre-authentication remote code execution vulnerability exists in React Server Components versions 19.0.0, 19.1.0, 19.1.1, and 19.2.0 including the following packages: react-server-dom-parcel, react-server-dom-turbopack, and react-server-dom-webpack. The vulnerable code unsafely deserializes payloads from HTTP requests to Server Function endpoints.

- [https://github.com/ToritoIO/Torito-R2S](https://github.com/ToritoIO/Torito-R2S) :  ![starts](https://img.shields.io/github/stars/ToritoIO/Torito-R2S.svg) ![forks](https://img.shields.io/github/forks/ToritoIO/Torito-R2S.svg)


## CVE-2025-24893
 XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Any guest can perform arbitrary remote code execution through a request to `SolrSearch`. This impacts the confidentiality, integrity and availability of the whole XWiki installation. To reproduce on an instance, without being logged in, go to `host/xwiki/bin/get/Main/SolrSearch?media=rss&text=%7D%7D%7D%7B%7Basync%20async%3Dfalse%7D%7D%7B%7Bgroovy%7D%7Dprintln%28"Hello%20from"%20%2B%20"%20search%20text%3A"%20%2B%20%2823%20%2B%2019%29%29%7B%7B%2Fgroovy%7D%7D%7B%7B%2Fasync%7D%7D%20`. If there is an output, and the title of the RSS feed contains `Hello from search text:42`, then the instance is vulnerable. This vulnerability has been patched in XWiki 15.10.11, 16.4.1 and 16.5.0RC1. Users are advised to upgrade. Users unable to upgrade may edit `Main.SolrSearchMacros` in `SolrSearchMacros.xml` on line 955 to match the `rawResponse` macro in `macros.vm#L2824` with a content type of `application/xml`, instead of simply outputting the content of the feed.

- [https://github.com/anxs3c/editor_machine_writeup](https://github.com/anxs3c/editor_machine_writeup) :  ![starts](https://img.shields.io/github/stars/anxs3c/editor_machine_writeup.svg) ![forks](https://img.shields.io/github/forks/anxs3c/editor_machine_writeup.svg)


## CVE-2024-29973
The command injection vulnerability in the “setCookie” parameter in Zyxel NAS326 firmware versions before V5.21(AAZF.17)C0 and NAS542 firmware versions before V5.21(ABAG.14)C0 could allow an unauthenticated attacker to execute some operating system (OS) commands by sending a crafted HTTP POST request.

- [https://github.com/h21n/CVE-2024-29973](https://github.com/h21n/CVE-2024-29973) :  ![starts](https://img.shields.io/github/stars/h21n/CVE-2024-29973.svg) ![forks](https://img.shields.io/github/forks/h21n/CVE-2024-29973.svg)


## CVE-2024-24919
 Potentially allowing an attacker to read certain information on Check Point Security Gateways once connected to the internet and enabled with remote Access VPN or Mobile Access Software Blades. A Security fix that mitigates this vulnerability is available.

- [https://github.com/h21n/CVE-2024-24919](https://github.com/h21n/CVE-2024-24919) :  ![starts](https://img.shields.io/github/stars/h21n/CVE-2024-24919.svg) ![forks](https://img.shields.io/github/forks/h21n/CVE-2024-24919.svg)


## CVE-2024-7593
 Incorrect implementation of an authentication algorithm in Ivanti vTM other than versions 22.2R1 or 22.7R2 allows a remote unauthenticated attacker to bypass authentication of the admin panel.

- [https://github.com/h21n/CVE-2024-7593](https://github.com/h21n/CVE-2024-7593) :  ![starts](https://img.shields.io/github/stars/h21n/CVE-2024-7593.svg) ![forks](https://img.shields.io/github/forks/h21n/CVE-2024-7593.svg)


## CVE-2024-2876
 The Email Subscribers by Icegram Express – Email Marketing, Newsletters, Automation for WordPress & WooCommerce plugin for WordPress is vulnerable to SQL Injection via the 'run' function of the 'IG_ES_Subscribers_Query' class in all versions up to, and including, 5.7.14 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/h21n/CVE-2024-2876](https://github.com/h21n/CVE-2024-2876) :  ![starts](https://img.shields.io/github/stars/h21n/CVE-2024-2876.svg) ![forks](https://img.shields.io/github/forks/h21n/CVE-2024-2876.svg)


## CVE-2023-20696
 In preloader, there is a possible out of bounds write due to a missing bounds check. This could lead to local escalation of privilege with System execution privileges needed. User interaction is not needed for exploitation. Patch ID: ALPS07856356 / ALPS07874388 (For MT6880 and MT6890 only); Issue ID: ALPS07856356 / ALPS07874388 (For MT6880 and MT6890 only).

- [https://github.com/kasnria001/pwnage24mtk](https://github.com/kasnria001/pwnage24mtk) :  ![starts](https://img.shields.io/github/stars/kasnria001/pwnage24mtk.svg) ![forks](https://img.shields.io/github/forks/kasnria001/pwnage24mtk.svg)


## CVE-2023-0386
 A flaw was found in the Linux kernel, where unauthorized access to the execution of the setuid file with capabilities was found in the Linux kernel’s OverlayFS subsystem in how a user copies a capable file from a nosuid mount into another mount. This uid mapping bug allows a local user to escalate their privileges on the system.

- [https://github.com/pwncone/CVE-2023-0386-OverlayFS](https://github.com/pwncone/CVE-2023-0386-OverlayFS) :  ![starts](https://img.shields.io/github/stars/pwncone/CVE-2023-0386-OverlayFS.svg) ![forks](https://img.shields.io/github/forks/pwncone/CVE-2023-0386-OverlayFS.svg)


## CVE-2022-22963
 In Spring Cloud Function versions 3.1.6, 3.2.2 and older unsupported versions, when using routing functionality it is possible for a user to provide a specially crafted SpEL as a routing-expression that may result in remote code execution and access to local resources.

- [https://github.com/xmqaq/CVE-2022-22963](https://github.com/xmqaq/CVE-2022-22963) :  ![starts](https://img.shields.io/github/stars/xmqaq/CVE-2022-22963.svg) ![forks](https://img.shields.io/github/forks/xmqaq/CVE-2022-22963.svg)


## CVE-2022-0847
 A flaw was found in the way the "flags" member of the new pipe buffer structure was lacking proper initialization in copy_page_to_iter_pipe and push_pipe functions in the Linux kernel and could thus contain stale values. An unprivileged local user could use this flaw to write to pages in the page cache backed by read only files and as such escalate their privileges on the system.

- [https://github.com/Scouserr/cve-2022-0847-poc-dockerimage](https://github.com/Scouserr/cve-2022-0847-poc-dockerimage) :  ![starts](https://img.shields.io/github/stars/Scouserr/cve-2022-0847-poc-dockerimage.svg) ![forks](https://img.shields.io/github/forks/Scouserr/cve-2022-0847-poc-dockerimage.svg)


## CVE-2020-7247
 smtp_mailaddr in smtp_session.c in OpenSMTPD 6.6, as used in OpenBSD 6.6 and other products, allows remote attackers to execute arbitrary commands as root via a crafted SMTP session, as demonstrated by shell metacharacters in a MAIL FROM field. This affects the "uncommented" default configuration. The issue exists because of an incorrect return value upon failure of input validation.

- [https://github.com/solmin111/OpenSMTPD-CVE-2020-7247-](https://github.com/solmin111/OpenSMTPD-CVE-2020-7247-) :  ![starts](https://img.shields.io/github/stars/solmin111/OpenSMTPD-CVE-2020-7247-.svg) ![forks](https://img.shields.io/github/forks/solmin111/OpenSMTPD-CVE-2020-7247-.svg)


## CVE-2020-0796
 A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 3.1.1 (SMBv3) protocol handles certain requests, aka 'Windows SMBv3 Client/Server Remote Code Execution Vulnerability'.

- [https://github.com/z3ena/Exploiting-and-Mitigating-CVE-2020-0796-SMBGhost-and-Print-Spooler-Vulnerabilities](https://github.com/z3ena/Exploiting-and-Mitigating-CVE-2020-0796-SMBGhost-and-Print-Spooler-Vulnerabilities) :  ![starts](https://img.shields.io/github/stars/z3ena/Exploiting-and-Mitigating-CVE-2020-0796-SMBGhost-and-Print-Spooler-Vulnerabilities.svg) ![forks](https://img.shields.io/github/forks/z3ena/Exploiting-and-Mitigating-CVE-2020-0796-SMBGhost-and-Print-Spooler-Vulnerabilities.svg)


## CVE-2018-18778
 ACME mini_httpd before 1.30 lets remote users read arbitrary files.

- [https://github.com/K3ysTr0K3R/CVE-2018-18778](https://github.com/K3ysTr0K3R/CVE-2018-18778) :  ![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2018-18778.svg) ![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2018-18778.svg)


## CVE-2012-2459
 Unspecified vulnerability in bitcoind and Bitcoin-Qt before 0.4.6, 0.5.x before 0.5.5, 0.6.0.x before 0.6.0.7, and 0.6.x before 0.6.2 allows remote attackers to cause a denial of service (block-processing outage and incorrect block count) via unknown behavior on a Bitcoin network.

- [https://github.com/systemslibrarian/crypto-lab-merkle-proofs](https://github.com/systemslibrarian/crypto-lab-merkle-proofs) :  ![starts](https://img.shields.io/github/stars/systemslibrarian/crypto-lab-merkle-proofs.svg) ![forks](https://img.shields.io/github/forks/systemslibrarian/crypto-lab-merkle-proofs.svg)

