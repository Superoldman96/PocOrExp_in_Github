# Update 2026-06-17
## CVE-2026-53519
 Nezha Monitoring is a self-hostable, lightweight, servers and websites monitoring and O&M tool. Prior to version 2.0.13, fallbackToFrontend in the dashboard's NoRoute handler treats any URL whose raw string starts with /dashboard as an admin-frontend asset request. The check uses strings.HasPrefix, not a path-segment match, so the input /dashboard../data/config.yaml is accepted; strings.TrimPrefix leaves ../data/config.yaml; and path.Join("admin-dist", "../data/config.yaml") normalizes to data/config.yaml — which os.Stat finds and http.ServeFile returns. No authentication required. This issue has been patched in version 2.0.13.

- [https://github.com/tar-xz/CVE-2026-53519-PoC](https://github.com/tar-xz/CVE-2026-53519-PoC) :  ![starts](https://img.shields.io/github/stars/tar-xz/CVE-2026-53519-PoC.svg) ![forks](https://img.shields.io/github/forks/tar-xz/CVE-2026-53519-PoC.svg)


## CVE-2026-49160
 Uncontrolled resource consumption in HTTP/2 allows an unauthorized attacker to deny service over a network.

- [https://github.com/dhmosfunk/CVE-2026-49160-HTTP.sys](https://github.com/dhmosfunk/CVE-2026-49160-HTTP.sys) :  ![starts](https://img.shields.io/github/stars/dhmosfunk/CVE-2026-49160-HTTP.sys.svg) ![forks](https://img.shields.io/github/forks/dhmosfunk/CVE-2026-49160-HTTP.sys.svg)


## CVE-2026-48849
 In Roundcube Webmail 1.6.x before 1.6.16 and 1.7.x before 1.7.1, an unsanitized subject field in the draft restored value could lead to stored XSS/HTML/CSS injection on shared mailboxes.

- [https://github.com/AnandJogawade/CVE-2026-48849-Roundcube-Webmail-Stored-XSS](https://github.com/AnandJogawade/CVE-2026-48849-Roundcube-Webmail-Stored-XSS) :  ![starts](https://img.shields.io/github/stars/AnandJogawade/CVE-2026-48849-Roundcube-Webmail-Stored-XSS.svg) ![forks](https://img.shields.io/github/forks/AnandJogawade/CVE-2026-48849-Roundcube-Webmail-Stored-XSS.svg)


## CVE-2026-48017
 DbGate is cross-platform database manager. In versions 7.1.8 and prior, the POST /runners/load-reader endpoint in DbGate accepts a functionName parameter that is directly interpolated into a JavaScript code template without any sanitization or validation. An authenticated user (with basic access, no special permissions required) can inject arbitrary JavaScript code that executes on the server with full process privileges, bypassing the require=null sandbox restriction. An authenticated user with basic access (no admin role, no run-shell-script permission required) can: execute arbitrary OS commands on the DbGate server with the privileges of the Node.js process, read/write any file accessible to the process, pivot to connected databases by reading connection credentials from DbGate's storage, and compromise the host system - in Docker deployments, this typically means root access within the container.

- [https://github.com/romain-deperne/CVE-2026-48017](https://github.com/romain-deperne/CVE-2026-48017) :  ![starts](https://img.shields.io/github/stars/romain-deperne/CVE-2026-48017.svg) ![forks](https://img.shields.io/github/forks/romain-deperne/CVE-2026-48017.svg)


## CVE-2026-45585
No, if you are using TPM+PIN the vulnerability is not exploitable.

- [https://github.com/saradasen27-collab/yellowkey-forensic-decryptor](https://github.com/saradasen27-collab/yellowkey-forensic-decryptor) :  ![starts](https://img.shields.io/github/stars/saradasen27-collab/yellowkey-forensic-decryptor.svg) ![forks](https://img.shields.io/github/forks/saradasen27-collab/yellowkey-forensic-decryptor.svg)


## CVE-2026-40791
 Unauthenticated Cross Site Scripting (XSS) in WP Time Slots Booking Form = 1.2.46 versions.

- [https://github.com/Rat5ak/CVE-2026-40791-WP-Time-Slots-Booking-Form-XSS](https://github.com/Rat5ak/CVE-2026-40791-WP-Time-Slots-Booking-Form-XSS) :  ![starts](https://img.shields.io/github/stars/Rat5ak/CVE-2026-40791-WP-Time-Slots-Booking-Form-XSS.svg) ![forks](https://img.shields.io/github/forks/Rat5ak/CVE-2026-40791-WP-Time-Slots-Booking-Form-XSS.svg)


## CVE-2026-40776
 Unauthenticated Broken Access Control in WP Event SOlution = 4.1.8 versions.

- [https://github.com/lorenzofradeani/CVE-2026-40776](https://github.com/lorenzofradeani/CVE-2026-40776) :  ![starts](https://img.shields.io/github/stars/lorenzofradeani/CVE-2026-40776.svg) ![forks](https://img.shields.io/github/forks/lorenzofradeani/CVE-2026-40776.svg)


## CVE-2026-40176
 Composer is a dependency manager for PHP. Versions 1.0 through 2.2.26 and 2.3 through 2.9.5 contain a command injection vulnerability in the Perforce::generateP4Command() method, which constructs shell commands by interpolating user-supplied Perforce connection parameters (port, user, client) without proper escaping. An attacker can inject arbitrary commands through these values in a malicious composer.json declaring a Perforce VCS repository, leading to command execution in the context of the user running Composer, even if Perforce is not installed. VCS repositories are only loaded from the root composer.json or the composer config directory, so this cannot be exploited through composer.json files of packages installed as dependencies. Users are at risk if they run Composer commands on untrusted projects with attacker-supplied composer.json files. This issue has been fixed in Composer 2.2.27 (2.2 LTS) and 2.9.6 (mainline).

- [https://github.com/ikarolaborda/CVE-2026-40176](https://github.com/ikarolaborda/CVE-2026-40176) :  ![starts](https://img.shields.io/github/stars/ikarolaborda/CVE-2026-40176.svg) ![forks](https://img.shields.io/github/forks/ikarolaborda/CVE-2026-40176.svg)


## CVE-2026-38812
 RuoYi v4.8.2 is vulnerable to SQL Injection via the /tool/gen/createTable endpoint. The issue affects the code generation module and may allow an authenticated attacker with administrative privileges to access sensitive database information.

- [https://github.com/jjcjgo/CVE-2026-38812-RuoYi-SQL-Injection](https://github.com/jjcjgo/CVE-2026-38812-RuoYi-SQL-Injection) :  ![starts](https://img.shields.io/github/stars/jjcjgo/CVE-2026-38812-RuoYi-SQL-Injection.svg) ![forks](https://img.shields.io/github/forks/jjcjgo/CVE-2026-38812-RuoYi-SQL-Injection.svg)


## CVE-2026-36670
 A Time-Based Blind SQL Injection vulnerability in the alias_management module of OpenSIPS Control Panel (opensips-cp) prior to version 9.3.3 allows authenticated attackers to execute arbitrary SQL commands via the 'table' GET parameter in alias_management.php.

- [https://github.com/Gabriel-Lacorte/CVE-2026-36670](https://github.com/Gabriel-Lacorte/CVE-2026-36670) :  ![starts](https://img.shields.io/github/stars/Gabriel-Lacorte/CVE-2026-36670.svg) ![forks](https://img.shields.io/github/forks/Gabriel-Lacorte/CVE-2026-36670.svg)


## CVE-2026-36213
 An issue in Microvirt MEmu Android Emulator 9.2.7.0 allows a local attacker to escalate privileges via the MemuService.exe component.

- [https://github.com/sec-zone/CVE-2026-36213](https://github.com/sec-zone/CVE-2026-36213) :  ![starts](https://img.shields.io/github/stars/sec-zone/CVE-2026-36213.svg) ![forks](https://img.shields.io/github/forks/sec-zone/CVE-2026-36213.svg)


## CVE-2026-31431
AD directly.

- [https://github.com/waltrone1/copyfail-safe-check](https://github.com/waltrone1/copyfail-safe-check) :  ![starts](https://img.shields.io/github/stars/waltrone1/copyfail-safe-check.svg) ![forks](https://img.shields.io/github/forks/waltrone1/copyfail-safe-check.svg)


## CVE-2026-10795
 The UpdraftPlus: WP Backup & Migration Plugin plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.26.4 via the UpdraftPlus_Remote_Communications_V2::wp_loaded function. This is due to insufficient validation of the remote communications message format, where signature verification can be bypassed and unchecked decryption return values collapse to a predictable all-zero encryption key. This makes it possible for unauthenticated attackers to forge arbitrary RPC commands and run them as the connected administrator, such as uploading and activating a malicious plugin, which ultimately leads to remote code execution.

- [https://github.com/rootdirective-sec/CVE-2026-10795-Lab](https://github.com/rootdirective-sec/CVE-2026-10795-Lab) :  ![starts](https://img.shields.io/github/stars/rootdirective-sec/CVE-2026-10795-Lab.svg) ![forks](https://img.shields.io/github/forks/rootdirective-sec/CVE-2026-10795-Lab.svg)


## CVE-2026-9277
 shell-quote's `quote()` function did not validate object-token inputs against the operator model used by `parse()`. The `.op` field was backslash-escaped character by character using `/(.)/g`, which in JavaScript does not match line terminators (\n, \r, U+2028, U+2029). A line terminator in `.op` therefore passed through unescaped into the output; POSIX shells treat a literal newline as a command separator, so any content after it would execute as a second command. The vulnerable code path is reachable in two ways: (1) direct construction of `{ op: '...\n...' }` from external input, and (2) via `parse(cmd, envFn)` when `envFn` returns object tokens whose `.op` is attacker-influenced. Both are documented API surface. Fixed by replacing the per-character escape with strict shape validation: `.op` must match the parser's control-operator allowlist; `{ op: 'glob', pattern }` validates `pattern` and forbids line terminators; `{ comment }` validates `comment` and forbids line terminators; any other object shape throws `TypeError`.

- [https://github.com/DylanZahedi/CVE-2026-9277](https://github.com/DylanZahedi/CVE-2026-9277) :  ![starts](https://img.shields.io/github/stars/DylanZahedi/CVE-2026-9277.svg) ![forks](https://img.shields.io/github/forks/DylanZahedi/CVE-2026-9277.svg)


## CVE-2026-3707
 A vulnerability was identified in MrNanko webp4j up to 1.3.x. The affected element is the function DecodeGifFromMemory of the file src/main/c/gif_decoder.c. Such manipulation of the argument canvas_height leads to integer overflow. Local access is required to approach this attack. The exploit is publicly available and might be used. The name of the patch is 89771b201c66d15d29e4cc016d8aae82b6a5fbe1. It is advisable to implement a patch to correct this issue.

- [https://github.com/jfs-jfs/CVE-2026-37071](https://github.com/jfs-jfs/CVE-2026-37071) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37071.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37071.svg)
- [https://github.com/jfs-jfs/CVE-2026-37073](https://github.com/jfs-jfs/CVE-2026-37073) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37073.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37073.svg)
- [https://github.com/jfs-jfs/CVE-2026-37072](https://github.com/jfs-jfs/CVE-2026-37072) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37072.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37072.svg)
- [https://github.com/jfs-jfs/CVE-2026-37070](https://github.com/jfs-jfs/CVE-2026-37070) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37070.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37070.svg)


## CVE-2026-3706
 A vulnerability was determined in mkj Dropbear up to 2025.89. Impacted is the function unpackneg of the file src/curve25519.c of the component S Range Check. This manipulation causes improper verification of cryptographic signature. The attack can be initiated remotely. The attack is considered to have high complexity. The exploitability is considered difficult. The actual existence of this vulnerability is currently in question. Patch name: fdec3c90a15447bd538641d85e5a3e3ac981011d. To fix this issue, it is recommended to deploy a patch. The project maintainer explains: "Signature Malleability is not exploitable in SSH protocol. (...) [A] PoC doesn't exist for SSH implementation, but rather it's against the internal API."

- [https://github.com/jfs-jfs/CVE-2026-37069](https://github.com/jfs-jfs/CVE-2026-37069) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37069.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37069.svg)
- [https://github.com/jfs-jfs/CVE-2026-37067](https://github.com/jfs-jfs/CVE-2026-37067) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37067.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37067.svg)
- [https://github.com/jfs-jfs/CVE-2026-37068](https://github.com/jfs-jfs/CVE-2026-37068) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37068.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37068.svg)
- [https://github.com/jfs-jfs/CVE-2026-37066](https://github.com/jfs-jfs/CVE-2026-37066) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37066.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37066.svg)
- [https://github.com/jfs-jfs/CVE-2026-37065](https://github.com/jfs-jfs/CVE-2026-37065) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37065.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37065.svg)
- [https://github.com/jfs-jfs/CVE-2026-37064](https://github.com/jfs-jfs/CVE-2026-37064) :  ![starts](https://img.shields.io/github/stars/jfs-jfs/CVE-2026-37064.svg) ![forks](https://img.shields.io/github/forks/jfs-jfs/CVE-2026-37064.svg)


## CVE-2026-3637
 Mattermost versions 11.5.x = 11.5.1, 10.11.x = 10.11.13, 11.4.x = 11.4.3 fail to check the create_post channel permission during post edit operations which allows an authenticated attacker with revoked posting privileges to modify their existing posts via direct API requests to the post update and patch endpoints.. Mattermost Advisory ID: MMSA-2026-00627

- [https://github.com/RRespxwnss/CVE-2026-36374](https://github.com/RRespxwnss/CVE-2026-36374) :  ![starts](https://img.shields.io/github/stars/RRespxwnss/CVE-2026-36374.svg) ![forks](https://img.shields.io/github/forks/RRespxwnss/CVE-2026-36374.svg)


## CVE-2026-3437
 An Improper Restriction of Operations within the Bounds of a Memory Buffer vulnerability in Portwell Engineering Toolkits version 4.8.2 could allow a local authenticated attacker to read and write to arbitrary memory via the Portwell Engineering Toolkits driver. Successful exploitation of this vulnerability could result in escalation of privileges or cause a denial-of-service condition.

- [https://github.com/tihomirocrew/cve-2026-3437](https://github.com/tihomirocrew/cve-2026-3437) :  ![starts](https://img.shields.io/github/stars/tihomirocrew/cve-2026-3437.svg) ![forks](https://img.shields.io/github/forks/tihomirocrew/cve-2026-3437.svg)


## CVE-2026-0257
Panorama and Cloud NGFW are not impacted by these issues.

- [https://github.com/Ez4rd1x1/CVE-2026-0257](https://github.com/Ez4rd1x1/CVE-2026-0257) :  ![starts](https://img.shields.io/github/stars/Ez4rd1x1/CVE-2026-0257.svg) ![forks](https://img.shields.io/github/forks/Ez4rd1x1/CVE-2026-0257.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/mantvmass/react2shell](https://github.com/mantvmass/react2shell) :  ![starts](https://img.shields.io/github/stars/mantvmass/react2shell.svg) ![forks](https://img.shields.io/github/forks/mantvmass/react2shell.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-alias](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-alias) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-alias.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-alias.svg)


## CVE-2025-15556
 Notepad++ versions prior to 8.8.9, when using the WinGUp updater, contain an update integrity verification vulnerability where downloaded update metadata and installers are not cryptographically verified. An attacker able to intercept or redirect update traffic can cause the updater to download and execute an attacker-controlled installer, resulting in arbitrary code execution with the privileges of the user.

- [https://github.com/centaurwandanger/Notepad-Plus-Plus-v8.9.6-Unlocked](https://github.com/centaurwandanger/Notepad-Plus-Plus-v8.9.6-Unlocked) :  ![starts](https://img.shields.io/github/stars/centaurwandanger/Notepad-Plus-Plus-v8.9.6-Unlocked.svg) ![forks](https://img.shields.io/github/forks/centaurwandanger/Notepad-Plus-Plus-v8.9.6-Unlocked.svg)


## CVE-2025-12420
ServiceNow has addressed this vulnerability by deploying a relevant security update to  hosted instances in October 2025. Security updates have also been provided to ServiceNow self-hosted customers, partners, and hosted customers with unique configurations. Additionally, the vulnerability is addressed in the listed Store App versions. We recommend that customers promptly apply an appropriate security update or upgrade if they have not already done so.

- [https://github.com/OloladeAbiola03/aisecplus-week01-servicenow-ai-security-incident](https://github.com/OloladeAbiola03/aisecplus-week01-servicenow-ai-security-incident) :  ![starts](https://img.shields.io/github/stars/OloladeAbiola03/aisecplus-week01-servicenow-ai-security-incident.svg) ![forks](https://img.shields.io/github/forks/OloladeAbiola03/aisecplus-week01-servicenow-ai-security-incident.svg)


## CVE-2025-2783
 Incorrect handle provided in unspecified circumstances in Mojo in Google Chrome on Windows prior to 134.0.6998.177 allowed a remote attacker to perform a sandbox escape via a malicious file. (Chromium security severity: High)

- [https://github.com/ElianGonzi00/CVE-2025-2783](https://github.com/ElianGonzi00/CVE-2025-2783) :  ![starts](https://img.shields.io/github/stars/ElianGonzi00/CVE-2025-2783.svg) ![forks](https://img.shields.io/github/forks/ElianGonzi00/CVE-2025-2783.svg)


## CVE-2023-24012
 An attacker can arbitrarily craft malicious DDS Participants (or ROS 2 Nodes) with valid certificates to compromise and get full control of the attacked secure DDS databus system by exploiting vulnerable attributes in the configuration of PKCS#7 certificate’s validation. This is caused by a non-compliant implementation of permission document verification used by some DDS vendors. Specifically, an improper use of the OpenSSL PKCS7_verify function used to validate S/MIME signatures.

- [https://github.com/SafeLock-D2E/Quiksand-CVE-2023-24012](https://github.com/SafeLock-D2E/Quiksand-CVE-2023-24012) :  ![starts](https://img.shields.io/github/stars/SafeLock-D2E/Quiksand-CVE-2023-24012.svg) ![forks](https://img.shields.io/github/forks/SafeLock-D2E/Quiksand-CVE-2023-24012.svg)


## CVE-2022-30190
Please see the MSRC Blog Entry for important information about steps you can take to protect your system from this vulnerability.

- [https://github.com/czabatta/THM-Tempest](https://github.com/czabatta/THM-Tempest) :  ![starts](https://img.shields.io/github/stars/czabatta/THM-Tempest.svg) ![forks](https://img.shields.io/github/forks/czabatta/THM-Tempest.svg)


## CVE-2017-5123
 Insufficient data validation in waitid allowed an user to escape sandboxes on Linux.

- [https://github.com/ahiahai242/CVE-2017-5123](https://github.com/ahiahai242/CVE-2017-5123) :  ![starts](https://img.shields.io/github/stars/ahiahai242/CVE-2017-5123.svg) ![forks](https://img.shields.io/github/forks/ahiahai242/CVE-2017-5123.svg)

