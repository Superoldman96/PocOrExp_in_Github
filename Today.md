# Update 2026-07-01
## CVE-2026-56782
 Gorse before 0.5.10 contains an authentication bypass vulnerability in the /api/dump and /api/restore endpoints that allows unauthenticated attackers to access protected functionality when admin_api_key is empty, which is the default configuration. Remote attackers can exfiltrate the entire database including user records, items, and feedback data containing personally identifiable information, or completely overwrite the dataset without authentication.

- [https://github.com/BiiTts/CVE-2026-56782-Gorse-Auth-Bypass](https://github.com/BiiTts/CVE-2026-56782-Gorse-Auth-Bypass) :  ![starts](https://img.shields.io/github/stars/BiiTts/CVE-2026-56782-Gorse-Auth-Bypass.svg) ![forks](https://img.shields.io/github/forks/BiiTts/CVE-2026-56782-Gorse-Auth-Bypass.svg)


## CVE-2026-55200
 libssh2 through 1.11.1, fixed in commit 7acf3df contains an out-of-bounds write vulnerability in ssh2_transport_read() that fails to enforce upper bounds on packet_length field. Remote attackers can send crafted SSH packets with excessively large packet_length values to corrupt heap memory and achieve remote code execution.

- [https://github.com/xd20111/CVE-2026-55200](https://github.com/xd20111/CVE-2026-55200) :  ![starts](https://img.shields.io/github/stars/xd20111/CVE-2026-55200.svg) ![forks](https://img.shields.io/github/forks/xd20111/CVE-2026-55200.svg)


## CVE-2026-53753
 Crawl4AI is an open-source LLM friendly web crawler & scraper. Prior to 0.8.7, the _safe_eval_expression() function in the computed fields feature uses an AST validator that only blocks attributes starting with underscore. Python generator and frame object attributes (gi_frame, f_back, f_builtins) do NOT start with underscore, enabling a complete sandbox escape to achieve arbitrary code execution. The attack requires no authentication (JWT disabled by default) and is triggered via POST /crawl with a crafted extraction schema. This vulnerability is fixed in 0.8.7.

- [https://github.com/BiiTts/CVE-2026-53753-Crawl4AI-RCE](https://github.com/BiiTts/CVE-2026-53753-Crawl4AI-RCE) :  ![starts](https://img.shields.io/github/stars/BiiTts/CVE-2026-53753-Crawl4AI-RCE.svg) ![forks](https://img.shields.io/github/forks/BiiTts/CVE-2026-53753-Crawl4AI-RCE.svg)


## CVE-2026-48939
 A vulnerability in the iCagenda extension for Joomla allows the upload of arbitrary files in the file attachment feature, ultimately resulting in PHP code upload and execution.

- [https://github.com/Polosss/By-Poloss..-..CVE-2026-48939](https://github.com/Polosss/By-Poloss..-..CVE-2026-48939) :  ![starts](https://img.shields.io/github/stars/Polosss/By-Poloss..-..CVE-2026-48939.svg) ![forks](https://img.shields.io/github/forks/Polosss/By-Poloss..-..CVE-2026-48939.svg)


## CVE-2026-48908
 A vulnerability in SP Page Builder for Joomla allows unauthenticated users to upload arbitrary files, ultimately resulting in the upload and execution of PHP code.

- [https://github.com/ayiezola/CVE-2026-48908](https://github.com/ayiezola/CVE-2026-48908) :  ![starts](https://img.shields.io/github/stars/ayiezola/CVE-2026-48908.svg) ![forks](https://img.shields.io/github/forks/ayiezola/CVE-2026-48908.svg)


## CVE-2026-48907
 A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

- [https://github.com/Almavj/Joomla_CVE_2026_48907](https://github.com/Almavj/Joomla_CVE_2026_48907) :  ![starts](https://img.shields.io/github/stars/Almavj/Joomla_CVE_2026_48907.svg) ![forks](https://img.shields.io/github/forks/Almavj/Joomla_CVE_2026_48907.svg)
- [https://github.com/xitexploiter96-dot/CVE-2026-48907-](https://github.com/xitexploiter96-dot/CVE-2026-48907-) :  ![starts](https://img.shields.io/github/stars/xitexploiter96-dot/CVE-2026-48907-.svg) ![forks](https://img.shields.io/github/forks/xitexploiter96-dot/CVE-2026-48907-.svg)
- [https://github.com/K3ysTr0K3R/CVE-2026-48907](https://github.com/K3ysTr0K3R/CVE-2026-48907) :  ![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2026-48907.svg) ![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2026-48907.svg)


## CVE-2026-46817
 Vulnerability in the Oracle Payments product of Oracle E-Business Suite (component: File Transmission).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle Payments.  Successful attacks of this vulnerability can result in takeover of Oracle Payments. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

- [https://github.com/0xBlackash/CVE-2026-46817](https://github.com/0xBlackash/CVE-2026-46817) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-46817.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-46817.svg)


## CVE-2026-46331
offset_valid() against INT_MIN, where negation is undefined.

- [https://github.com/Quaerendir/cve-2026-46331-audit](https://github.com/Quaerendir/cve-2026-46331-audit) :  ![starts](https://img.shields.io/github/stars/Quaerendir/cve-2026-46331-audit.svg) ![forks](https://img.shields.io/github/forks/Quaerendir/cve-2026-46331-audit.svg)


## CVE-2026-43503
so segments drawing frags from frag_list members carry the marker.

- [https://github.com/entra1337/DirtyClone](https://github.com/entra1337/DirtyClone) :  ![starts](https://img.shields.io/github/stars/entra1337/DirtyClone.svg) ![forks](https://img.shields.io/github/forks/entra1337/DirtyClone.svg)
- [https://github.com/SecureWithUmer/CVE-2026-43503](https://github.com/SecureWithUmer/CVE-2026-43503) :  ![starts](https://img.shields.io/github/stars/SecureWithUmer/CVE-2026-43503.svg) ![forks](https://img.shields.io/github/forks/SecureWithUmer/CVE-2026-43503.svg)


## CVE-2026-37637
 An issue in Alexantr filemanager v.1.0 allows a remote attacker to execute arbitrary code via the filemanager.php component

- [https://github.com/SLO-CYBER-SEC/CVE-2026-37637](https://github.com/SLO-CYBER-SEC/CVE-2026-37637) :  ![starts](https://img.shields.io/github/stars/SLO-CYBER-SEC/CVE-2026-37637.svg) ![forks](https://img.shields.io/github/forks/SLO-CYBER-SEC/CVE-2026-37637.svg)


## CVE-2026-36848
 Gigamon GVOS v5.16.1 and below is vulnerable to Directory Traversal in the GVOS H-VUE subsystem.

- [https://github.com/calligraf0/CVE-2026-36848](https://github.com/calligraf0/CVE-2026-36848) :  ![starts](https://img.shields.io/github/stars/calligraf0/CVE-2026-36848.svg) ![forks](https://img.shields.io/github/forks/calligraf0/CVE-2026-36848.svg)


## CVE-2026-31431
AD directly.

- [https://github.com/pedromizz/copy-fail](https://github.com/pedromizz/copy-fail) :  ![starts](https://img.shields.io/github/stars/pedromizz/copy-fail.svg) ![forks](https://img.shields.io/github/forks/pedromizz/copy-fail.svg)


## CVE-2026-28496
 FOSSBilling is a free, open-source billing and client management system. Versions prior to 0.8.0 have a Server-Side Template Injection (SSTI) vulnerability in the template rendering system. Administrators with access to features that render Twig templates (email templates, mass mail campaigns, custom payment adapters, and the `string_render` API endpoint) can inject arbitrary Twig expressions, leading to information disclosure and remote code execution. The vulnerability exists because Twig templates are rendered without a sandbox, allowing access to the full Twig environment, API context, and the application's dependency injection container. Version 0.8.0 patches the issue. Some workarounds are available. Audit existing email templates for suspicious Twig expressions, rotate all admin and client API tokens, and/or block external access to /api/system/* at reverse proxy/WAF to mitigate chaining with GHSA-78x5-c8gw-8279.

- [https://github.com/rootdirective-sec/CVE-2026-28496-Lab](https://github.com/rootdirective-sec/CVE-2026-28496-Lab) :  ![starts](https://img.shields.io/github/stars/rootdirective-sec/CVE-2026-28496-Lab.svg) ![forks](https://img.shields.io/github/forks/rootdirective-sec/CVE-2026-28496-Lab.svg)


## CVE-2026-22226
Build 20260430.

- [https://github.com/LucasVanHaaren/CVE-2026-22226](https://github.com/LucasVanHaaren/CVE-2026-22226) :  ![starts](https://img.shields.io/github/stars/LucasVanHaaren/CVE-2026-22226.svg) ![forks](https://img.shields.io/github/forks/LucasVanHaaren/CVE-2026-22226.svg)


## CVE-2026-20253
 In Splunk Enterprise 10.2 versions below 10.2.4 and 10 versions below 10.0.7, an unauthenticated user could create or truncate arbitrary files through a PostgreSQL sidecar service endpoint. The vulnerability exists because the PostgreSQL sidecar service endpoint lacks authentication controls, allowing any network-reachable user to invoke file operations without credentials. Splunk Enterprise versions 9.4 and earlier are not affected. If you cannot immediately upgrade to a fixed version, you can mitigate this vulnerability by disabling the PostgreSQL sidecar service.

- [https://github.com/pssec-io/CVE-2026-20253](https://github.com/pssec-io/CVE-2026-20253) :  ![starts](https://img.shields.io/github/stars/pssec-io/CVE-2026-20253.svg) ![forks](https://img.shields.io/github/forks/pssec-io/CVE-2026-20253.svg)


## CVE-2026-9082
This issue affects Drupal core: from 8.9.0 before 10.4.10, from 10.5.0 before 10.5.10, from 10.6.0 before 10.6.9, from 11.0.0 before 11.1.10, from 11.2.0 before 11.2.12, from 11.3.0 before 11.3.10.

- [https://github.com/evidencebasedvulnerability/cve-2026-9082-drupal](https://github.com/evidencebasedvulnerability/cve-2026-9082-drupal) :  ![starts](https://img.shields.io/github/stars/evidencebasedvulnerability/cve-2026-9082-drupal.svg) ![forks](https://img.shields.io/github/forks/evidencebasedvulnerability/cve-2026-9082-drupal.svg)


## CVE-2026-8023
 Zephyr's HTTP server (subsys/net/lib/http) provides a static-filesystem resource type (HTTP_RESOURCE_TYPE_STATIC_FS, available when CONFIG_FILE_SYSTEM is enabled) that serves files from a configured root directory. Before this fix, both the HTTP/1 and HTTP/2 front-ends placed the raw, attacker-controlled request path into client-url_buffer (assembled in on_url() for HTTP/1 and copied verbatim from the :path pseudo-header for HTTP/2) without resolving ./.. segments. The static-FS handler then built the on-disk filename by directly concatenating the configured root with that raw URL (snprintk(fname, ..., "%s%s", static_fs_detail-fs_path, client-url_buffer) at http_server_http1.c:603 and http_server_http2.c:490) and opened it with fs_open(fname, FS_O_READ). Because the handler is reached via wildcard/leading-dir (fnmatch FNM_LEADING_DIR) or fallback resource matching, a request such as GET /prefix/../../file is dispatched to the handler and, after the underlying filesystem (e.g. LittleFS/FAT) resolves the .. segments, escapes the configured web root, letting an unauthenticated remote client read arbitrary readable files on the mounted volume (information disclosure). The HTTP server requires no TLS or authentication to reach this path. The fix adds http_server_remove_dot_segments(), which canonicalizes the path portion of the URL before resource lookup in both protocol handlers, neutralizing the traversal. Affects releases v4.0.0 through v4.4.0 for deployments that register a static-filesystem resource.

- [https://github.com/ret2c/CVE-2026-8023](https://github.com/ret2c/CVE-2026-8023) :  ![starts](https://img.shields.io/github/stars/ret2c/CVE-2026-8023.svg) ![forks](https://img.shields.io/github/forks/ret2c/CVE-2026-8023.svg)


## CVE-2026-5562
 A vulnerability was identified in provectus kafka-ui up to 0.7.2. This impacts the function validateAccess of the file /api/smartfilters/testexecutions of the component Endpoint. The manipulation leads to code injection. The attack can be initiated remotely. The exploit is publicly available and might be used. The vendor was contacted early about this disclosure but did not respond in any way.

- [https://github.com/HutTwoThreeFour/CVE-2026-5562-Exploit](https://github.com/HutTwoThreeFour/CVE-2026-5562-Exploit) :  ![starts](https://img.shields.io/github/stars/HutTwoThreeFour/CVE-2026-5562-Exploit.svg) ![forks](https://img.shields.io/github/forks/HutTwoThreeFour/CVE-2026-5562-Exploit.svg)


## CVE-2026-1134
 A vulnerability was identified in itsourcecode Society Management System 1.0. This affects an unknown function of the file /admin/expenses.php. The manipulation of the argument detail leads to cross site scripting. The attack may be initiated remotely. The exploit is publicly available and might be used.

- [https://github.com/Hann1bl3L3ct3r/CVE-2026-11349](https://github.com/Hann1bl3L3ct3r/CVE-2026-11349) :  ![starts](https://img.shields.io/github/stars/Hann1bl3L3ct3r/CVE-2026-11349.svg) ![forks](https://img.shields.io/github/forks/Hann1bl3L3ct3r/CVE-2026-11349.svg)


## CVE-2025-69212
 OpenSTAManager is an open source management software for technical assistance and invoicing. In 2.9.8 and earlier, a critical OS Command Injection vulnerability exists in the P7M (signed XML) file decoding functionality. An authenticated attacker can upload a ZIP file containing a .p7m file with a malicious filename to execute arbitrary system commands on the server.

- [https://github.com/w3nch/CVE-2025-69212](https://github.com/w3nch/CVE-2025-69212) :  ![starts](https://img.shields.io/github/stars/w3nch/CVE-2025-69212.svg) ![forks](https://img.shields.io/github/forks/w3nch/CVE-2025-69212.svg)
- [https://github.com/jonathan-corbin/CVE-2025-69212-Authenticated-RCE-PoC](https://github.com/jonathan-corbin/CVE-2025-69212-Authenticated-RCE-PoC) :  ![starts](https://img.shields.io/github/stars/jonathan-corbin/CVE-2025-69212-Authenticated-RCE-PoC.svg) ![forks](https://img.shields.io/github/forks/jonathan-corbin/CVE-2025-69212-Authenticated-RCE-PoC.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-resolutions](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-resolutions) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-resolutions.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-resolutions.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-15x](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-15x) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-15x.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-15x.svg)


## CVE-2025-31161
 CrushFTP 10 before 10.8.4 and 11 before 11.3.1 allows authentication bypass and takeover of the crushadmin account (unless a DMZ proxy instance is used), as exploited in the wild in March and April 2025, aka "Unauthenticated HTTP(S) port access." A race condition exists in the AWS4-HMAC (compatible with S3) authorization method of the HTTP component of the FTP server. The server first verifies the existence of the user by performing a call to login_user_pass() with no password requirement. This will authenticate the session through the HMAC verification process and up until the server checks for user verification once more. The vulnerability can be further stabilized, eliminating the need for successfully triggering a race condition, by sending a mangled AWS4-HMAC header. By providing only the username and a following slash (/), the server will successfully find a username, which triggers the successful anypass authentication process, but the server will fail to find the expected SignedHeaders entry, resulting in an index-out-of-bounds error that stops the code from reaching the session cleanup. Together, these issues make it trivial to authenticate as any known or guessable user (e.g., crushadmin), and can lead to a full compromise of the system by obtaining an administrative account.

- [https://github.com/rufflabs/crushftp_cve-2025-31161](https://github.com/rufflabs/crushftp_cve-2025-31161) :  ![starts](https://img.shields.io/github/stars/rufflabs/crushftp_cve-2025-31161.svg) ![forks](https://img.shields.io/github/forks/rufflabs/crushftp_cve-2025-31161.svg)
- [https://github.com/rufflabs/ludus_crushftp_cve-2025-31161](https://github.com/rufflabs/ludus_crushftp_cve-2025-31161) :  ![starts](https://img.shields.io/github/stars/rufflabs/ludus_crushftp_cve-2025-31161.svg) ![forks](https://img.shields.io/github/forks/rufflabs/ludus_crushftp_cve-2025-31161.svg)
- [https://github.com/rufflabs/ludus_crushftp_cve-2025-31161_sim](https://github.com/rufflabs/ludus_crushftp_cve-2025-31161_sim) :  ![starts](https://img.shields.io/github/stars/rufflabs/ludus_crushftp_cve-2025-31161_sim.svg) ![forks](https://img.shields.io/github/forks/rufflabs/ludus_crushftp_cve-2025-31161_sim.svg)


## CVE-2025-24203
 The issue was addressed with improved checks. This issue is fixed in iOS 18.4 and iPadOS 18.4, iPadOS 17.7.6, macOS Sequoia 15.4, macOS Sonoma 14.7.5, macOS Ventura 13.7.5, tvOS 18.4, visionOS 2.4, watchOS 11.4. An app may be able to modify protected parts of the file system.

- [https://github.com/jailbreakdotparty/dirtyZero](https://github.com/jailbreakdotparty/dirtyZero) :  ![starts](https://img.shields.io/github/stars/jailbreakdotparty/dirtyZero.svg) ![forks](https://img.shields.io/github/forks/jailbreakdotparty/dirtyZero.svg)


## CVE-2025-10576
 Potential vulnerabilities have been identified in the audio package for certain HP PC products using the Sound Research SECOMN64 driver, which might allow escalation of privilege. HP is releasing updated audio packages to mitigate the potential vulnerabilities.

- [https://github.com/R41N3RZUF477/CVE-2025-10576](https://github.com/R41N3RZUF477/CVE-2025-10576) :  ![starts](https://img.shields.io/github/stars/R41N3RZUF477/CVE-2025-10576.svg) ![forks](https://img.shields.io/github/forks/R41N3RZUF477/CVE-2025-10576.svg)


## CVE-2025-0133
For GlobalProtect users with Clientless VPN enabled, there is a limited impact on confidentiality due to inherent risks of Clientless VPN that facilitate credential theft. You can read more about this risk in the informational bulletin  PAN-SA-2025-0005 https://security.paloaltonetworks.com/PAN-SA-2025-0005   https://security.paloaltonetworks.com/PAN-SA-2025-0005 . There is no impact to confidentiality for GlobalProtect users if you did not enable (or you disable) Clientless VPN.

- [https://github.com/radityahack/cve-2025-0133](https://github.com/radityahack/cve-2025-0133) :  ![starts](https://img.shields.io/github/stars/radityahack/cve-2025-0133.svg) ![forks](https://img.shields.io/github/forks/radityahack/cve-2025-0133.svg)


## CVE-2024-24824
 Graylog is a free and open log management platform. Starting in version 2.0.0 and prior to versions 5.1.11 and 5.2.4, arbitrary classes can be loaded and instantiated using a HTTP PUT request to the `/api/system/cluster_config/` endpoint. Graylog's cluster config system uses fully qualified class names as config keys. To validate the existence of the requested class before using them, Graylog loads the class using the class loader. If a user with the appropriate permissions performs the request, arbitrary classes with 1-arg String constructors can be instantiated. This will execute arbitrary code that is run during class instantiation. In the specific use case of `java.io.File`, the behavior of the internal web-server stack will lead to information exposure by including the entire file content in the response to the REST request. Versions 5.1.11 and 5.2.4 contain a fix for this issue.

- [https://github.com/rootkiTED/graylog-cve-2024-24824-exploit](https://github.com/rootkiTED/graylog-cve-2024-24824-exploit) :  ![starts](https://img.shields.io/github/stars/rootkiTED/graylog-cve-2024-24824-exploit.svg) ![forks](https://img.shields.io/github/forks/rootkiTED/graylog-cve-2024-24824-exploit.svg)


## CVE-2024-9264
 The SQL Expressions experimental feature of Grafana allows for the evaluation of `duckdb` queries containing user input. These queries are insufficiently sanitized before being passed to `duckdb`, leading to a command injection and local file inclusion vulnerability. Any user with the VIEWER or higher permission is capable of executing this attack.  The `duckdb` binary must be present in Grafana's $PATH for this attack to function; by default, this binary is not installed in Grafana distributions.

- [https://github.com/yeonchoda/CVE-2024-9264](https://github.com/yeonchoda/CVE-2024-9264) :  ![starts](https://img.shields.io/github/stars/yeonchoda/CVE-2024-9264.svg) ![forks](https://img.shields.io/github/forks/yeonchoda/CVE-2024-9264.svg)


## CVE-2024-1086
We recommend upgrading past commit f342de4e2f33e0e39165d8639387aa6c19dff660.

- [https://github.com/JHarv613/CVE_2024_1086_vulnerability_check](https://github.com/JHarv613/CVE_2024_1086_vulnerability_check) :  ![starts](https://img.shields.io/github/stars/JHarv613/CVE_2024_1086_vulnerability_check.svg) ![forks](https://img.shields.io/github/forks/JHarv613/CVE_2024_1086_vulnerability_check.svg)


## CVE-2023-43364
 main.py in Searchor before 2.4.2 uses eval on CLI input, which may cause unexpected code execution.

- [https://github.com/Herick-Costa/CVE-2023-43364-Searchor-RCE-Exploit](https://github.com/Herick-Costa/CVE-2023-43364-Searchor-RCE-Exploit) :  ![starts](https://img.shields.io/github/stars/Herick-Costa/CVE-2023-43364-Searchor-RCE-Exploit.svg) ![forks](https://img.shields.io/github/forks/Herick-Costa/CVE-2023-43364-Searchor-RCE-Exploit.svg)


## CVE-2023-41772
 Win32k Elevation of Privilege Vulnerability

- [https://github.com/R41N3RZUF477/CVE-2023-41772](https://github.com/R41N3RZUF477/CVE-2023-41772) :  ![starts](https://img.shields.io/github/stars/R41N3RZUF477/CVE-2023-41772.svg) ![forks](https://img.shields.io/github/forks/R41N3RZUF477/CVE-2023-41772.svg)


## CVE-2023-38646
 Metabase open source before 0.46.6.1 and Metabase Enterprise before 1.46.6.1 allow attackers to execute arbitrary commands on the server, at the server's privilege level. Authentication is not required for exploitation. The other fixed versions are 0.45.4.1, 1.45.4.1, 0.44.7.1, 1.44.7.1, 0.43.7.2, and 1.43.7.2.

- [https://github.com/nuclide-research/metabase-cve-2023-38646](https://github.com/nuclide-research/metabase-cve-2023-38646) :  ![starts](https://img.shields.io/github/stars/nuclide-research/metabase-cve-2023-38646.svg) ![forks](https://img.shields.io/github/forks/nuclide-research/metabase-cve-2023-38646.svg)


## CVE-2023-4911
 A buffer overflow was discovered in the GNU C Library's dynamic loader ld.so while processing the GLIBC_TUNABLES environment variable. This issue could allow a local attacker to use maliciously crafted GLIBC_TUNABLES environment variables when launching binaries with SUID permission to execute code with elevated privileges.

- [https://github.com/jarpex/cve-2023-4911-exploit-optimized](https://github.com/jarpex/cve-2023-4911-exploit-optimized) :  ![starts](https://img.shields.io/github/stars/jarpex/cve-2023-4911-exploit-optimized.svg) ![forks](https://img.shields.io/github/forks/jarpex/cve-2023-4911-exploit-optimized.svg)


## CVE-2022-22965
 A Spring MVC or Spring WebFlux application running on JDK 9+ may be vulnerable to remote code execution (RCE) via data binding. The specific exploit requires the application to run on Tomcat as a WAR deployment. If the application is deployed as a Spring Boot executable jar, i.e. the default, it is not vulnerable to the exploit. However, the nature of the vulnerability is more general, and there may be other ways to exploit it.

- [https://github.com/Kuri119/CVE-2022-22965-Spring4Shell](https://github.com/Kuri119/CVE-2022-22965-Spring4Shell) :  ![starts](https://img.shields.io/github/stars/Kuri119/CVE-2022-22965-Spring4Shell.svg) ![forks](https://img.shields.io/github/forks/Kuri119/CVE-2022-22965-Spring4Shell.svg)


## CVE-2021-36368
 An issue was discovered in OpenSSH before 8.9. If a client is using public-key authentication with agent forwarding but without -oLogLevel=verbose, and an attacker has silently modified the server to support the None authentication option, then the user cannot determine whether FIDO authentication is going to confirm that the user wishes to connect to that server, or that the user wishes to allow that server to connect to a different server on the user's behalf. NOTE: the vendor's position is "this is not an authentication bypass, since nothing is being bypassed.

- [https://github.com/ssh-mitm/ssh-mitm](https://github.com/ssh-mitm/ssh-mitm) :  ![starts](https://img.shields.io/github/stars/ssh-mitm/ssh-mitm.svg) ![forks](https://img.shields.io/github/forks/ssh-mitm/ssh-mitm.svg)


## CVE-2021-36367
 PuTTY through 0.75 proceeds with establishing an SSH session even if it has never sent a substantive authentication response. This makes it easier for an attacker-controlled SSH server to present a later spoofed authentication prompt (that the attacker can use to capture credential data, and use that data for purposes that are undesired by the client user).

- [https://github.com/ssh-mitm/ssh-mitm](https://github.com/ssh-mitm/ssh-mitm) :  ![starts](https://img.shields.io/github/stars/ssh-mitm/ssh-mitm.svg) ![forks](https://img.shields.io/github/forks/ssh-mitm/ssh-mitm.svg)


## CVE-2019-2215
 A use-after-free in binder.c allows an elevation of privilege from an application to the Linux Kernel. No user interaction is required to exploit this vulnerability, however exploitation does require either the installation of a malicious local application or a separate vulnerability in a network facing application.Product: AndroidAndroid ID: A-141720095

- [https://github.com/flipphoneguy/root-sonim-xp3800](https://github.com/flipphoneguy/root-sonim-xp3800) :  ![starts](https://img.shields.io/github/stars/flipphoneguy/root-sonim-xp3800.svg) ![forks](https://img.shields.io/github/forks/flipphoneguy/root-sonim-xp3800.svg)


## CVE-2017-7494
 Samba since version 3.5.0 and before 4.6.4, 4.5.10 and 4.4.14 is vulnerable to remote code execution vulnerability, allowing a malicious client to upload a shared library to a writable share, and then cause the server to load and execute it.

- [https://github.com/Sadz1d/IS](https://github.com/Sadz1d/IS) :  ![starts](https://img.shields.io/github/stars/Sadz1d/IS.svg) ![forks](https://img.shields.io/github/forks/Sadz1d/IS.svg)


## CVE-2015-1187
 The ping tool in multiple D-Link and TRENDnet devices allow remote attackers to execute arbitrary code via the ping_addr parameter to ping.ccp.

- [https://github.com/Flanbox/cve-2015-1187-dir820l-reproduction](https://github.com/Flanbox/cve-2015-1187-dir820l-reproduction) :  ![starts](https://img.shields.io/github/stars/Flanbox/cve-2015-1187-dir820l-reproduction.svg) ![forks](https://img.shields.io/github/forks/Flanbox/cve-2015-1187-dir820l-reproduction.svg)


## CVE-2012-1823
 sapi/cgi/cgi_main.c in PHP before 5.3.12 and 5.4.x before 5.4.2, when configured as a CGI script (aka php-cgi), does not properly handle query strings that lack an = (equals sign) character, which allows remote attackers to execute arbitrary code by placing command-line options in the query string, related to lack of skipping a certain php_getopt for the 'd' case.

- [https://github.com/K3ysTr0K3R/CVE-2012-1823](https://github.com/K3ysTr0K3R/CVE-2012-1823) :  ![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2012-1823.svg) ![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2012-1823.svg)

