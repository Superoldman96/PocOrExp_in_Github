# Update 2026-06-29
## CVE-2026-49417
The /dev/dsp device nodes are world-accessible by default.  On a system with an audio device, either issue allows an unprivileged local user to read and write kernel memory, which can be used to escalate privileges, potentially gaining full control of the affected system.  At a minimum, an attacker can crash the kernel, resulting in a Denial of Service (DoS).

- [https://github.com/Yayoi-cs/CVE-2026-49417_1day_LPE_exploit](https://github.com/Yayoi-cs/CVE-2026-49417_1day_LPE_exploit) :  ![starts](https://img.shields.io/github/stars/Yayoi-cs/CVE-2026-49417_1day_LPE_exploit.svg) ![forks](https://img.shields.io/github/forks/Yayoi-cs/CVE-2026-49417_1day_LPE_exploit.svg)


## CVE-2026-49413
An unprivileged local user can inject a shared library via LD_PRELOAD into a set-user-ID or set-group-ID Linux binary, gaining the privileges of that binary.

- [https://github.com/ii4gsp/CVE-2026-49413](https://github.com/ii4gsp/CVE-2026-49413) :  ![starts](https://img.shields.io/github/stars/ii4gsp/CVE-2026-49413.svg) ![forks](https://img.shields.io/github/forks/ii4gsp/CVE-2026-49413.svg)


## CVE-2026-48907
 A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

- [https://github.com/gh1mau/masta-cve-2026-48907](https://github.com/gh1mau/masta-cve-2026-48907) :  ![starts](https://img.shields.io/github/stars/gh1mau/masta-cve-2026-48907.svg) ![forks](https://img.shields.io/github/forks/gh1mau/masta-cve-2026-48907.svg)
- [https://github.com/grayxploit/CVE-2026-48907](https://github.com/grayxploit/CVE-2026-48907) :  ![starts](https://img.shields.io/github/stars/grayxploit/CVE-2026-48907.svg) ![forks](https://img.shields.io/github/forks/grayxploit/CVE-2026-48907.svg)


## CVE-2026-48020
 Traefik is an HTTP reverse proxy and load balancer. Prior to 2.11.48, 3.6.19, and 3.7.3, there is a high severity vulnerability in Traefik's StripPrefix middleware that allows an unauthenticated attacker to bypass route-level authentication and authorization. When a public router matches on a PathPrefix rule and applies the StripPrefix middleware, a request path containing .. or its percent-encoded form %2e%2e can match the public route at routing time and then, after the prefix is stripped and the path is normalized, resolve to a path served by a separate, authenticated router. As a result, an attacker can reach protected backend paths — such as admin or internal configuration endpoints — without satisfying the authentication middleware attached to the protected router. This vulnerability is fixed in 2.11.48, 3.6.19, and 3.7.3.

- [https://github.com/Hunt-Benito/traefik-stripprefix-auth-bypass-cve-2026-48020-path-normalization](https://github.com/Hunt-Benito/traefik-stripprefix-auth-bypass-cve-2026-48020-path-normalization) :  ![starts](https://img.shields.io/github/stars/Hunt-Benito/traefik-stripprefix-auth-bypass-cve-2026-48020-path-normalization.svg) ![forks](https://img.shields.io/github/forks/Hunt-Benito/traefik-stripprefix-auth-bypass-cve-2026-48020-path-normalization.svg)


## CVE-2026-46331
offset_valid() against INT_MIN, where negation is undefined.

- [https://github.com/douglasmun/pagecache-lpe-containment-kit](https://github.com/douglasmun/pagecache-lpe-containment-kit) :  ![starts](https://img.shields.io/github/stars/douglasmun/pagecache-lpe-containment-kit.svg) ![forks](https://img.shields.io/github/forks/douglasmun/pagecache-lpe-containment-kit.svg)
- [https://github.com/HORKimhab/CVE-2026-46331](https://github.com/HORKimhab/CVE-2026-46331) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-46331.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-46331.svg)


## CVE-2026-45258
The /dev/dsp device nodes are world-accessible by default.  On a system with an audio device, either issue allows an unprivileged local user to read and write kernel memory, which can be used to escalate privileges, potentially gaining full control of the affected system.  At a minimum, an attacker can crash the kernel, resulting in a Denial of Service (DoS).

- [https://github.com/Yayoi-cs/CVE-2026-45258_1day_LPE_exploit](https://github.com/Yayoi-cs/CVE-2026-45258_1day_LPE_exploit) :  ![starts](https://img.shields.io/github/stars/Yayoi-cs/CVE-2026-45258_1day_LPE_exploit.svg) ![forks](https://img.shields.io/github/forks/Yayoi-cs/CVE-2026-45258_1day_LPE_exploit.svg)


## CVE-2026-43503
so segments drawing frags from frag_list members carry the marker.

- [https://github.com/douglasmun/pagecache-lpe-containment-kit](https://github.com/douglasmun/pagecache-lpe-containment-kit) :  ![starts](https://img.shields.io/github/stars/douglasmun/pagecache-lpe-containment-kit.svg) ![forks](https://img.shields.io/github/forks/douglasmun/pagecache-lpe-containment-kit.svg)


## CVE-2026-43499
  	changelog ]

- [https://github.com/MobiusM/CVE-2026-43499](https://github.com/MobiusM/CVE-2026-43499) :  ![starts](https://img.shields.io/github/stars/MobiusM/CVE-2026-43499.svg) ![forks](https://img.shields.io/github/forks/MobiusM/CVE-2026-43499.svg)


## CVE-2026-38751
 OpenSTAManager version 2.10 and earlier contains an arbitrary file upload vulnerability in the module update functionality (modules/aggiornamenti/upload_modules.php)

- [https://github.com/b0ySie7e/OpenSTAManager-RCE-Exploit-CVE-2026-38751](https://github.com/b0ySie7e/OpenSTAManager-RCE-Exploit-CVE-2026-38751) :  ![starts](https://img.shields.io/github/stars/b0ySie7e/OpenSTAManager-RCE-Exploit-CVE-2026-38751.svg) ![forks](https://img.shields.io/github/forks/b0ySie7e/OpenSTAManager-RCE-Exploit-CVE-2026-38751.svg)


## CVE-2026-24061
 telnetd in GNU Inetutils through 2.7 allows remote authentication bypass via a "-f root" value for the USER environment variable.

- [https://github.com/kyukazamiqq/CVE-2026-24061](https://github.com/kyukazamiqq/CVE-2026-24061) :  ![starts](https://img.shields.io/github/stars/kyukazamiqq/CVE-2026-24061.svg) ![forks](https://img.shields.io/github/forks/kyukazamiqq/CVE-2026-24061.svg)
- [https://github.com/Cosm3No1de/htb-orion-writeup](https://github.com/Cosm3No1de/htb-orion-writeup) :  ![starts](https://img.shields.io/github/stars/Cosm3No1de/htb-orion-writeup.svg) ![forks](https://img.shields.io/github/forks/Cosm3No1de/htb-orion-writeup.svg)


## CVE-2026-12432
 The WP Full Stripe Free plugin for WordPress is vulnerable to Missing Authorization in versions up to, and including, 8.4.3 via the wpfs_update_failed_payment_status AJAX action. The handler is registered through both wp_ajax_ and wp_ajax_nopriv_ hooks and the underlying update_failed_payment_status() function performs no capability check, no nonce verification, and no logged-in check before calling $this-db-updatePaymentByEventId() with attacker-controlled POST parameters. This makes it possible for unauthenticated attackers who can obtain a valid Stripe Payment Intent ID for the target site (Payment Intent IDs are exposed to the customer browser during normal Stripe.js checkout flows) to manipulate payment records in the site's database, marking previously successful payments as failed and overwriting failure codes and messages with attacker-supplied values.

- [https://github.com/Polosss/By-Poloss..-..CVE-2026-12432-PoC](https://github.com/Polosss/By-Poloss..-..CVE-2026-12432-PoC) :  ![starts](https://img.shields.io/github/stars/Polosss/By-Poloss..-..CVE-2026-12432-PoC.svg) ![forks](https://img.shields.io/github/forks/Polosss/By-Poloss..-..CVE-2026-12432-PoC.svg)


## CVE-2026-12415
 The Invoice Generator plugin for WordPress is vulnerable to privilege escalation due to a missing capability check on the pravel_invoice_edit_account() AJAX action in versions up to, and including, 1.0.0. The handler is exposed via wp_ajax_nopriv_pravel_invoice_edit_account, accepts an attacker-controlled user_id and user_email from POST data, and calls wp_update_user() without verifying authentication, ownership, or a nonce. This makes it possible for unauthenticated attackers to change the email address of any user, including administrators, and then trigger WordPress's password reset flow to gain access to the targeted account.

- [https://github.com/xxconi/CVE-2026-12415-or-CVE-2026-12416.py](https://github.com/xxconi/CVE-2026-12415-or-CVE-2026-12416.py) :  ![starts](https://img.shields.io/github/stars/xxconi/CVE-2026-12415-or-CVE-2026-12416.py.svg) ![forks](https://img.shields.io/github/forks/xxconi/CVE-2026-12415-or-CVE-2026-12416.py.svg)


## CVE-2026-8461
This issue affects FFmpeg before version 8.1.2.

- [https://github.com/ray-goldman/ffmpeg-jellyfix](https://github.com/ray-goldman/ffmpeg-jellyfix) :  ![starts](https://img.shields.io/github/stars/ray-goldman/ffmpeg-jellyfix.svg) ![forks](https://img.shields.io/github/forks/ray-goldman/ffmpeg-jellyfix.svg)


## CVE-2026-5366
 Prefect version 3.6.23 is vulnerable to remote code execution due to improper handling of user-controlled input in the `GitRepository` storage class. The `commit_sha` parameter, which is passed to git commands, lacks validation and does not include a `--` separator to distinguish user input from git flags. This allows attackers to inject arbitrary git flags, such as `--upload-pack`, enabling execution of external programs. Additionally, the `directories` parameter can be exploited to inject git flags during sparse-checkout operations. These vulnerabilities allow any user with deployment creation permissions to execute arbitrary commands on worker machines, compromising shared work pools in multi-tenant environments.

- [https://github.com/renat0z3r0/prefect-cve-2026-5366](https://github.com/renat0z3r0/prefect-cve-2026-5366) :  ![starts](https://img.shields.io/github/stars/renat0z3r0/prefect-cve-2026-5366.svg) ![forks](https://img.shields.io/github/forks/renat0z3r0/prefect-cve-2026-5366.svg)


## CVE-2026-3683
 A vulnerability was detected in bufanyun HotGo up to 2.0. This issue affects the function ImageTransferStorage of the file /server/internal/logic/common/upload.go of the component Endpoint. The manipulation results in server-side request forgery. The attack may be launched remotely. The exploit is now public and may be used. The vendor was contacted early about this disclosure but did not respond in any way.

- [https://github.com/kpatsakis/CVE-2026-36834](https://github.com/kpatsakis/CVE-2026-36834) :  ![starts](https://img.shields.io/github/stars/kpatsakis/CVE-2026-36834.svg) ![forks](https://img.shields.io/github/forks/kpatsakis/CVE-2026-36834.svg)


## CVE-2026-3462
 The Frisbii Pay plugin for WordPress is vulnerable to unauthorized modification of data due to missing capability checks on the 'upload_csv' and 'process_batch' functions in all versions up to, and including, 1.8.9. This makes it possible for authenticated attackers, with Subscriber-level access and above, to upload arbitrary CSV data and overwrite WooCommerce payment tokens, postmeta, and order meta records.

- [https://github.com/open-flaw/CVE-2026-3462](https://github.com/open-flaw/CVE-2026-3462) :  ![starts](https://img.shields.io/github/stars/open-flaw/CVE-2026-3462.svg) ![forks](https://img.shields.io/github/forks/open-flaw/CVE-2026-3462.svg)


## CVE-2026-0073
 In adbd_tls_verify_cert of auth.cpp, there is a possible bypass of wireless ADB mutual authentication due to a logic error in the code. This could lead to remote (proximal/adjacent) code execution as the shell user with no additional execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/ctnBobong32/CVE-2026-0073-Android-ADBD-bypass-POC_zh_CN](https://github.com/ctnBobong32/CVE-2026-0073-Android-ADBD-bypass-POC_zh_CN) :  ![starts](https://img.shields.io/github/stars/ctnBobong32/CVE-2026-0073-Android-ADBD-bypass-POC_zh_CN.svg) ![forks](https://img.shields.io/github/forks/ctnBobong32/CVE-2026-0073-Android-ADBD-bypass-POC_zh_CN.svg)


## CVE-2025-69212
 OpenSTAManager is an open source management software for technical assistance and invoicing. In 2.9.8 and earlier, a critical OS Command Injection vulnerability exists in the P7M (signed XML) file decoding functionality. An authenticated attacker can upload a ZIP file containing a .p7m file with a malicious filename to execute arbitrary system commands on the server.

- [https://github.com/tohib09/CVE-2025-69212-PoC](https://github.com/tohib09/CVE-2025-69212-PoC) :  ![starts](https://img.shields.io/github/stars/tohib09/CVE-2025-69212-PoC.svg) ![forks](https://img.shields.io/github/forks/tohib09/CVE-2025-69212-PoC.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-overrides](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-overrides) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-overrides.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-overrides.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive.svg)


## CVE-2025-32432
 Craft is a flexible, user-friendly CMS for creating custom digital experiences on the web and beyond. Starting from version 3.0.0-RC1 to before 3.9.15, 4.0.0-RC1 to before 4.14.15, and 5.0.0-RC1 to before 5.6.17, Craft is vulnerable to remote code execution. This is a high-impact, low-complexity attack vector. This issue has been patched in versions 3.9.15, 4.14.15, and 5.6.17, and is an additional fix for CVE-2023-41892.

- [https://github.com/Cosm3No1de/htb-orion-writeup](https://github.com/Cosm3No1de/htb-orion-writeup) :  ![starts](https://img.shields.io/github/stars/Cosm3No1de/htb-orion-writeup.svg) ![forks](https://img.shields.io/github/forks/Cosm3No1de/htb-orion-writeup.svg)


## CVE-2024-0044
 In createSessionInternal of PackageInstallerService.java, there is a possible run-as any app due to improper input validation. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/k4ran909/cve_2024_0044](https://github.com/k4ran909/cve_2024_0044) :  ![starts](https://img.shields.io/github/stars/k4ran909/cve_2024_0044.svg) ![forks](https://img.shields.io/github/forks/k4ran909/cve_2024_0044.svg)


## CVE-2020-0796
 A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 3.1.1 (SMBv3) protocol handles certain requests, aka 'Windows SMBv3 Client/Server Remote Code Execution Vulnerability'.

- [https://github.com/nyambiblaise/Microsoft-Windows-SMBGhost-Vulnerability-Checker---CVE-2020-0796---SMBv3-RCE](https://github.com/nyambiblaise/Microsoft-Windows-SMBGhost-Vulnerability-Checker---CVE-2020-0796---SMBv3-RCE) :  ![starts](https://img.shields.io/github/stars/nyambiblaise/Microsoft-Windows-SMBGhost-Vulnerability-Checker---CVE-2020-0796---SMBv3-RCE.svg) ![forks](https://img.shields.io/github/forks/nyambiblaise/Microsoft-Windows-SMBGhost-Vulnerability-Checker---CVE-2020-0796---SMBv3-RCE.svg)


## CVE-2014-3566
 The SSL protocol 3.0, as used in OpenSSL through 1.0.1i and other products, uses nondeterministic CBC padding, which makes it easier for man-in-the-middle attackers to obtain cleartext data via a padding-oracle attack, aka the "POODLE" issue.

- [https://github.com/Karma4488/CVE-2014-3566](https://github.com/Karma4488/CVE-2014-3566) :  ![starts](https://img.shields.io/github/stars/Karma4488/CVE-2014-3566.svg) ![forks](https://img.shields.io/github/forks/Karma4488/CVE-2014-3566.svg)

