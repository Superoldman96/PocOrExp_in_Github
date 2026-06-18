# Update 2026-06-18
## CVE-2026-54420
 LiteSpeed cPanel plugin before 2.4.8 (as distributed in LiteSpeed WHM PlugIn before 5.3.2.0) mishandles symlinks provided by a user with FTP or web shell access on a shared hosting server running CloudLinux/CageFS, as exploited in the wild in May 2026.

- [https://github.com/HORKimhab/CVE-2026-54420](https://github.com/HORKimhab/CVE-2026-54420) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-54420.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-54420.svg)
- [https://github.com/Resellnom/litespeed-cpanel-cve-2026-54420-fix](https://github.com/Resellnom/litespeed-cpanel-cve-2026-54420-fix) :  ![starts](https://img.shields.io/github/stars/Resellnom/litespeed-cpanel-cve-2026-54420-fix.svg) ![forks](https://img.shields.io/github/forks/Resellnom/litespeed-cpanel-cve-2026-54420-fix.svg)
- [https://github.com/mahfuzreham/litespeed-cpanel-cve-2026-54420-fix](https://github.com/mahfuzreham/litespeed-cpanel-cve-2026-54420-fix) :  ![starts](https://img.shields.io/github/stars/mahfuzreham/litespeed-cpanel-cve-2026-54420-fix.svg) ![forks](https://img.shields.io/github/forks/mahfuzreham/litespeed-cpanel-cve-2026-54420-fix.svg)


## CVE-2026-50751
 A logic flow weakness in Remote Access and Mobile Access certificate validation in deprecated IKEv1 key exchange allows an unauthenticated remote attacker to bypass user authentication and establish a remote access VPN connection without a valid user password.

- [https://github.com/bolubey/CVE-2026-50751](https://github.com/bolubey/CVE-2026-50751) :  ![starts](https://img.shields.io/github/stars/bolubey/CVE-2026-50751.svg) ![forks](https://img.shields.io/github/forks/bolubey/CVE-2026-50751.svg)


## CVE-2026-49160
 Uncontrolled resource consumption in HTTP/2 allows an unauthorized attacker to deny service over a network.

- [https://github.com/dhmosfunk/CVE-2026-49160-CVE-2026-47291-HTTP.sys](https://github.com/dhmosfunk/CVE-2026-49160-CVE-2026-47291-HTTP.sys) :  ![starts](https://img.shields.io/github/stars/dhmosfunk/CVE-2026-49160-CVE-2026-47291-HTTP.sys.svg) ![forks](https://img.shields.io/github/forks/dhmosfunk/CVE-2026-49160-CVE-2026-47291-HTTP.sys.svg)


## CVE-2026-47291
 Integer overflow or wraparound in Windows HTTP.sys allows an unauthorized attacker to execute code over a network.

- [https://github.com/dhmosfunk/CVE-2026-49160-CVE-2026-47291-HTTP.sys](https://github.com/dhmosfunk/CVE-2026-49160-CVE-2026-47291-HTTP.sys) :  ![starts](https://img.shields.io/github/stars/dhmosfunk/CVE-2026-49160-CVE-2026-47291-HTTP.sys.svg) ![forks](https://img.shields.io/github/forks/dhmosfunk/CVE-2026-49160-CVE-2026-47291-HTTP.sys.svg)


## CVE-2026-47102
 LiteLLM prior to 1.83.10 allows a user to modify their own user_role via the /user/update endpoint. While the endpoint correctly restricts users to updating only their own account, it does not restrict which fields may be changed. A user who can reach this endpoint can set their role to proxy_admin, gaining full administrative access to LiteLLM including all users, teams, keys, models, and prompt history. Users with the org_admin role have legitimate access to this endpoint and can exploit this vulnerability without chaining any additional flaw.

- [https://github.com/HORKimhab/CVE-LiteLLM](https://github.com/HORKimhab/CVE-LiteLLM) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-LiteLLM.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-LiteLLM.svg)


## CVE-2026-47101
 LiteLLM prior to 1.83.14 allows an authenticated internal_user to create API keys with access to routes that their role does not permit. When generating a key, the allowed_routes field is stored without verifying that the specified routes fall within the user's own permissions. A key created with access to admin-only routes can then be used to reach those routes successfully, bypassing the role-based access controls that would otherwise block the request, enabling full privilege escalation from internal_user to proxy_admin.

- [https://github.com/HORKimhab/CVE-LiteLLM](https://github.com/HORKimhab/CVE-LiteLLM) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-LiteLLM.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-LiteLLM.svg)


## CVE-2026-45585
No, if you are using TPM+PIN the vulnerability is not exploitable.

- [https://github.com/Desireeontrial76/yellowkey-bitlocker](https://github.com/Desireeontrial76/yellowkey-bitlocker) :  ![starts](https://img.shields.io/github/stars/Desireeontrial76/yellowkey-bitlocker.svg) ![forks](https://img.shields.io/github/forks/Desireeontrial76/yellowkey-bitlocker.svg)


## CVE-2026-44881
 Portainer Community Edition is a lightweight service delivery platform for containerized applications that can be used to manage Docker, Swarm, Kubernetes and ACI environments. From 2.33.0 to before 2.33.8, 2.39.2, and 2.41.0, Portainer supports deploying stacks from Git repositories. When a Git-backed stack is created or updated, Portainer clones the repository using go-git v5, which translates Git blob entries with mode 0o120000 (symlink) into real OS symlinks on the host filesystem via os.Symlink. The only entry blocked from becoming a symlink is .gitmodules; every other path is created as a symlink without validation. Portainer's GET /api/stacks/{id}/file endpoint then reads the stack entry point with os.ReadFile, which follows OS symlinks transparently. A repository containing docker-compose.yml as a symlink to an arbitrary filesystem path causes the symlink target's contents to be returned verbatim in the HTTP response. Any authenticated user with rights to create or update a Git-backed stack — the default configuration in Portainer CE — can read arbitrary files accessible to the Portainer process. This vulnerability is fixed in 2.33.8, 2.39.2, and 2.41.0.

- [https://github.com/0xdak/CVE-2026-44881_exploit](https://github.com/0xdak/CVE-2026-44881_exploit) :  ![starts](https://img.shields.io/github/stars/0xdak/CVE-2026-44881_exploit.svg) ![forks](https://img.shields.io/github/forks/0xdak/CVE-2026-44881_exploit.svg)


## CVE-2026-41940
 cPanel and WHM versions after 11.40 contain an authentication bypass vulnerability in the login flow that allows unauthenticated remote attackers to gain unauthorized access to the control panel.

- [https://github.com/clsmight/CVE-2026-41940-PoC](https://github.com/clsmight/CVE-2026-41940-PoC) :  ![starts](https://img.shields.io/github/stars/clsmight/CVE-2026-41940-PoC.svg) ![forks](https://img.shields.io/github/forks/clsmight/CVE-2026-41940-PoC.svg)


## CVE-2026-40217
 LiteLLM through 2026-04-08 allows remote attackers to execute arbitrary code via bytecode rewriting at the /guardrails/test_custom_code URI.

- [https://github.com/HORKimhab/CVE-LiteLLM](https://github.com/HORKimhab/CVE-LiteLLM) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-LiteLLM.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-LiteLLM.svg)


## CVE-2026-32488
 Incorrect Privilege Assignment vulnerability in wpeverest User Registration user-registration allows Privilege Escalation.This issue affects User Registration: from n/a through = 4.4.9.

- [https://github.com/webshellseo8/CVE-2026-32488-POC](https://github.com/webshellseo8/CVE-2026-32488-POC) :  ![starts](https://img.shields.io/github/stars/webshellseo8/CVE-2026-32488-POC.svg) ![forks](https://img.shields.io/github/forks/webshellseo8/CVE-2026-32488-POC.svg)


## CVE-2026-31431
AD directly.

- [https://github.com/g1nt0n1x/copy-fail-CVE-2026-31431-shell](https://github.com/g1nt0n1x/copy-fail-CVE-2026-31431-shell) :  ![starts](https://img.shields.io/github/stars/g1nt0n1x/copy-fail-CVE-2026-31431-shell.svg) ![forks](https://img.shields.io/github/forks/g1nt0n1x/copy-fail-CVE-2026-31431-shell.svg)


## CVE-2026-20262
This vulnerability exists because the affected software does not properly validate user-supplied input during a file upload process. An attacker could exploit this vulnerability by sending a crafted HTTP request to an affected API endpoint of the affected system. A successful exploit could allow the attacker to create or overwrite any file on the underlying operating system. This file could later be used to elevate to root. To exploit this vulnerability, the attacker must have valid credentials with at least a lower-privileged, single-task user account.

- [https://github.com/HORKimhab/CVE-2026-20262](https://github.com/HORKimhab/CVE-2026-20262) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-20262.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-20262.svg)


## CVE-2026-9082
This issue affects Drupal core: from 8.9.0 before 10.4.10, from 10.5.0 before 10.5.10, from 10.6.0 before 10.6.9, from 11.0.0 before 11.1.10, from 11.2.0 before 11.2.12, from 11.3.0 before 11.3.10.

- [https://github.com/sourcecode347/CVE-2026-9082-Mass_Scanner](https://github.com/sourcecode347/CVE-2026-9082-Mass_Scanner) :  ![starts](https://img.shields.io/github/stars/sourcecode347/CVE-2026-9082-Mass_Scanner.svg) ![forks](https://img.shields.io/github/forks/sourcecode347/CVE-2026-9082-Mass_Scanner.svg)


## CVE-2026-5516
 IBM WebSphere Application Server - Liberty 22.0.0.11 through 26.0.0.5 IBM WebSphere Application Server Liberty could allow a remote attacker to bypass security under limited conditions by exploiting a specific timing window.

- [https://github.com/KovachVL/CVE-2026-55168](https://github.com/KovachVL/CVE-2026-55168) :  ![starts](https://img.shields.io/github/stars/KovachVL/CVE-2026-55168.svg) ![forks](https://img.shields.io/github/forks/KovachVL/CVE-2026-55168.svg)


## CVE-2026-5468
 A security flaw has been discovered in Casdoor 2.356.0. This affects the function dangerouslySetInnerHTML. Performing a manipulation of the argument formCss/formCssMobile/formSideHtml results in cross site scripting. The attack can be initiated remotely. The exploit has been released to the public and may be used for attacks. The vendor was contacted early about this disclosure but did not respond in any way.

- [https://github.com/87achrafg-stack/CVE-2026-54686](https://github.com/87achrafg-stack/CVE-2026-54686) :  ![starts](https://img.shields.io/github/stars/87achrafg-stack/CVE-2026-54686.svg) ![forks](https://img.shields.io/github/forks/87achrafg-stack/CVE-2026-54686.svg)
- [https://github.com/Saku0512/CVE-2026-54686-poc](https://github.com/Saku0512/CVE-2026-54686-poc) :  ![starts](https://img.shields.io/github/stars/Saku0512/CVE-2026-54686-poc.svg) ![forks](https://img.shields.io/github/forks/Saku0512/CVE-2026-54686-poc.svg)


## CVE-2026-5358
 REJECTED: CVE-2026-5358 is rejected for two reasons. Firstly it has been discovered that no NIS+ client or server was ever released for any Linux-based OS distributions and as such this makes the API provisional and unused.  Secondly it has been discovered that the NIS+ cold start cache (/var/nis/NIS_COLD_START) cannot be bypassed and as such the API can only be called with a trusted server from the pre-populated cache. The use of a trusted server means no trust boundary is crossed and this is therefore considered a normal bug.

- [https://github.com/eev4n/CVE-2026-53582](https://github.com/eev4n/CVE-2026-53582) :  ![starts](https://img.shields.io/github/stars/eev4n/CVE-2026-53582.svg) ![forks](https://img.shields.io/github/forks/eev4n/CVE-2026-53582.svg)


## CVE-2026-4480
substitution character without escaping shell meta characters. A remote attacker could exploit this vulnerability by sending a specially crafted print job description that contains unescaped shell characters. This could lead to remote code execution on the affected system.

- [https://github.com/Vusal777/CVE-2026-4480-exploit-poc](https://github.com/Vusal777/CVE-2026-4480-exploit-poc) :  ![starts](https://img.shields.io/github/stars/Vusal777/CVE-2026-4480-exploit-poc.svg) ![forks](https://img.shields.io/github/forks/Vusal777/CVE-2026-4480-exploit-poc.svg)


## CVE-2026-3994
 A vulnerability was detected in rui314 mold up to 2.40.4. This issue affects the function mold::ObjectFilemold::X86_64::initialize_sections of the file src/input-files.cc of the component Object File Handler. Performing a manipulation results in heap-based buffer overflow. Attacking locally is a requirement. The exploit is now public and may be used. The project was informed of the problem early through an issue report but has not responded yet.

- [https://github.com/lukehebe/CVE-2026-39949](https://github.com/lukehebe/CVE-2026-39949) :  ![starts](https://img.shields.io/github/stars/lukehebe/CVE-2026-39949.svg) ![forks](https://img.shields.io/github/forks/lukehebe/CVE-2026-39949.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-zero-installs](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-zero-installs) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-zero-installs.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-zero-installs.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-tilde](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-tilde) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-tilde.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-tilde.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-resolutions](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-resolutions) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-resolutions.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-yarn-resolutions.svg)


## CVE-2025-49844
 Redis is an open source, in-memory database that persists on disk. Versions 8.2.1 and below allow an authenticated user to use a specially crafted Lua script to manipulate the garbage collector, trigger a use-after-free and potentially lead to remote code execution. The problem exists in all versions of Redis with Lua scripting. This issue is fixed in version 8.2.2. To workaround this issue without patching the redis-server executable is to prevent users from executing Lua scripts. This can be done using ACL to restrict EVAL and EVALSHA commands.

- [https://github.com/cc3305/CVE-2025-49844](https://github.com/cc3305/CVE-2025-49844) :  ![starts](https://img.shields.io/github/stars/cc3305/CVE-2025-49844.svg) ![forks](https://img.shields.io/github/forks/cc3305/CVE-2025-49844.svg)


## CVE-2025-49132
 Pterodactyl is a free, open-source game server management panel. Prior to version 1.11.11, using the /locales/locale.json with the locale and namespace query parameters, a malicious actor is able to execute arbitrary code without being authenticated. With the ability to execute arbitrary code it could be used to gain access to the Panel's server, read credentials from the Panel's config, extract sensitive information from the database, access files of servers managed by the panel, etc. This issue has been patched in version 1.11.11. There are no software workarounds for this vulnerability, but use of an external Web Application Firewall (WAF) could help mitigate this attack.

- [https://github.com/vimmwy/CVE-2025-49132](https://github.com/vimmwy/CVE-2025-49132) :  ![starts](https://img.shields.io/github/stars/vimmwy/CVE-2025-49132.svg) ![forks](https://img.shields.io/github/forks/vimmwy/CVE-2025-49132.svg)


## CVE-2025-30208
 Vite, a provider of frontend development tooling, has a vulnerability in versions prior to 6.2.3, 6.1.2, 6.0.12, 5.4.15, and 4.5.10. `@fs` denies access to files outside of Vite serving allow list. Adding `?raw??` or `?import&raw??` to the URL bypasses this limitation and returns the file content if it exists. This bypass exists because trailing separators such as `?` are removed in several places, but are not accounted for in query string regexes. The contents of arbitrary files can be returned to the browser. Only apps explicitly exposing the Vite dev server to the network (using `--host` or `server.host` config option) are affected. Versions 6.2.3, 6.1.2, 6.0.12, 5.4.15, and 4.5.10 fix the issue.

- [https://github.com/cc3305/CVE-2025-30208](https://github.com/cc3305/CVE-2025-30208) :  ![starts](https://img.shields.io/github/stars/cc3305/CVE-2025-30208.svg) ![forks](https://img.shields.io/github/forks/cc3305/CVE-2025-30208.svg)


## CVE-2025-6639
 The Tutor LMS Pro – eLearning and online course solution plugin for WordPress is vulnerable to Insecure Direct Object Reference in all versions up to, and including, 3.8.3 due to missing validation on a user controlled key when viewing and editing assignments through the tutor_assignment_submit() function. This makes it possible for authenticated attackers, with Subscriber-level access and above, to view and edit assignment submissions of other students.

- [https://github.com/mandeepsohal/CVE-2025-66391](https://github.com/mandeepsohal/CVE-2025-66391) :  ![starts](https://img.shields.io/github/stars/mandeepsohal/CVE-2025-66391.svg) ![forks](https://img.shields.io/github/forks/mandeepsohal/CVE-2025-66391.svg)


## CVE-2024-23897
 Jenkins 2.441 and earlier, LTS 2.426.2 and earlier does not disable a feature of its CLI command parser that replaces an '@' character followed by a file path in an argument with the file's contents, allowing unauthenticated attackers to read arbitrary files on the Jenkins controller file system.

- [https://github.com/rivaedoardo62-boop/cve-2024-23897-jenkins-poc](https://github.com/rivaedoardo62-boop/cve-2024-23897-jenkins-poc) :  ![starts](https://img.shields.io/github/stars/rivaedoardo62-boop/cve-2024-23897-jenkins-poc.svg) ![forks](https://img.shields.io/github/forks/rivaedoardo62-boop/cve-2024-23897-jenkins-poc.svg)


## CVE-2024-20399
Nexus 9000 Series Switches in standalone NX-OS mode

- [https://github.com/HORKimhab/CVE-2024-20399](https://github.com/HORKimhab/CVE-2024-20399) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2024-20399.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2024-20399.svg)


## CVE-2023-34468
You are recommended to upgrade to version 1.22.0 or later which fixes this issue.

- [https://github.com/spikeyjr/CVE-2023-34468-PoC](https://github.com/spikeyjr/CVE-2023-34468-PoC) :  ![starts](https://img.shields.io/github/stars/spikeyjr/CVE-2023-34468-PoC.svg) ![forks](https://img.shields.io/github/forks/spikeyjr/CVE-2023-34468-PoC.svg)


## CVE-2023-28218
 Windows Ancillary Function Driver for WinSock Elevation of Privilege Vulnerability

- [https://github.com/ahiahai242/CVE-2023-28218](https://github.com/ahiahai242/CVE-2023-28218) :  ![starts](https://img.shields.io/github/stars/ahiahai242/CVE-2023-28218.svg) ![forks](https://img.shields.io/github/forks/ahiahai242/CVE-2023-28218.svg)


## CVE-2023-21768
 Windows Ancillary Function Driver for WinSock Elevation of Privilege Vulnerability

- [https://github.com/ahiahai242/CVE-2023-21768](https://github.com/ahiahai242/CVE-2023-21768) :  ![starts](https://img.shields.io/github/stars/ahiahai242/CVE-2023-21768.svg) ![forks](https://img.shields.io/github/forks/ahiahai242/CVE-2023-21768.svg)


## CVE-2023-20938
 In binder_transaction_buffer_release of binder.c, there is a possible use after free due to improper input validation. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android kernelAndroid ID: A-257685302References: Upstream kernel

- [https://github.com/jaf0rk/CVE-2023-20938](https://github.com/jaf0rk/CVE-2023-20938) :  ![starts](https://img.shields.io/github/stars/jaf0rk/CVE-2023-20938.svg) ![forks](https://img.shields.io/github/forks/jaf0rk/CVE-2023-20938.svg)


## CVE-2021-3156
 Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via "sudoedit -s" and a command-line argument that ends with a single backslash character.

- [https://github.com/Kranti08/CVE-2021-3156-Baron-Samedit](https://github.com/Kranti08/CVE-2021-3156-Baron-Samedit) :  ![starts](https://img.shields.io/github/stars/Kranti08/CVE-2021-3156-Baron-Samedit.svg) ![forks](https://img.shields.io/github/forks/Kranti08/CVE-2021-3156-Baron-Samedit.svg)


## CVE-2021-1732
 Windows Win32k Elevation of Privilege Vulnerability

- [https://github.com/Joe1sn/CVE_2021_1732](https://github.com/Joe1sn/CVE_2021_1732) :  ![starts](https://img.shields.io/github/stars/Joe1sn/CVE_2021_1732.svg) ![forks](https://img.shields.io/github/forks/Joe1sn/CVE_2021_1732.svg)


## CVE-2020-7961
 Deserialization of Untrusted Data in Liferay Portal prior to 7.2.1 CE GA2 allows remote attackers to execute arbitrary code via JSON web services (JSONWS).

- [https://github.com/d4ngkh04w/CVE-2020-7961](https://github.com/d4ngkh04w/CVE-2020-7961) :  ![starts](https://img.shields.io/github/stars/d4ngkh04w/CVE-2020-7961.svg) ![forks](https://img.shields.io/github/forks/d4ngkh04w/CVE-2020-7961.svg)


## CVE-2019-16891
 Liferay Portal CE 6.2.5 allows remote command execution because of deserialization of a JSON payload.

- [https://github.com/d4ngkh04w/CVE-2019-16891](https://github.com/d4ngkh04w/CVE-2019-16891) :  ![starts](https://img.shields.io/github/stars/d4ngkh04w/CVE-2019-16891.svg) ![forks](https://img.shields.io/github/forks/d4ngkh04w/CVE-2019-16891.svg)


## CVE-2017-7269
 Buffer overflow in the ScStoragePathFromUrl function in the WebDAV service in Internet Information Services (IIS) 6.0 in Microsoft Windows Server 2003 R2 allows remote attackers to execute arbitrary code via a long header beginning with "If: http://" in a PROPFIND request, as exploited in the wild in July or August 2016.

- [https://github.com/Admin2099/Penetration-Testing-Assessment-23-04-2026](https://github.com/Admin2099/Penetration-Testing-Assessment-23-04-2026) :  ![starts](https://img.shields.io/github/stars/Admin2099/Penetration-Testing-Assessment-23-04-2026.svg) ![forks](https://img.shields.io/github/forks/Admin2099/Penetration-Testing-Assessment-23-04-2026.svg)


## CVE-2015-3306
 The mod_copy module in ProFTPD 1.3.5 allows remote attackers to read and write to arbitrary files via the site cpfr and site cpto commands.

- [https://github.com/xyk0x/cpx_proftpd](https://github.com/xyk0x/cpx_proftpd) :  ![starts](https://img.shields.io/github/stars/xyk0x/cpx_proftpd.svg) ![forks](https://img.shields.io/github/forks/xyk0x/cpx_proftpd.svg)
- [https://github.com/bcononugbor-source/OpenVAS-Vulnerability-Analysis-Incident-Response-Report](https://github.com/bcononugbor-source/OpenVAS-Vulnerability-Analysis-Incident-Response-Report) :  ![starts](https://img.shields.io/github/stars/bcononugbor-source/OpenVAS-Vulnerability-Analysis-Incident-Response-Report.svg) ![forks](https://img.shields.io/github/forks/bcononugbor-source/OpenVAS-Vulnerability-Analysis-Incident-Response-Report.svg)

