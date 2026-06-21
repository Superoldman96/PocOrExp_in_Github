# Update 2026-06-21
## CVE-2026-49345
 Mercator is an open source web application that enables mapping of the information system. Prior to version 2025.05.19, a Server-Side Request Forgery (SSRF) vulnerability exists in Mercator's CVE configuration panel (`/admin/config/parameters`). The `testProvider()` method in `ConfigurationController` passes user-supplied input directly to `curl_init()` without validating the scheme, hostname, or destination IP address. An authenticated user with the `configure` permission can force the Mercator server to issue arbitrary outbound network requests. The suffix `/api/dbInfo` appended to the URL can be bypassed by injecting a `#` fragment character (e.g. `http://TARGET/PATH#`), allowing full control over the target URL. No scheme whitelist, host whitelist, or private/loopback IP block is applied. The `telnet://` scheme can be used for internal port scanning; the `gopher://` scheme enables interaction with unauthenticated internal services (Redis, Memcached), potentially leading to Remote Code Execution under specific deployment conditions. Version 2025.05.19 patches the issue.

- [https://github.com/hadhub/CVE-2026-49345-Mercator-SSRF](https://github.com/hadhub/CVE-2026-49345-Mercator-SSRF) :  ![starts](https://img.shields.io/github/stars/hadhub/CVE-2026-49345-Mercator-SSRF.svg) ![forks](https://img.shields.io/github/forks/hadhub/CVE-2026-49345-Mercator-SSRF.svg)


## CVE-2026-49344
 Mercator is an open source web application that enables mapping of the information system. Prior to version 2025.05.19, Mercator's Query Engine (`/admin/queries/execute`) accepts a JSON DSL (`from` / `select` / `filters` / `traverse` / `output`), translates it into an Eloquent query, and returns results as JSON. The controller method `QueryController::execute()` does not enforce an authorization gate, unlike `store()` and `massDestroy()` in the same controller which are correctly protected. As a result, any authenticated account — including the read-only Auditor role — can query models beyond its intended scope, including the `User` model. Additionally, the `password` column, although declared `$hidden`, is not excluded from filter predicates, which allows it to be used in `LIKE` conditions. The `schema()` and `schemaModel()` endpoints of the same controller are similarly unguarded. The Query Engine is read-only; integrity and availability are not affected. Version 2025.05.19 patches the issue.

- [https://github.com/hadhub/CVE-2026-49344-Mercator-JSON-DSL](https://github.com/hadhub/CVE-2026-49344-Mercator-JSON-DSL) :  ![starts](https://img.shields.io/github/stars/hadhub/CVE-2026-49344-Mercator-JSON-DSL.svg) ![forks](https://img.shields.io/github/forks/hadhub/CVE-2026-49344-Mercator-JSON-DSL.svg)


## CVE-2026-48611
 Improper authentication checks in the OAuth implementation allow account hijacking even when OAuth is not configured or enabled leading to unauthorized access in default installations.

- [https://github.com/Diznev/CVE-2026-48611-EXPLOIT](https://github.com/Diznev/CVE-2026-48611-EXPLOIT) :  ![starts](https://img.shields.io/github/stars/Diznev/CVE-2026-48611-EXPLOIT.svg) ![forks](https://img.shields.io/github/forks/Diznev/CVE-2026-48611-EXPLOIT.svg)


## CVE-2026-43515
Users are recommended to upgrade to version 11.0.22, 10.1.55 or 9.0.118 which fix the issue.

- [https://github.com/covepseng/cve-2026-43515-poc](https://github.com/covepseng/cve-2026-43515-poc) :  ![starts](https://img.shields.io/github/stars/covepseng/cve-2026-43515-poc.svg) ![forks](https://img.shields.io/github/forks/covepseng/cve-2026-43515-poc.svg)


## CVE-2026-42530
Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

- [https://github.com/v4ltonn/CVE-2026-42530](https://github.com/v4ltonn/CVE-2026-42530) :  ![starts](https://img.shields.io/github/stars/v4ltonn/CVE-2026-42530.svg) ![forks](https://img.shields.io/github/forks/v4ltonn/CVE-2026-42530.svg)
- [https://github.com/0xBlackash/CVE-2026-42530](https://github.com/0xBlackash/CVE-2026-42530) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-42530.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-42530.svg)
- [https://github.com/HORKimhab/CVE-2026-42530](https://github.com/HORKimhab/CVE-2026-42530) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-42530.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-42530.svg)


## CVE-2026-42055
Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

- [https://github.com/HORKimhab/CVE-2026-42055](https://github.com/HORKimhab/CVE-2026-42055) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-42055.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-42055.svg)


## CVE-2026-25212
 An issue was discovered in Percona PMM before 3.7. Because an internal database user retains specific superuser privileges, an attacker with pmm-admin rights can abuse the "Add data source" feature to break out of the database context and execute shell commands on the underlying operating system.

- [https://github.com/5170Temp/CVE-2026-25212](https://github.com/5170Temp/CVE-2026-25212) :  ![starts](https://img.shields.io/github/stars/5170Temp/CVE-2026-25212.svg) ![forks](https://img.shields.io/github/forks/5170Temp/CVE-2026-25212.svg)


## CVE-2026-12569
  *  The identified vulnerability also impacts Windchill and FlexPLM releases prior to 11.0 M030

- [https://github.com/west-wind/Threat-Hunting-With-Splunk](https://github.com/west-wind/Threat-Hunting-With-Splunk) :  ![starts](https://img.shields.io/github/stars/west-wind/Threat-Hunting-With-Splunk.svg) ![forks](https://img.shields.io/github/forks/west-wind/Threat-Hunting-With-Splunk.svg)


## CVE-2026-11784
 The Optimole – Optimize Images | Convert WebP & AVIF | CDN & Lazy Load | Image Optimization plugin for WordPress is vulnerable to Cross-Site Request Forgery in all versions up to, and including, 4.2.6. This is due to missing or incorrect nonce validation on the replace_file function. This makes it possible for unauthenticated attackers to overwrite existing media attachments with attacker-supplied file content by supplying a forged multipart POST request targeting any attachment the victim has edit_post capability over via a forged request granted they can trick a site administrator into performing an action such as clicking on a link. The forged request requires a victim with at least Author-level privileges, as the handler enforces a current_user_can('edit_post', $id) check; tricking an Author-level or higher user into clicking a crafted link is sufficient to trigger the overwrite against attachments that user can edit.

- [https://github.com/AlexMihailEngineer/CVE-2026-11784-Optimole-CSRF](https://github.com/AlexMihailEngineer/CVE-2026-11784-Optimole-CSRF) :  ![starts](https://img.shields.io/github/stars/AlexMihailEngineer/CVE-2026-11784-Optimole-CSRF.svg) ![forks](https://img.shields.io/github/forks/AlexMihailEngineer/CVE-2026-11784-Optimole-CSRF.svg)


## CVE-2026-11551
 The Branda plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 3.4.29. This is due to the plugin not properly validating a user's identity prior to updating their password. This makes it possible for unauthenticated attackers to change arbitrary user's passwords, including administrators, and leverage that to gain access to their account.

- [https://github.com/Polosss/By-Poloss..-..CVE-2026-11551-PoC](https://github.com/Polosss/By-Poloss..-..CVE-2026-11551-PoC) :  ![starts](https://img.shields.io/github/stars/Polosss/By-Poloss..-..CVE-2026-11551-PoC.svg) ![forks](https://img.shields.io/github/forks/Polosss/By-Poloss..-..CVE-2026-11551-PoC.svg)
- [https://github.com/xxconi/2026-11551](https://github.com/xxconi/2026-11551) :  ![starts](https://img.shields.io/github/stars/xxconi/2026-11551.svg) ![forks](https://img.shields.io/github/forks/xxconi/2026-11551.svg)


## CVE-2026-10523
 An Authentication Bypass vulnerability (CWE-288) in Ivanti Sentry before the R10.5.2, R10.6.2 and R10.7.1 versions allows a remote unauthenticated attacker to create arbitrary administrative accounts and obtain full administrative access

- [https://github.com/gagaltotal/CVE-2026-10523-Ivanti-sentry](https://github.com/gagaltotal/CVE-2026-10523-Ivanti-sentry) :  ![starts](https://img.shields.io/github/stars/gagaltotal/CVE-2026-10523-Ivanti-sentry.svg) ![forks](https://img.shields.io/github/forks/gagaltotal/CVE-2026-10523-Ivanti-sentry.svg)


## CVE-2026-10520
 An OS Command Injection vulnerability in Ivanti Sentry before the R10.5.2, R10.6.2 and R10.7.1 versions allows a remote unauthenticated user to achieve root-level remote code execution

- [https://github.com/gagaltotal/CVE-2026-10523-Ivanti-sentry](https://github.com/gagaltotal/CVE-2026-10523-Ivanti-sentry) :  ![starts](https://img.shields.io/github/stars/gagaltotal/CVE-2026-10523-Ivanti-sentry.svg) ![forks](https://img.shields.io/github/forks/gagaltotal/CVE-2026-10523-Ivanti-sentry.svg)


## CVE-2026-7515
 The BetterDocs Pro plugin for WordPress is vulnerable to Local File Inclusion in versions up to, and including, 3.8.0 via the `doc_style` parameter. This makes it possible for unauthenticated attackers to include and execute arbitrary .php files on the server, allowing the execution of any PHP code in those files. This can be used to bypass access controls, obtain sensitive data, or achieve code execution in cases where .php file types can be uploaded and included.

- [https://github.com/Polosss/By-Poloss..-..CVE-2026-7515-PoC](https://github.com/Polosss/By-Poloss..-..CVE-2026-7515-PoC) :  ![starts](https://img.shields.io/github/stars/Polosss/By-Poloss..-..CVE-2026-7515-PoC.svg) ![forks](https://img.shields.io/github/forks/Polosss/By-Poloss..-..CVE-2026-7515-PoC.svg)
- [https://github.com/izxci/CVE_2026_7515](https://github.com/izxci/CVE_2026_7515) :  ![starts](https://img.shields.io/github/stars/izxci/CVE_2026_7515.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE_2026_7515.svg)


## CVE-2026-5476
 A vulnerability was identified in NASA cFS up to 7.0.0 on 32-bit. Affected is the function CFE_TBL_ValidateCodecLoadSize of the file cfe/modules/tbl/fsw/src/cfe_tbl_passthru_codec.c. The manipulation leads to integer overflow. The complexity of an attack is rather high. The exploitability is told to be difficult. A fix is planned for the upcoming version milestone of the project.

- [https://github.com/Saku0512/CVE-2026-54761-poc](https://github.com/Saku0512/CVE-2026-54761-poc) :  ![starts](https://img.shields.io/github/stars/Saku0512/CVE-2026-54761-poc.svg) ![forks](https://img.shields.io/github/forks/Saku0512/CVE-2026-54761-poc.svg)


## CVE-2026-4782
 The Avada Builder plugin for WordPress is vulnerable to Arbitrary File Read in all versions up to, and including, 3.15.2 via the 'fusion_get_svg_from_file' function with the 'custom_svg' parameter of the 'fusion_section_separator' shortcode. This makes it possible for authenticated attackers, with Subscriber-level access and above, to read the contents of arbitrary files on the server, which can contain sensitive information. The vulnerability was partially patched in version 3.15.2 and fully patched in version 3.15.3.

- [https://github.com/xxconi/CVE-2026-4782](https://github.com/xxconi/CVE-2026-4782) :  ![starts](https://img.shields.io/github/stars/xxconi/CVE-2026-4782.svg) ![forks](https://img.shields.io/github/forks/xxconi/CVE-2026-4782.svg)


## CVE-2026-3925
 Incorrect security UI in LookalikeChecks in Google Chrome on Android prior to 146.0.7680.71 allowed a remote attacker to perform UI spoofing via a crafted HTML page. (Chromium security severity: Medium)

- [https://github.com/yousif-IQ/CVE-2026-39259](https://github.com/yousif-IQ/CVE-2026-39259) :  ![starts](https://img.shields.io/github/stars/yousif-IQ/CVE-2026-39259.svg) ![forks](https://img.shields.io/github/forks/yousif-IQ/CVE-2026-39259.svg)


## CVE-2026-1657
 The EventPrime plugin for WordPress is vulnerable to unauthorized image file upload in all versions up to, and including, 4.2.8.4. This is due to the plugin registering the upload_file_media AJAX action as publicly accessible (nopriv-enabled) without implementing any authentication, authorization, or nonce verification despite a nonce being created. This makes it possible for unauthenticated attackers to upload image files to the WordPress uploads directory and create Media Library attachments via the ep_upload_file_media endpoint.

- [https://github.com/VimashDilshara/-CVE-2026-1657](https://github.com/VimashDilshara/-CVE-2026-1657) :  ![starts](https://img.shields.io/github/stars/VimashDilshara/-CVE-2026-1657.svg) ![forks](https://img.shields.io/github/forks/VimashDilshara/-CVE-2026-1657.svg)


## CVE-2025-62821
 Microsoft HEIF Image Extensions 1.2.22.0 has an out-of-bounds read because CHEIFItemInfoEntry_GetDataSize can return success while leaving the reported data size as 0. This causes a caller to make a 1-byte allocation. Later, CopyPixels computes copy_size = stride * abs(roi_height) but does not check the source buffer length before a memmove call.

- [https://github.com/hyunjungg/CVE-2025-62821](https://github.com/hyunjungg/CVE-2025-62821) :  ![starts](https://img.shields.io/github/stars/hyunjungg/CVE-2025-62821.svg) ![forks](https://img.shields.io/github/forks/hyunjungg/CVE-2025-62821.svg)


## CVE-2025-39459
 Incorrect Privilege Assignment vulnerability in contempoinc Real Estate 7 realestate-7 allows Privilege Escalation.This issue affects Real Estate 7: from n/a through = 3.5.2.

- [https://github.com/TheBl4ckPh4nt0m/CVE-2025-39459](https://github.com/TheBl4ckPh4nt0m/CVE-2025-39459) :  ![starts](https://img.shields.io/github/stars/TheBl4ckPh4nt0m/CVE-2025-39459.svg) ![forks](https://img.shields.io/github/forks/TheBl4ckPh4nt0m/CVE-2025-39459.svg)


## CVE-2025-21298
 Windows OLE Remote Code Execution Vulnerability

- [https://github.com/TheBl4ckPh4nt0m/CVE-2025-21298](https://github.com/TheBl4ckPh4nt0m/CVE-2025-21298) :  ![starts](https://img.shields.io/github/stars/TheBl4ckPh4nt0m/CVE-2025-21298.svg) ![forks](https://img.shields.io/github/forks/TheBl4ckPh4nt0m/CVE-2025-21298.svg)


## CVE-2025-8110
 Improper Symbolic link handling in the PutContents API in Gogs allows Local Execution of Code.

- [https://github.com/AdityaInnovates/CVE-2025-8110-Gogs-RCE-Exploit](https://github.com/AdityaInnovates/CVE-2025-8110-Gogs-RCE-Exploit) :  ![starts](https://img.shields.io/github/stars/AdityaInnovates/CVE-2025-8110-Gogs-RCE-Exploit.svg) ![forks](https://img.shields.io/github/forks/AdityaInnovates/CVE-2025-8110-Gogs-RCE-Exploit.svg)


## CVE-2025-2304
When a user wishes to change his password, the 'updated_ajax' method of the UsersController is called. The vulnerability stems from the use of the dangerous permit! method, which allows all parameters to pass through without any filtering.

- [https://github.com/0xk4rth1/CVE-2025-2304](https://github.com/0xk4rth1/CVE-2025-2304) :  ![starts](https://img.shields.io/github/stars/0xk4rth1/CVE-2025-2304.svg) ![forks](https://img.shields.io/github/forks/0xk4rth1/CVE-2025-2304.svg)


## CVE-2024-0044
 In createSessionInternal of PackageInstallerService.java, there is a possible run-as any app due to improper input validation. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/TheBl4ckPh4nt0m/CVE-2024-0044](https://github.com/TheBl4ckPh4nt0m/CVE-2024-0044) :  ![starts](https://img.shields.io/github/stars/TheBl4ckPh4nt0m/CVE-2024-0044.svg) ![forks](https://img.shields.io/github/forks/TheBl4ckPh4nt0m/CVE-2024-0044.svg)


## CVE-2023-6019
 A command injection existed in Ray's cpu_profile URL parameter allowing attackers to execute os commands on the system running the ray dashboard remotely without authentication. The issue is fixed in version 2.8.1+. Ray maintainers' response can be found here: https://www.anyscale.com/blog/update-on-ray-cves-cve-2023-6019-cve-2023-6020-cve-2023-6021-cve-2023-48022-cve-2023-48023

- [https://github.com/joaquinrrr/CVE-2023-6019](https://github.com/joaquinrrr/CVE-2023-6019) :  ![starts](https://img.shields.io/github/stars/joaquinrrr/CVE-2023-6019.svg) ![forks](https://img.shields.io/github/forks/joaquinrrr/CVE-2023-6019.svg)


## CVE-2022-0543
 It was discovered, that redis, a persistent key-value database, due to a packaging issue, is prone to a (Debian-specific) Lua sandbox escape, which could result in remote code execution.

- [https://github.com/K3ysTr0K3R/CVE-2022-0543](https://github.com/K3ysTr0K3R/CVE-2022-0543) :  ![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2022-0543.svg) ![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2022-0543.svg)


## CVE-2021-3560
 It was found that polkit could be tricked into bypassing the credential checks for D-Bus requests, elevating the privileges of the requestor to the root user. This flaw could be used by an unprivileged local attacker to, for example, create a new local administrator. The highest threat from this vulnerability is to data confidentiality and integrity as well as system availability.

- [https://github.com/adakoifman/CVE-2021-3560](https://github.com/adakoifman/CVE-2021-3560) :  ![starts](https://img.shields.io/github/stars/adakoifman/CVE-2021-3560.svg) ![forks](https://img.shields.io/github/forks/adakoifman/CVE-2021-3560.svg)


## CVE-2019-9053
 An issue was discovered in CMS Made Simple 2.2.8. It is possible with the News module, through a crafted URL, to achieve unauthenticated blind time-based SQL injection via the m1_idlist parameter.

- [https://github.com/rgkue/mysqli](https://github.com/rgkue/mysqli) :  ![starts](https://img.shields.io/github/stars/rgkue/mysqli.svg) ![forks](https://img.shields.io/github/forks/rgkue/mysqli.svg)


## CVE-2017-20271
 Joomla StreetGuessr Game 1.1.8 contains an SQL injection vulnerability that allows unauthenticated attackers to execute arbitrary SQL queries by injecting malicious code through the catid parameter. Attackers can send GET requests to index.php with the option=com_streetguess&view=maps parameters and inject SQL code in the catid parameter to extract sensitive database information including version and database names.

- [https://github.com/ghhubin/weblogic_cve2017-20271](https://github.com/ghhubin/weblogic_cve2017-20271) :  ![starts](https://img.shields.io/github/stars/ghhubin/weblogic_cve2017-20271.svg) ![forks](https://img.shields.io/github/forks/ghhubin/weblogic_cve2017-20271.svg)

