# Update 2026-06-19
## CVE-2026-49952
 Discuz! X5.0 releases 20260320 through 20260501 contains an authentication bypass vulnerability that allows unauthenticated remote attackers to gain unauthorized access to database backup and restore functionality by exploiting a shared cryptographic key between UCenter integration and the database backup API exposed by dbbak.php. Attackers can inject a crafted payload through the username parameter during login to abuse the encryption oracle in logging_ctl::logging_more(), obtain a legitimately signed token, and use it to bypass authorization for database export and import operations, with the additional ability to trigger a race condition to impersonate arbitrary users.

- [https://github.com/passwa11/CVE-2026-49952](https://github.com/passwa11/CVE-2026-49952) :  ![starts](https://img.shields.io/github/stars/passwa11/CVE-2026-49952.svg) ![forks](https://img.shields.io/github/forks/passwa11/CVE-2026-49952.svg)


## CVE-2026-49105
 Unauthenticated PHP Object Injection in WP Zendesk for Contact Form 7, WPForms, Elementor, Formidable and Ninja Forms = 1.1.4 versions.

- [https://github.com/izxci/CVE-2026-49105](https://github.com/izxci/CVE-2026-49105) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-49105.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-49105.svg)


## CVE-2026-49104
 Unauthenticated PHP Object Injection in Integration for Keap/infusionsoft and Contact Form 7, WPForms, Elementor, Formidable, Ninja Forms = 1.2.1 versions.

- [https://github.com/izxci/CVE-2026-49104-](https://github.com/izxci/CVE-2026-49104-) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-49104-.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-49104-.svg)


## CVE-2026-49085
 Unauthenticated PHP Object Injection in WP Insightly for Contact Form 7, WPForms, Elementor, Formidable and Ninja Forms = 1.1.4 versions.

- [https://github.com/izxci/CVE-2026-49085](https://github.com/izxci/CVE-2026-49085) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-49085.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-49085.svg)


## CVE-2026-49083
 Contributor Privilege Escalation in LatePoint = 5.5.1 versions.

- [https://github.com/87achrafg-stack/CVE-2026-49083](https://github.com/87achrafg-stack/CVE-2026-49083) :  ![starts](https://img.shields.io/github/stars/87achrafg-stack/CVE-2026-49083.svg) ![forks](https://img.shields.io/github/forks/87achrafg-stack/CVE-2026-49083.svg)
- [https://github.com/izxci/CVE-2026-49083](https://github.com/izxci/CVE-2026-49083) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-49083.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-49083.svg)


## CVE-2026-49079
 Unauthenticated SQL Injection in JetSearch = 3.5.17 versions.

- [https://github.com/izxci/CVE-2026-49079](https://github.com/izxci/CVE-2026-49079) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-49079.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-49079.svg)


## CVE-2026-49060
This issue affects Hippoo Mobile App for WooCommerce: from n/a through 1.9.4.

- [https://github.com/rootdirective-sec/CVE-2026-49060-Lab](https://github.com/rootdirective-sec/CVE-2026-49060-Lab) :  ![starts](https://img.shields.io/github/stars/rootdirective-sec/CVE-2026-49060-Lab.svg) ![forks](https://img.shields.io/github/forks/rootdirective-sec/CVE-2026-49060-Lab.svg)


## CVE-2026-48907
 A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

- [https://github.com/HORKimhab/CVE-2026-48907](https://github.com/HORKimhab/CVE-2026-48907) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-48907.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-48907.svg)
- [https://github.com/wearehackers160/CVE-2026-48907](https://github.com/wearehackers160/CVE-2026-48907) :  ![starts](https://img.shields.io/github/stars/wearehackers160/CVE-2026-48907.svg) ![forks](https://img.shields.io/github/forks/wearehackers160/CVE-2026-48907.svg)


## CVE-2026-47774
 Envoy is an open source edge and service proxy designed for cloud-native applications. Prior to versions 1.35.11, 1.36.7, 1.37.3, and 1.38.1, a vulnerability in Envoy's HTTP/2 downstream request processing allows an unauthenticated remote client to trigger excessive memory consumption, potentially resulting in OOM termination of the Envoy process and denial of service. The issue arises from the combination of two behaviors. First, cookie header bytes are not fully accounted for during request header size validation in Envoy. Second, HPACK header block limits in oghttp2/quiche are enforced on encoded bytes without a corresponding limit on total decoded header size. Together, these behaviors allow a malicious client to cause large decoded header allocations while bypassing the intended request header size protections. Versions 1.35.11, 1.36.7, 1.37.3, and 1.38.1 contain a fix. No complete workaround is known short of applying a fix. Possible temporary mitigations include disabling downstream HTTP/2 where operationally feasible; enforcing stricter request header and cookie limits before traffic reaches Envoy; and monitoring Envoy memory usage for abnormal growth under HTTP/2 traffic.

- [https://github.com/minc-nice-100/http2-bomb-analysis-paper](https://github.com/minc-nice-100/http2-bomb-analysis-paper) :  ![starts](https://img.shields.io/github/stars/minc-nice-100/http2-bomb-analysis-paper.svg) ![forks](https://img.shields.io/github/forks/minc-nice-100/http2-bomb-analysis-paper.svg)


## CVE-2026-46331
offset_valid() against INT_MIN, where negation is undefined.

- [https://github.com/sgkdev/packet_edit_meme](https://github.com/sgkdev/packet_edit_meme) :  ![starts](https://img.shields.io/github/stars/sgkdev/packet_edit_meme.svg) ![forks](https://img.shields.io/github/forks/sgkdev/packet_edit_meme.svg)


## CVE-2026-46300
bytes into @to's linear data rather than transferring frag descriptors.

- [https://github.com/BenedictEjepu/CVE-2026-46300-Fragnesia---TryHackMe-Lab-Project](https://github.com/BenedictEjepu/CVE-2026-46300-Fragnesia---TryHackMe-Lab-Project) :  ![starts](https://img.shields.io/github/stars/BenedictEjepu/CVE-2026-46300-Fragnesia---TryHackMe-Lab-Project.svg) ![forks](https://img.shields.io/github/forks/BenedictEjepu/CVE-2026-46300-Fragnesia---TryHackMe-Lab-Project.svg)
- [https://github.com/BenedictEjepu/CVE-2026-46300-Fragnesia---TryHackMe-Lab-Walkthrough](https://github.com/BenedictEjepu/CVE-2026-46300-Fragnesia---TryHackMe-Lab-Walkthrough) :  ![starts](https://img.shields.io/github/stars/BenedictEjepu/CVE-2026-46300-Fragnesia---TryHackMe-Lab-Walkthrough.svg) ![forks](https://img.shields.io/github/forks/BenedictEjepu/CVE-2026-46300-Fragnesia---TryHackMe-Lab-Walkthrough.svg)


## CVE-2026-45777
 OpenXDMoD is an open framework for collecting and analyzing HPC metrics. Starting in version 9.5.0 and prior to version 11.0.3, an attacker can remotely execute arbitrary system commands on the web server hosting Open XDMoD with the privileges of the web server process. This could allow an attacker to read or modify application data, alter system configuration, or disrupt service availability. All deployments of Open XDMoD versions 9.5.0 through 11.0.2 (inclusive) are impacted. This issue was reported privately on 2026-04-06, and at this time there is no evidence that this vulnerability has been exploited in the wild. The vulnerability was patched in Open XDMoD 11.0.3 on 2026-05-12. As a workaround, apply the patch manually.

- [https://github.com/morepoints/CVE-2026-45777](https://github.com/morepoints/CVE-2026-45777) :  ![starts](https://img.shields.io/github/stars/morepoints/CVE-2026-45777.svg) ![forks](https://img.shields.io/github/forks/morepoints/CVE-2026-45777.svg)


## CVE-2026-42945
 NGINX Plus and NGINX Open Source have a vulnerability in the ngx_http_rewrite_module module. This vulnerability exists when the rewrite directive is followed by a rewrite, if, or set directive and an unnamed Perl-Compatible Regular Expression (PCRE) capture (for example, $1, $2) with a replacement string that includes a question mark (?). An unauthenticated attacker along with conditions beyond its control can exploit this vulnerability by sending crafted HTTP requests. This may cause a heap buffer overflow in the NGINX worker process leading to a restart. Additionally, attackers can execute code on systems with Address Space Layout Randomization (ASLR) disabled or when the attacker can bypass ASLR.  Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

- [https://github.com/hulina9900-boop/DIY-CVE-2026-42945-POC](https://github.com/hulina9900-boop/DIY-CVE-2026-42945-POC) :  ![starts](https://img.shields.io/github/stars/hulina9900-boop/DIY-CVE-2026-42945-POC.svg) ![forks](https://img.shields.io/github/forks/hulina9900-boop/DIY-CVE-2026-42945-POC.svg)


## CVE-2026-42758
 Incorrect Privilege Assignment vulnerability in Saleswonder Team: Tobias WebinarIgnition webinar-ignition allows Privilege Escalation.This issue affects WebinarIgnition: from n/a through  4.08.253.

- [https://github.com/izxci/CVE-2026-42758](https://github.com/izxci/CVE-2026-42758) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-42758.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-42758.svg)


## CVE-2026-39813
 A path traversal: '../filedir' vulnerability in Fortinet FortiSandbox 5.0.0 through 5.0.5, FortiSandbox 4.4.0 through 4.4.8 may allow attacker to escalation of privilege via insert attack vector here

- [https://github.com/HORKimhab/CVE-2026-39813](https://github.com/HORKimhab/CVE-2026-39813) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-39813.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-39813.svg)


## CVE-2026-39808
 A improper neutralization of special elements used in an os command ('os command injection') vulnerability in Fortinet FortiSandbox 4.4.0 through 4.4.8 may allow attacker to execute unauthorized code or commands via insert attack vector here

- [https://github.com/HORKimhab/CVE-2026-39808](https://github.com/HORKimhab/CVE-2026-39808) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-39808.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-39808.svg)


## CVE-2026-32488
 Incorrect Privilege Assignment vulnerability in wpeverest User Registration user-registration allows Privilege Escalation.This issue affects User Registration: from n/a through = 4.4.9.

- [https://github.com/izxci/CVE-2026-32488](https://github.com/izxci/CVE-2026-32488) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-32488.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-32488.svg)


## CVE-2026-25177
 Improper restriction of names for files and other resources in Active Directory Domain Services allows an authorized attacker to elevate privileges over a network.

- [https://github.com/HORKimhab/CVE-2026-25177](https://github.com/HORKimhab/CVE-2026-25177) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-25177.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-25177.svg)


## CVE-2026-24061
 telnetd in GNU Inetutils through 2.7 allows remote authentication bypass via a "-f root" value for the USER environment variable.

- [https://github.com/akpmarcelin/CVE-2026-24061-lab](https://github.com/akpmarcelin/CVE-2026-24061-lab) :  ![starts](https://img.shields.io/github/stars/akpmarcelin/CVE-2026-24061-lab.svg) ![forks](https://img.shields.io/github/forks/akpmarcelin/CVE-2026-24061-lab.svg)


## CVE-2026-20262
This vulnerability exists because the affected software does not properly validate user-supplied input during a file upload process. An attacker could exploit this vulnerability by sending a crafted HTTP request to an affected API endpoint of the affected system. A successful exploit could allow the attacker to create or overwrite any file on the underlying operating system. This file could later be used to elevate to root. To exploit this vulnerability, the attacker must have valid credentials with at least a lower-privileged, single-task user account.

- [https://github.com/fevar54/CVE-2026-20262-Cisco-Catalyst-SD-WAN-Manager-Arbitrary-File-Write-](https://github.com/fevar54/CVE-2026-20262-Cisco-Catalyst-SD-WAN-Manager-Arbitrary-File-Write-) :  ![starts](https://img.shields.io/github/stars/fevar54/CVE-2026-20262-Cisco-Catalyst-SD-WAN-Manager-Arbitrary-File-Write-.svg) ![forks](https://img.shields.io/github/forks/fevar54/CVE-2026-20262-Cisco-Catalyst-SD-WAN-Manager-Arbitrary-File-Write-.svg)


## CVE-2026-9691
 Unauthenticated PHP Object Injection in Integration for ActiveCampaign and Contact Form 7, WPForms, Elementor, Ninja Forms = 1.1.1 versions.

- [https://github.com/izxci/CVE-2026-9691](https://github.com/izxci/CVE-2026-9691) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-9691.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-9691.svg)


## CVE-2026-8206
 The Kirki – Freeform Page Builder, Website Builder & Customizer plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions 6.0.0 to 6.0.6. This is due to the plugin accepting an arbitrary email address when a username is used in the password reset request. This makes it possible for unauthenticated attackers to send a password reset link for any user registered on the site to their own email address.

- [https://github.com/izxci/CVE-2026-8206](https://github.com/izxci/CVE-2026-8206) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-8206.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-8206.svg)


## CVE-2026-7654
 The Admin Columns plugin for WordPress is vulnerable to PHP Object Injection leading to Remote Code Execution in versions up to and including 7.0.18. This is due to the use of `unserialize()` without an `allowed_classes` restriction in the `IdsToCollection::get_ids_from_string()` function, which processes attacker-controlled post meta values without proper validation. This makes it possible for authenticated attackers with Contributor-level access and above to inject a serialized PHP object into a post's custom meta field and trigger arbitrary code execution by exploiting a bundled POP gadget chain, resulting in remote code execution as the web server user.

- [https://github.com/izxci/CVE-2026-7654](https://github.com/izxci/CVE-2026-7654) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-7654.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-7654.svg)


## CVE-2026-7465
 The Spectra Gutenberg Blocks – Website Builder for the Block Editor plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 2.19.25. This makes it possible for authenticated attackers, with Contributor-level access and above, to execute code on the server. Exploitation requires a two-block payload embedded in post content: the first block registers a fake uagb/-prefixed block type with an attacker-specified render_callback, and the second block of the same fake type triggers invocation of that callback via call_user_func() during sequential block rendering in the same page request.

- [https://github.com/izxci/-CVE-2026-7465](https://github.com/izxci/-CVE-2026-7465) :  ![starts](https://img.shields.io/github/stars/izxci/-CVE-2026-7465.svg) ![forks](https://img.shields.io/github/forks/izxci/-CVE-2026-7465.svg)


## CVE-2026-7459
 The Simple History – Track, Log, and Audit WordPress Changes plugin for WordPress is vulnerable to authenticated (Subscriber+) account takeover in all versions up to, and including, 5.26.0 via the event reaction endpoints (react_to_event() / unreact_to_event()). The endpoints register get_items_permissions_check() as their permission_callback, which only verifies the requester is logged in and does not enforce the per-logger capability checks normally applied by Log_Query. As a result, a Subscriber-level user can POST to /wp-json/simple-history/v1/events/id/react with the _fields=context query parameter and read the full context of any Simple History event — including SimpleUserLogger entries that record the full password-reset email body (reset URL with the reset key) for any user. The attacker triggers a password reset for an administrator via the lost-password form, brute-forces recent event IDs through the reaction endpoint to read the resulting user_requested_password_reset_link event, extracts the reset key from context.message, and completes the password reset to take over the administrator account. Exploitation requires an administrator to have first enabled the experimental features option (simple_history_experimental_features_enabled), which is not the default.

- [https://github.com/izxci/CVE-2026-7459](https://github.com/izxci/CVE-2026-7459) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-7459.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-7459.svg)


## CVE-2026-5415
 The WP Captcha PRO (the premium version of the Advanced Google reCAPTCHA plugin, both have the same slug) plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 5.38. This is due to the ajax_run_tool() AJAX handler relying solely on a nonce check (check_ajax_referer) for security without performing any capability check, combined with the create_temporary_link tool allowing the generation of passwordless login links for arbitrary users, and the handle_temporary_links() function authenticating visitors via these links without any additional authorization validation. The required nonce is exposed to all authenticated backend users (including Subscribers) via wp_localize_script() on all non-settings admin pages when the plugin's welcome pointer has not been dismissed. This makes it possible for authenticated attackers, with Subscriber-level access and above, to bypass normal authentication and log in as any user, including Administrators, resulting in complete account takeover.

- [https://github.com/izxci/CVE-2026-5415](https://github.com/izxci/CVE-2026-5415) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-5415.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-5415.svg)


## CVE-2026-5411
 The WP Captcha PRO (the premium version of the Advanced Google reCAPTCHA plugin, both have the same slug) plugin for WordPress is vulnerable to arbitrary file upload in all versions up to, and including, 5.38. This is due to a capability check in the save_ajax() function of the licensing module, combined with unrestricted file extraction in sync_cloud_protection(). This makes it possible for authenticated attackers, with Subscriber-level access and above, to upload arbitrary files including PHP webshells to the server by injecting a malicious cloud_protection_url into the license meta, which the plugin then downloads and extracts without file type validation into a web-accessible uploads directory. This can be used for remote code execution. Note: The vulnerability can only be exploited with a remote URL if "allow_url_fopen" is enabled in the php.ini config.

- [https://github.com/izxci/CVE-2026-5411](https://github.com/izxci/CVE-2026-5411) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-5411.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-5411.svg)


## CVE-2026-5281
 Use after free in Dawn in Google Chrome prior to 146.0.7680.178 allowed a remote attacker who had compromised the renderer process to execute arbitrary code via a crafted HTML page. (Chromium security severity: High)

- [https://github.com/jaf0rk/CVE-2026-5281](https://github.com/jaf0rk/CVE-2026-5281) :  ![starts](https://img.shields.io/github/stars/jaf0rk/CVE-2026-5281.svg) ![forks](https://img.shields.io/github/forks/jaf0rk/CVE-2026-5281.svg)


## CVE-2026-3909
 Out of bounds write in Skia in Google Chrome prior to 146.0.7680.75 allowed a remote attacker to perform out of bounds memory access via a crafted HTML page. (Chromium security severity: High)

- [https://github.com/jaf0rk/CVE-2026-3909](https://github.com/jaf0rk/CVE-2026-3909) :  ![starts](https://img.shields.io/github/stars/jaf0rk/CVE-2026-3909.svg) ![forks](https://img.shields.io/github/forks/jaf0rk/CVE-2026-3909.svg)


## CVE-2026-3642
 The e-shot™ form builder plugin for WordPress is vulnerable to Missing Authorization in all versions up to and including 1.0.2. The eshot_form_builder_update_field_data() AJAX handler lacks any capability checks (current_user_can()) or nonce verification (check_ajax_referer()/wp_verify_nonce()). The function is registered via the wp_ajax_ hook, making it accessible to any authenticated user. This makes it possible for authenticated attackers, with Subscriber-level access and above, to modify form field configurations including mandatory status, field visibility, and form display preferences via the eshot_form_builder_update_field_data AJAX action.

- [https://github.com/redteamfortress/CVE-2026-36425](https://github.com/redteamfortress/CVE-2026-36425) :  ![starts](https://img.shields.io/github/stars/redteamfortress/CVE-2026-36425.svg) ![forks](https://img.shields.io/github/forks/redteamfortress/CVE-2026-36425.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-transitive.svg)


## CVE-2025-66391
 In Citrix Cloud through 2025-11-10, an account with read-only access can trigger the beginning of a workflow for write operations, e.g., the system will send a one-time password to an attacker-controlled email address when the attacker attempts to reset the password of a user account.

- [https://github.com/mandeepsohal/CVE-2025-66391](https://github.com/mandeepsohal/CVE-2025-66391) :  ![starts](https://img.shields.io/github/stars/mandeepsohal/CVE-2025-66391.svg) ![forks](https://img.shields.io/github/forks/mandeepsohal/CVE-2025-66391.svg)


## CVE-2025-54123
 Hoverfly is an open source API simulation tool. In versions 1.11.3 and prior, the middleware functionality in Hoverfly is vulnerable to command injection vulnerability at `/api/v2/hoverfly/middleware` endpoint due to insufficient validation and sanitization in user input. The vulnerability exists in the middleware management API endpoint `/api/v2/hoverfly/middleware`. This issue is born due to combination of three code level flaws: Insufficient Input Validation in middleware.go line 94-96; Unsafe Command Execution in local_middleware.go line 14-19; and Immediate Execution During Testing in hoverfly_service.go line 173. This allows an attacker to gain remote code execution (RCE) on any system running the vulnerable Hoverfly service. Since the input is directly passed to system commands without proper checks, an attacker can upload a malicious payload or directly execute arbitrary commands (including reverse shells) on the host server with the privileges of the Hoverfly process. Commit 17e60a9bc78826deb4b782dca1c1abd3dbe60d40 in version 1.12.0 disables the set middleware API by default, and subsequent changes to documentation make users aware of the security changes of exposing the set middleware API.

- [https://github.com/0xk4rth1/CVE-2025-54123](https://github.com/0xk4rth1/CVE-2025-54123) :  ![starts](https://img.shields.io/github/stars/0xk4rth1/CVE-2025-54123.svg) ![forks](https://img.shields.io/github/forks/0xk4rth1/CVE-2025-54123.svg)


## CVE-2025-26240
 In JazzCore python-pdfkit 1.0.0, the from_string method enables the execution of JavaScript code within the context of the server application and the exfiltration of local files.

- [https://github.com/Habuon/CVE-2025-26240](https://github.com/Habuon/CVE-2025-26240) :  ![starts](https://img.shields.io/github/stars/Habuon/CVE-2025-26240.svg) ![forks](https://img.shields.io/github/forks/Habuon/CVE-2025-26240.svg)


## CVE-2025-11683
The issue is seen with complex YAML files with a hash of all keys and empty values.  There is no indication that the issue leads to accessing memory outside that allocated to the module.

- [https://github.com/ValentinTorassa/ubuntu-security-fixes](https://github.com/ValentinTorassa/ubuntu-security-fixes) :  ![starts](https://img.shields.io/github/stars/ValentinTorassa/ubuntu-security-fixes.svg) ![forks](https://img.shields.io/github/forks/ValentinTorassa/ubuntu-security-fixes.svg)


## CVE-2025-11266
 An out-of-bounds write vulnerability exists in the Grassroots DICOM library (GDCM). The issue is triggered during parsing of a malformed DICOM file containing encapsulated PixelData fragments (compressed image data stored as multiple fragments). This vulnerability leads to a segmentation fault caused by an out-of-bounds memory access due to unsigned integer underflow in buffer indexing. It is exploitable via file input, simply opening a crafted malicious DICOM file is sufficient to trigger the crash, resulting in a denial-of-service condition.

- [https://github.com/ValentinTorassa/ubuntu-security-fixes](https://github.com/ValentinTorassa/ubuntu-security-fixes) :  ![starts](https://img.shields.io/github/stars/ValentinTorassa/ubuntu-security-fixes.svg) ![forks](https://img.shields.io/github/forks/ValentinTorassa/ubuntu-security-fixes.svg)


## CVE-2025-11021
 A flaw was found in the cookie date handling logic of the libsoup HTTP library, widely used by GNOME and other applications for web communication. When processing cookies with specially crafted expiration dates, the library may perform an out-of-bounds memory read. This flaw could result in unintended disclosure of memory contents, potentially exposing sensitive information from the process using libsoup.

- [https://github.com/ValentinTorassa/ubuntu-security-fixes](https://github.com/ValentinTorassa/ubuntu-security-fixes) :  ![starts](https://img.shields.io/github/stars/ValentinTorassa/ubuntu-security-fixes.svg) ![forks](https://img.shields.io/github/forks/ValentinTorassa/ubuntu-security-fixes.svg)


## CVE-2024-42009
 A Cross-Site Scripting vulnerability in Roundcube through 1.5.7 and 1.6.x through 1.6.7 allows a remote attacker to steal and send emails of a victim via a crafted e-mail message that abuses a Desanitization issue in message_body() in program/actions/mail/show.php.

- [https://github.com/segunakinsoyinu/CVE-2024-42009-roundcube-xss](https://github.com/segunakinsoyinu/CVE-2024-42009-roundcube-xss) :  ![starts](https://img.shields.io/github/stars/segunakinsoyinu/CVE-2024-42009-roundcube-xss.svg) ![forks](https://img.shields.io/github/forks/segunakinsoyinu/CVE-2024-42009-roundcube-xss.svg)


## CVE-2024-38819
 Applications serving static resources through the functional web frameworks WebMvc.fn or WebFlux.fn are vulnerable to path traversal attacks. An attacker can craft malicious HTTP requests and obtain any file on the file system that is also accessible to the process in which the Spring application is running.

- [https://github.com/trevorputbrese/cve-2024-38819-lab](https://github.com/trevorputbrese/cve-2024-38819-lab) :  ![starts](https://img.shields.io/github/stars/trevorputbrese/cve-2024-38819-lab.svg) ![forks](https://img.shields.io/github/forks/trevorputbrese/cve-2024-38819-lab.svg)


## CVE-2024-6536
 The Zephyr Project Manager WordPress plugin before 3.3.99 does not sanitise and escape some of its settings, which could allow high privilege users such as editors and admins to perform Stored Cross-Site Scripting attacks even when the unfiltered_html capability is disallowed (for example in multisite setup)

- [https://github.com/gfd6tthf/CVE-2024-6536](https://github.com/gfd6tthf/CVE-2024-6536) :  ![starts](https://img.shields.io/github/stars/gfd6tthf/CVE-2024-6536.svg) ![forks](https://img.shields.io/github/forks/gfd6tthf/CVE-2024-6536.svg)


## CVE-2022-29800
 A time-of-check-time-of-use (TOCTOU) race condition vulnerability was found in networkd-dispatcher. This flaw exists because there is a certain time between the scripts being discovered and them being run. An attacker can abuse this vulnerability to replace scripts that networkd-dispatcher believes to be owned by root with ones that are not.

- [https://github.com/joshuavanderpoll/NimbusPWN-CVE-2022-29799-29800](https://github.com/joshuavanderpoll/NimbusPWN-CVE-2022-29799-29800) :  ![starts](https://img.shields.io/github/stars/joshuavanderpoll/NimbusPWN-CVE-2022-29799-29800.svg) ![forks](https://img.shields.io/github/forks/joshuavanderpoll/NimbusPWN-CVE-2022-29799-29800.svg)


## CVE-2022-29799
 A vulnerability was found in networkd-dispatcher. This flaw exists because no functions are sanitized by the OperationalState or the AdministrativeState of networkd-dispatcher. This attack leads to a directory traversal to escape from the “/etc/networkd-dispatcher” base directory.

- [https://github.com/joshuavanderpoll/NimbusPWN-CVE-2022-29799-29800](https://github.com/joshuavanderpoll/NimbusPWN-CVE-2022-29799-29800) :  ![starts](https://img.shields.io/github/stars/joshuavanderpoll/NimbusPWN-CVE-2022-29799-29800.svg) ![forks](https://img.shields.io/github/forks/joshuavanderpoll/NimbusPWN-CVE-2022-29799-29800.svg)


## CVE-2021-41773
 A flaw was found in a change made to path normalization in Apache HTTP Server 2.4.49. An attacker could use a path traversal attack to map URLs to files outside the directories configured by Alias-like directives. If files outside of these directories are not protected by the usual default configuration "require all denied", these requests can succeed. If CGI scripts are also enabled for these aliased pathes, this could allow for remote code execution. This issue is known to be exploited in the wild. This issue only affects Apache 2.4.49 and not earlier versions. The fix in Apache HTTP Server 2.4.50 was found to be incomplete, see CVE-2021-42013.

- [https://github.com/TheLastVvV/CVE-2021-41773](https://github.com/TheLastVvV/CVE-2021-41773) :  ![starts](https://img.shields.io/github/stars/TheLastVvV/CVE-2021-41773.svg) ![forks](https://img.shields.io/github/forks/TheLastVvV/CVE-2021-41773.svg)


## CVE-2021-34427
 In Eclipse BIRT versions 4.8.0 and earlier, an attacker can use query parameters to create a JSP file which is accessible from remote (current BIRT viewer dir) to inject JSP code into the running instance.

- [https://github.com/rt1252/CVE-2021-34427](https://github.com/rt1252/CVE-2021-34427) :  ![starts](https://img.shields.io/github/stars/rt1252/CVE-2021-34427.svg) ![forks](https://img.shields.io/github/forks/rt1252/CVE-2021-34427.svg)


## CVE-2021-27876
 An issue was discovered in Veritas Backup Exec before 21.2. The communication between a client and an Agent requires successful authentication, which is typically completed over a secure TLS communication. However, due to a vulnerability in the SHA Authentication scheme, an attacker is able to gain unauthorized access and complete the authentication process. Subsequently, the client can execute data management protocol commands on the authenticated connection. By using crafted input parameters in one of these commands, an attacker can access an arbitrary file on the system using System privileges.

- [https://github.com/wingerbijay/CVE-2021-27876](https://github.com/wingerbijay/CVE-2021-27876) :  ![starts](https://img.shields.io/github/stars/wingerbijay/CVE-2021-27876.svg) ![forks](https://img.shields.io/github/forks/wingerbijay/CVE-2021-27876.svg)


## CVE-2021-3975
 A use-after-free flaw was found in libvirt. The qemuMonitorUnregister() function in qemuProcessHandleMonitorEOF is called using multiple threads without being adequately protected by a monitor lock. This flaw could be triggered by the virConnectGetAllDomainStats API when the guest is shutting down. An unprivileged client with a read-only connection could use this flaw to perform a denial of service attack by causing the libvirt daemon to crash.

- [https://github.com/yan5ui/ENV-CVE-2021-3975](https://github.com/yan5ui/ENV-CVE-2021-3975) :  ![starts](https://img.shields.io/github/stars/yan5ui/ENV-CVE-2021-3975.svg) ![forks](https://img.shields.io/github/forks/yan5ui/ENV-CVE-2021-3975.svg)


## CVE-2020-8036
 The tok2strbuf() function in tcpdump 4.10.0-PRE-GIT was used by the SOME/IP dissector in an unsafe way.

- [https://github.com/yan5ui/ENV-CVE-2020-8036](https://github.com/yan5ui/ENV-CVE-2020-8036) :  ![starts](https://img.shields.io/github/stars/yan5ui/ENV-CVE-2020-8036.svg) ![forks](https://img.shields.io/github/forks/yan5ui/ENV-CVE-2020-8036.svg)


## CVE-2015-10141
 An unauthenticated OS command injection vulnerability exists within Xdebug versions 2.5.5 and earlier, a PHP debugging extension developed by Derick Rethans. When remote debugging is enabled, Xdebug listens on port 9000 and accepts debugger protocol commands without authentication. An attacker can send a crafted eval command over this interface to execute arbitrary PHP code, which may invoke system-level functions such as system() or passthru(). This results in full compromise of the host under the privileges of the web server user.

- [https://github.com/K3ysTr0K3R/CVE-2015-10141](https://github.com/K3ysTr0K3R/CVE-2015-10141) :  ![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2015-10141.svg) ![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2015-10141.svg)

