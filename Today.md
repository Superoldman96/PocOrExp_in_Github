# Update 2026-06-26
## CVE-2026-56111
 Marlin Firmware through 2.1.2.7, fixed in commit 1f255d1, when built with MESH_BED_LEVELING enabled, contains an out-of-bounds write vulnerability in the M421 G-code handler that allows attackers to corrupt firmware memory by supplying out-of-range X and Y grid indices. Attackers can send a single crafted G-code command via USB serial, network interface, or malicious gcode file to write an attacker-controlled 32-bit float value past the z_values array bounds, corrupting adjacent firmware variables and causing denial of service or firmware state corruption.

- [https://github.com/Christbowel/CVE-2026-56111](https://github.com/Christbowel/CVE-2026-56111) :  ![starts](https://img.shields.io/github/stars/Christbowel/CVE-2026-56111.svg) ![forks](https://img.shields.io/github/forks/Christbowel/CVE-2026-56111.svg)


## CVE-2026-54686
 Warp is an agentic development environment. From 0.2021.04.25.23.05.stable_00 until 0.2026.05.06.15.42.stable_01, Warp accepted certain state-mutating terminal lifecycle hooks from the PTY stream without verifying that the hooks were emitted by Warp's shell integration for the active session. An attacker who could cause a victim to view attacker-controlled terminal output in Warp could spoof selected lifecycle metadata, including the current working directory reported for the active block or SSH session transport metadata. This vulnerability is fixed in 0.2026.05.06.15.42.stable_01.

- [https://github.com/Saku0512/CVE-2026-54686-poc](https://github.com/Saku0512/CVE-2026-54686-poc) :  ![starts](https://img.shields.io/github/stars/Saku0512/CVE-2026-54686-poc.svg) ![forks](https://img.shields.io/github/forks/Saku0512/CVE-2026-54686-poc.svg)


## CVE-2026-52943
closely and avoiding the need for a balancing net_zcopy_put().

- [https://github.com/vn-lazyming/CVE-2026-52943](https://github.com/vn-lazyming/CVE-2026-52943) :  ![starts](https://img.shields.io/github/stars/vn-lazyming/CVE-2026-52943.svg) ![forks](https://img.shields.io/github/forks/vn-lazyming/CVE-2026-52943.svg)


## CVE-2026-49777
This issue affects Product Slider Pro for WooCommerce: from n/a before 3.5.4.

- [https://github.com/HORKimhab/CVE-Wordpress](https://github.com/HORKimhab/CVE-Wordpress) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-Wordpress.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-Wordpress.svg)


## CVE-2026-48908
 A vulnerability in SP Page Builder for Joomla allows unauthenticated users to upload arbitrary files, ultimately resulting in the upload and execution of PHP code.

- [https://github.com/0xBlackash/CVE-2026-48908](https://github.com/0xBlackash/CVE-2026-48908) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-48908.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-48908.svg)
- [https://github.com/ogenich/CVE-2026-48908](https://github.com/ogenich/CVE-2026-48908) :  ![starts](https://img.shields.io/github/stars/ogenich/CVE-2026-48908.svg) ![forks](https://img.shields.io/github/forks/ogenich/CVE-2026-48908.svg)
- [https://github.com/gagaltotal/CVE-2026-48908-SP-Page-Builder-Joomla](https://github.com/gagaltotal/CVE-2026-48908-SP-Page-Builder-Joomla) :  ![starts](https://img.shields.io/github/stars/gagaltotal/CVE-2026-48908-SP-Page-Builder-Joomla.svg) ![forks](https://img.shields.io/github/forks/gagaltotal/CVE-2026-48908-SP-Page-Builder-Joomla.svg)


## CVE-2026-48732
 Warp is an agentic development environment. From 0.2023.03.21.08.02.stable_00 until 0.2026.05.06.15.42.stable_01, Warp contains a command injection issue in the legacy SSH background command path. Warp used the remote working directory reported by the session when building helper commands for SSH-backed metadata collection. A remote host, repository, or directory name controlled by an attacker could cause that helper command to execute additional shell syntax on the remote host as the victim's authenticated SSH account. This vulnerability is fixed in 0.2026.05.06.15.42.stable_01.

- [https://github.com/Saku0512/CVE-2026-48732-poc](https://github.com/Saku0512/CVE-2026-48732-poc) :  ![starts](https://img.shields.io/github/stars/Saku0512/CVE-2026-48732-poc.svg) ![forks](https://img.shields.io/github/forks/Saku0512/CVE-2026-48732-poc.svg)


## CVE-2026-45504
 Server-side request forgery (ssrf) in Microsoft Exchange Server allows an authorized attacker to elevate privileges over a network.

- [https://github.com/hawktrace/CVE-2026-45504](https://github.com/hawktrace/CVE-2026-45504) :  ![starts](https://img.shields.io/github/stars/hawktrace/CVE-2026-45504.svg) ![forks](https://img.shields.io/github/forks/hawktrace/CVE-2026-45504.svg)


## CVE-2026-38526
 An authenticated arbitrary file upload vulnerability in the /admin/tinymce/upload endpoint of Webkul Krayin CRM v2.2.x allows attackers to execute arbitrary code via uploading a crafted PHP file.

- [https://github.com/pawpic/CVE-2026-38526-POC](https://github.com/pawpic/CVE-2026-38526-POC) :  ![starts](https://img.shields.io/github/stars/pawpic/CVE-2026-38526-POC.svg) ![forks](https://img.shields.io/github/forks/pawpic/CVE-2026-38526-POC.svg)


## CVE-2026-29145
Users are recommended to upgrade to version Tomcat Native 1.3.7 or 2.0.14 and Tomcat 11.0.20, 10.1.53 and 9.0.116, which fix the issue.

- [https://github.com/sancliffe/CVE-2026-29145-Tester](https://github.com/sancliffe/CVE-2026-29145-Tester) :  ![starts](https://img.shields.io/github/stars/sancliffe/CVE-2026-29145-Tester.svg) ![forks](https://img.shields.io/github/forks/sancliffe/CVE-2026-29145-Tester.svg)


## CVE-2026-12417
 The SignUp & SignIn plugin for WordPress is vulnerable to Authentication Bypass via Weak Password Reset Validation leading to Account Takeover in versions up to, and including, 1.0.0. This is due to the `pravel_change_password()` AJAX handler — registered via `wp_ajax_nopriv_pravel_change_password` and therefore accessible to unauthenticated users — performing no nonce verification, no capability check, and only a loose equality check between an attacker-supplied `reset_activation_code` POST parameter and the target user's `forgot_email` user meta value; when a user has never initiated a password reset, `get_user_meta()` returns an empty string that trivially satisfies this check against an omitted or empty attacker-supplied code. This makes it possible for unauthenticated attackers to change the password of any WordPress user, including administrators, by sending a crafted POST request to `admin-ajax.php` with `action=pravel_change_password`, `reset_user_id` set to the target account's user ID, and `new_password_custom` set to an attacker-chosen password. Successful exploitation allows the attacker to authenticate with the newly set password and fully take over the targeted account, achieving administrator-level privilege escalation on the affected site.

- [https://github.com/Nxploited/CVE-2026-12416-CVE-2026-12417](https://github.com/Nxploited/CVE-2026-12416-CVE-2026-12417) :  ![starts](https://img.shields.io/github/stars/Nxploited/CVE-2026-12416-CVE-2026-12417.svg) ![forks](https://img.shields.io/github/forks/Nxploited/CVE-2026-12416-CVE-2026-12417.svg)


## CVE-2026-12416
 The Invoice Generator plugin for WordPress is vulnerable to Account Takeover via Password Reset in all versions up to, and including, 1.0.0. This is due to the `pravel_invoice_change_password()` function being registered as a nopriv AJAX handler with no nonce verification and no authorization check, and performing a loose equality comparison between the supplied `reset_activation_code` POST parameter and the target user's stored `forgot_email` user meta — a check that trivially evaluates to true (`'' == ''`) for any user who has never initiated a forgot-password request, which applies to administrators under normal conditions. This makes it possible for unauthenticated attackers to supply an arbitrary user ID via the `reset_user_id` POST parameter, bypass the activation code check entirely by omitting `reset_activation_code`, and set the target account's password to an attacker-chosen value, enabling full takeover of any account on the site, including administrator accounts.

- [https://github.com/Nxploited/CVE-2026-12416-CVE-2026-12417](https://github.com/Nxploited/CVE-2026-12416-CVE-2026-12417) :  ![starts](https://img.shields.io/github/stars/Nxploited/CVE-2026-12416-CVE-2026-12417.svg) ![forks](https://img.shields.io/github/forks/Nxploited/CVE-2026-12416-CVE-2026-12417.svg)


## CVE-2026-10735
 Multiple Shapedsmart-post-show-pro WordPress plugin before 4.0.2, Real Testimonials Pro WordPress plugin before 3.2.5, Product Slider for WooCommerce Pro WordPress plugin before 3.5.3 Pro smart-post-show-pro WordPress plugin before 4.0.2, Real Testimonials Pro WordPress plugin before 3.2.5, Product Slider for WooCommerce Pro WordPress plugin before 3.5.3 were distributed with malicious code through the vendor's compromised update server, allowing unauthenticated attackers to deploy a second-stage payload that exfiltrates credentials and other sensitive data and grants full control of affected sites.

- [https://github.com/HORKimhab/CVE-Wordpress](https://github.com/HORKimhab/CVE-Wordpress) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-Wordpress.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-Wordpress.svg)
- [https://github.com/xxconi/CVE-2026-49777-CVE-2026-10735](https://github.com/xxconi/CVE-2026-49777-CVE-2026-10735) :  ![starts](https://img.shields.io/github/stars/xxconi/CVE-2026-49777-CVE-2026-10735.svg) ![forks](https://img.shields.io/github/forks/xxconi/CVE-2026-49777-CVE-2026-10735.svg)


## CVE-2026-8461
This issue affects FFmpeg before version 8.1.2.

- [https://github.com/Y5neKO/CVE-2026-8461-EXP](https://github.com/Y5neKO/CVE-2026-8461-EXP) :  ![starts](https://img.shields.io/github/stars/Y5neKO/CVE-2026-8461-EXP.svg) ![forks](https://img.shields.io/github/forks/Y5neKO/CVE-2026-8461-EXP.svg)
- [https://github.com/HORKimhab/CVE-2026-8461](https://github.com/HORKimhab/CVE-2026-8461) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-8461.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-8461.svg)


## CVE-2026-6992
 A vulnerability was identified in Linksys MR9600 2.0.6.206937. This affects the function BTRequestGetSmartConnectStatus of the file /etc/init.d/run_central2.sh of the component JNAP Action Handler. The manipulation of the argument pin leads to os command injection. The attack may be initiated remotely. The exploit is publicly available and might be used. The vendor was contacted early about this disclosure but did not respond in any way.

- [https://github.com/nicholas-howland/CVE-2026-6992-PoC](https://github.com/nicholas-howland/CVE-2026-6992-PoC) :  ![starts](https://img.shields.io/github/stars/nicholas-howland/CVE-2026-6992-PoC.svg) ![forks](https://img.shields.io/github/forks/nicholas-howland/CVE-2026-6992-PoC.svg)


## CVE-2026-3652
 The ARForms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the `value` parameter of the `arf_save_incomplete_form_data` AJAX action in all versions up to, and including, 7.1.3 due to insufficient input sanitization and output escaping. This makes it possible for unauthenticated attackers to inject arbitrary web scripts that will execute whenever an administrator views the "Partial Filled Form Entries" page in the ARForms dashboard.

- [https://github.com/deepwoodssec/CVE-2026-36522](https://github.com/deepwoodssec/CVE-2026-36522) :  ![starts](https://img.shields.io/github/stars/deepwoodssec/CVE-2026-36522.svg) ![forks](https://img.shields.io/github/forks/deepwoodssec/CVE-2026-36522.svg)


## CVE-2025-68645
 A Local File Inclusion (LFI) vulnerability exists in the Webmail Classic UI of Zimbra Collaboration (ZCS) 10.0 and 10.1 because of improper handling of user-supplied request parameters in the RestFilter servlet. An unauthenticated remote attacker can craft requests to the /h/rest endpoint to influence internal request dispatching, allowing inclusion of arbitrary files from the WebRoot directory.

- [https://github.com/Crow5-oss/CVE-2025-68645](https://github.com/Crow5-oss/CVE-2025-68645) :  ![starts](https://img.shields.io/github/stars/Crow5-oss/CVE-2025-68645.svg) ![forks](https://img.shields.io/github/forks/Crow5-oss/CVE-2025-68645.svg)


## CVE-2025-64446
 A relative path traversal vulnerability in Fortinet FortiWeb 8.0.0 through 8.0.1, FortiWeb 7.6.0 through 7.6.4, FortiWeb 7.4.0 through 7.4.9, FortiWeb 7.2.0 through 7.2.11, FortiWeb 7.0.0 through 7.0.11 may allow an attacker to execute administrative commands on the system via crafted HTTP or HTTPS requests.

- [https://github.com/litndat/Vulnerability-CVE-2025-64446-CVE-2025-58034](https://github.com/litndat/Vulnerability-CVE-2025-64446-CVE-2025-58034) :  ![starts](https://img.shields.io/github/stars/litndat/Vulnerability-CVE-2025-64446-CVE-2025-58034.svg) ![forks](https://img.shields.io/github/forks/litndat/Vulnerability-CVE-2025-64446-CVE-2025-58034.svg)


## CVE-2025-58034
 An Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability [CWE-78] vulnerability in Fortinet FortiWeb 8.0.0 through 8.0.1, FortiWeb 7.6.0 through 7.6.5, FortiWeb 7.4.0 through 7.4.10, FortiWeb 7.2.0 through 7.2.11, FortiWeb 7.0.0 through 7.0.11 may allow an authenticated attacker to execute unauthorized code on the underlying system via crafted HTTP requests or CLI commands.

- [https://github.com/litndat/Vulnerability-CVE-2025-64446-CVE-2025-58034](https://github.com/litndat/Vulnerability-CVE-2025-64446-CVE-2025-58034) :  ![starts](https://img.shields.io/github/stars/litndat/Vulnerability-CVE-2025-64446-CVE-2025-58034.svg) ![forks](https://img.shields.io/github/forks/litndat/Vulnerability-CVE-2025-64446-CVE-2025-58034.svg)


## CVE-2025-57819
 FreePBX is an open-source web-based graphical user interface. FreePBX 15, 16, and 17 endpoints are vulnerable due to insufficiently sanitized user-supplied data allowing unauthenticated access to FreePBX Administrator leading to arbitrary database manipulation and remote code execution. This issue has been patched in endpoint versions 15.0.66, 16.0.89, and 17.0.3.

- [https://github.com/JazzTheRabbit/FreePBX-SQLi-RCE](https://github.com/JazzTheRabbit/FreePBX-SQLi-RCE) :  ![starts](https://img.shields.io/github/stars/JazzTheRabbit/FreePBX-SQLi-RCE.svg) ![forks](https://img.shields.io/github/forks/JazzTheRabbit/FreePBX-SQLi-RCE.svg)


## CVE-2025-55182
 A pre-authentication remote code execution vulnerability exists in React Server Components versions 19.0.0, 19.1.0, 19.1.1, and 19.2.0 including the following packages: react-server-dom-parcel, react-server-dom-turbopack, and react-server-dom-webpack. The vulnerable code unsafely deserializes payloads from HTTP requests to Server Function endpoints.

- [https://github.com/pkrasulia/CVE-2025-55182-NextJS-RCE-PoC](https://github.com/pkrasulia/CVE-2025-55182-NextJS-RCE-PoC) :  ![starts](https://img.shields.io/github/stars/pkrasulia/CVE-2025-55182-NextJS-RCE-PoC.svg) ![forks](https://img.shields.io/github/forks/pkrasulia/CVE-2025-55182-NextJS-RCE-PoC.svg)


## CVE-2025-32432
 Craft is a flexible, user-friendly CMS for creating custom digital experiences on the web and beyond. Starting from version 3.0.0-RC1 to before 3.9.15, 4.0.0-RC1 to before 4.14.15, and 5.0.0-RC1 to before 5.6.17, Craft is vulnerable to remote code execution. This is a high-impact, low-complexity attack vector. This issue has been patched in versions 3.9.15, 4.14.15, and 5.6.17, and is an additional fix for CVE-2023-41892.

- [https://github.com/n40y/PoC_CVE-2025-32432](https://github.com/n40y/PoC_CVE-2025-32432) :  ![starts](https://img.shields.io/github/stars/n40y/PoC_CVE-2025-32432.svg) ![forks](https://img.shields.io/github/forks/n40y/PoC_CVE-2025-32432.svg)


## CVE-2025-29927
 Next.js is a React framework for building full-stack web applications. Starting in version 1.11.4 and prior to versions 12.3.5, 13.5.9, 14.2.25, and 15.2.3, it is possible to bypass authorization checks within a Next.js application, if the authorization check occurs in middleware. If patching to a safe version is infeasible, it is recommend that you prevent external user requests which contain the x-middleware-subrequest header from reaching your Next.js application. This vulnerability is fixed in 12.3.5, 13.5.9, 14.2.25, and 15.2.3.

- [https://github.com/0rd1na1/CVE-2025-29927-Research](https://github.com/0rd1na1/CVE-2025-29927-Research) :  ![starts](https://img.shields.io/github/stars/0rd1na1/CVE-2025-29927-Research.svg) ![forks](https://img.shields.io/github/forks/0rd1na1/CVE-2025-29927-Research.svg)


## CVE-2024-21762
 A out-of-bounds write in Fortinet FortiOS versions 7.4.0 through 7.4.2, 7.2.0 through 7.2.6, 7.0.0 through 7.0.13, 6.4.0 through 6.4.14, 6.2.0 through 6.2.15, 6.0.0 through 6.0.17, FortiProxy versions 7.4.0 through 7.4.2, 7.2.0 through 7.2.8, 7.0.0 through 7.0.14, 2.0.0 through 2.0.13, 1.2.0 through 1.2.13, 1.1.0 through 1.1.6, 1.0.0 through 1.0.7 allows attacker to execute unauthorized code or commands via specifically crafted requests

- [https://github.com/Sxmpl3/CVE-2024-21762-Safe-Check](https://github.com/Sxmpl3/CVE-2024-21762-Safe-Check) :  ![starts](https://img.shields.io/github/stars/Sxmpl3/CVE-2024-21762-Safe-Check.svg) ![forks](https://img.shields.io/github/forks/Sxmpl3/CVE-2024-21762-Safe-Check.svg)


## CVE-2024-0670
 Privilege escalation in windows agent plugin in Checkmk before 2.2.0p23, 2.1.0p40 and 2.0.0 (EOL) allows local user to escalate privileges

- [https://github.com/dfdxarjy/HTB-NanoCorp-CVE-2024-0670](https://github.com/dfdxarjy/HTB-NanoCorp-CVE-2024-0670) :  ![starts](https://img.shields.io/github/stars/dfdxarjy/HTB-NanoCorp-CVE-2024-0670.svg) ![forks](https://img.shields.io/github/forks/dfdxarjy/HTB-NanoCorp-CVE-2024-0670.svg)


## CVE-2023-20198
 Cisco is providing an update for the ongoing investigation into observed exploitation of the web UI feature in Cisco IOS XE Software. We are updating the list of fixed releases and adding the Software Checker. Our investigation has determined that the actors exploited two previously unknown issues. The attacker first exploited CVE-2023-20198 to gain initial access and issued a privilege 15 command to create a local user and password combination. This allowed the user to log in with normal user access. The attacker then exploited another component of the web UI feature, leveraging the new local user to elevate privilege to root and write the implant to the file system. Cisco has assigned CVE-2023-20273 to this issue. CVE-2023-20198 has been assigned a CVSS Score of 10.0. CVE-2023-20273 has been assigned a CVSS Score of 7.2. Both of these CVEs are being tracked by CSCwh87343.

- [https://github.com/charlesjson/CVE-2023-20198](https://github.com/charlesjson/CVE-2023-20198) :  ![starts](https://img.shields.io/github/stars/charlesjson/CVE-2023-20198.svg) ![forks](https://img.shields.io/github/forks/charlesjson/CVE-2023-20198.svg)


## CVE-2022-39299
 Passport-SAML is a SAML 2.0 authentication provider for Passport, the Node.js authentication library. A remote attacker may be able to bypass SAML authentication on a website using passport-saml. A successful attack requires that the attacker is in possession of an arbitrary IDP signed XML element. Depending on the IDP used, fully unauthenticated attacks (e.g without access to a valid user) might also be feasible if generation of a signed message can be triggered. Users should upgrade to passport-saml version 3.2.2 or newer. The issue was also present in the beta releases of `node-saml` before version 4.0.0-beta.5. If you cannot upgrade, disabling SAML authentication may be done as a workaround.

- [https://github.com/0rd1na1/CVE-2022-39299-Research](https://github.com/0rd1na1/CVE-2022-39299-Research) :  ![starts](https://img.shields.io/github/stars/0rd1na1/CVE-2022-39299-Research.svg) ![forks](https://img.shields.io/github/forks/0rd1na1/CVE-2022-39299-Research.svg)


## CVE-2022-37706
 enlightenment_sys in Enlightenment before 0.25.4 allows local users to gain privileges because it is setuid root, and the system library function mishandles pathnames that begin with a /dev/.. substring.

- [https://github.com/Massive43/CVE-2022-37706](https://github.com/Massive43/CVE-2022-37706) :  ![starts](https://img.shields.io/github/stars/Massive43/CVE-2022-37706.svg) ![forks](https://img.shields.io/github/forks/Massive43/CVE-2022-37706.svg)


## CVE-2022-29078
 The ejs (aka Embedded JavaScript templates) package 3.1.6 for Node.js allows server-side template injection in settings[view options][outputFunctionName]. This is parsed as an internal option, and overwrites the outputFunctionName option with an arbitrary OS command (which is executed upon template compilation).

- [https://github.com/test-avm-714877d2df585126/C-test-2](https://github.com/test-avm-714877d2df585126/C-test-2) :  ![starts](https://img.shields.io/github/stars/test-avm-714877d2df585126/C-test-2.svg) ![forks](https://img.shields.io/github/forks/test-avm-714877d2df585126/C-test-2.svg)
- [https://github.com/test-avm-714877d2df585126/vuln-ejs-critical](https://github.com/test-avm-714877d2df585126/vuln-ejs-critical) :  ![starts](https://img.shields.io/github/stars/test-avm-714877d2df585126/vuln-ejs-critical.svg) ![forks](https://img.shields.io/github/forks/test-avm-714877d2df585126/vuln-ejs-critical.svg)


## CVE-2022-0847
 A flaw was found in the way the "flags" member of the new pipe buffer structure was lacking proper initialization in copy_page_to_iter_pipe and push_pipe functions in the Linux kernel and could thus contain stale values. An unprivileged local user could use this flaw to write to pages in the page cache backed by read only files and as such escalate their privileges on the system.

- [https://github.com/AyoubNajim/cve-2022-0847dirtypipe-exploit](https://github.com/AyoubNajim/cve-2022-0847dirtypipe-exploit) :  ![starts](https://img.shields.io/github/stars/AyoubNajim/cve-2022-0847dirtypipe-exploit.svg) ![forks](https://img.shields.io/github/forks/AyoubNajim/cve-2022-0847dirtypipe-exploit.svg)


## CVE-2021-33044
 The identity authentication bypass vulnerability found in some Dahua products during the login process. Attackers can bypass device identity authentication by constructing malicious data packets.

- [https://github.com/litndat/Camera-Dahua-Research-l-h-ng-CVE-2021-33044](https://github.com/litndat/Camera-Dahua-Research-l-h-ng-CVE-2021-33044) :  ![starts](https://img.shields.io/github/stars/litndat/Camera-Dahua-Research-l-h-ng-CVE-2021-33044.svg) ![forks](https://img.shields.io/github/forks/litndat/Camera-Dahua-Research-l-h-ng-CVE-2021-33044.svg)


## CVE-2021-30327
 Buffer overflow in sahara protocol while processing commands leads to overwrite of secure configuration data in Snapdragon Mobile, Snapdragon Compute, Snapdragon Auto, Snapdragon IOT, Snapdragon Connectivity, Snapdragon Voice & Music

- [https://github.com/Daniel224455/katana](https://github.com/Daniel224455/katana) :  ![starts](https://img.shields.io/github/stars/Daniel224455/katana.svg) ![forks](https://img.shields.io/github/forks/Daniel224455/katana.svg)


## CVE-2021-29441
 Nacos is a platform designed for dynamic service discovery and configuration and service management. In Nacos before version 1.4.1, when configured to use authentication (-Dnacos.core.auth.enabled=true) Nacos uses the AuthFilter servlet filter to enforce authentication. This filter has a backdoor that enables Nacos servers to bypass this filter and therefore skip authentication checks. This mechanism relies on the user-agent HTTP header so it can be easily spoofed. This issue may allow any user to carry out any administrative tasks on the Nacos server.

- [https://github.com/K3ysTr0K3R/CVE-2021-29441](https://github.com/K3ysTr0K3R/CVE-2021-29441) :  ![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2021-29441.svg) ![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2021-29441.svg)


## CVE-2021-22205
 An issue has been discovered in GitLab CE/EE affecting all versions starting from 11.9. GitLab was not properly validating image files that were passed to a file parser which resulted in a remote command execution.

- [https://github.com/K3ysTr0K3R/CVE-2021-22205](https://github.com/K3ysTr0K3R/CVE-2021-22205) :  ![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2021-22205.svg) ![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2021-22205.svg)


## CVE-2020-24186
 A Remote Code Execution vulnerability exists in the gVectors wpDiscuz plugin 7.0 through 7.0.4 for WordPress, which allows unauthenticated users to upload any type of file, including PHP files via the wmuUploadFiles AJAX action.

- [https://github.com/wvverez/CVE-2020-24186](https://github.com/wvverez/CVE-2020-24186) :  ![starts](https://img.shields.io/github/stars/wvverez/CVE-2020-24186.svg) ![forks](https://img.shields.io/github/forks/wvverez/CVE-2020-24186.svg)


## CVE-2020-8636
 An issue was discovered in OpServices OpMon 9.3.2 that allows Remote Code Execution .

- [https://github.com/phor3nsic/opmonster](https://github.com/phor3nsic/opmonster) :  ![starts](https://img.shields.io/github/stars/phor3nsic/opmonster.svg) ![forks](https://img.shields.io/github/forks/phor3nsic/opmonster.svg)


## CVE-2019-9053
 An issue was discovered in CMS Made Simple 2.2.8. It is possible with the News module, through a crafted URL, to achieve unauthenticated blind time-based SQL injection via the m1_idlist parameter.

- [https://github.com/Vedantrana73/cve-2019-9053-py3](https://github.com/Vedantrana73/cve-2019-9053-py3) :  ![starts](https://img.shields.io/github/stars/Vedantrana73/cve-2019-9053-py3.svg) ![forks](https://img.shields.io/github/forks/Vedantrana73/cve-2019-9053-py3.svg)


## CVE-2017-11882
 Microsoft Office 2007 Service Pack 3, Microsoft Office 2010 Service Pack 2, Microsoft Office 2013 Service Pack 1, and Microsoft Office 2016 allow an attacker to run arbitrary code in the context of the current user by failing to properly handle objects in memory, aka "Microsoft Office Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11884.

- [https://github.com/Mo200909/Office-Malware-Forensics-Lab-REMnux-Static-Analysis](https://github.com/Mo200909/Office-Malware-Forensics-Lab-REMnux-Static-Analysis) :  ![starts](https://img.shields.io/github/stars/Mo200909/Office-Malware-Forensics-Lab-REMnux-Static-Analysis.svg) ![forks](https://img.shields.io/github/forks/Mo200909/Office-Malware-Forensics-Lab-REMnux-Static-Analysis.svg)


## CVE-2016-5195
 Race condition in mm/gup.c in the Linux kernel 2.x through 4.x before 4.8.3 allows local users to gain privileges by leveraging incorrect handling of a copy-on-write (COW) feature to write to a read-only memory mapping, as exploited in the wild in October 2016, aka "Dirty COW."

- [https://github.com/GonzaBot/kernel-exploit-dirtycow](https://github.com/GonzaBot/kernel-exploit-dirtycow) :  ![starts](https://img.shields.io/github/stars/GonzaBot/kernel-exploit-dirtycow.svg) ![forks](https://img.shields.io/github/forks/GonzaBot/kernel-exploit-dirtycow.svg)

