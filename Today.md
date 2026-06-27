# Update 2026-06-27
## CVE-2026-54088
 File Browser is a file managing interface for uploading, deleting, previewing, renaming, and editing files within a specified directory. Prior to 2.63.6, the Hook Authentication feature in File Browser allows administrators to delegate login verification to an external shell command. User-supplied credentials (username and password) are interpolated into this command string using os.Expand without sanitization. An unauthenticated remote attacker can inject shell metacharacters in the username or password field at the login screen, causing the server to execute arbitrary OS commands before any authentication takes place. This is a critical pre-authentication RCE. This vulnerability is fixed in 2.63.6.

- [https://github.com/Saku0512/CVE-2026-54088-poc](https://github.com/Saku0512/CVE-2026-54088-poc) :  ![starts](https://img.shields.io/github/stars/Saku0512/CVE-2026-54088-poc.svg) ![forks](https://img.shields.io/github/forks/Saku0512/CVE-2026-54088-poc.svg)


## CVE-2026-53075
case.

- [https://github.com/lottiedeyan/CVE-2026-53075poc](https://github.com/lottiedeyan/CVE-2026-53075poc) :  ![starts](https://img.shields.io/github/stars/lottiedeyan/CVE-2026-53075poc.svg) ![forks](https://img.shields.io/github/forks/lottiedeyan/CVE-2026-53075poc.svg)


## CVE-2026-45321
 On 2026-05-11, between approximately 19:20 and 19:26 UTC, 84 malicious versions across 42 @tanstack/* packages were published to the npm registry. The publishes were authenticated via the legitimate GitHub Actions OIDC trusted-publisher binding for TanStack/router, but the publish workflow itself was not modified. The attacker chained three known vulnerability classes — a pull_request_target "Pwn Request" misconfiguration, GitHub Actions cache poisoning across the fork↔base trust boundary, and runtime memory extraction of the OIDC token from the Actions runner process — to publish credential-stealing malware under a trusted identity. Each affected package received exactly two malicious versions, published a few minutes apart.

- [https://github.com/7whyex/CVE-2026-45321-Tanstack](https://github.com/7whyex/CVE-2026-45321-Tanstack) :  ![starts](https://img.shields.io/github/stars/7whyex/CVE-2026-45321-Tanstack.svg) ![forks](https://img.shields.io/github/forks/7whyex/CVE-2026-45321-Tanstack.svg)


## CVE-2026-43503
so segments drawing frags from frag_list members carry the marker.

- [https://github.com/mooder1/dirtyclone-CVE-2026-43503](https://github.com/mooder1/dirtyclone-CVE-2026-43503) :  ![starts](https://img.shields.io/github/stars/mooder1/dirtyclone-CVE-2026-43503.svg) ![forks](https://img.shields.io/github/forks/mooder1/dirtyclone-CVE-2026-43503.svg)
- [https://github.com/0xBlackash/CVE-2026-43503](https://github.com/0xBlackash/CVE-2026-43503) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-43503.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-43503.svg)


## CVE-2026-37149
 GROCERY-STORE-MANAGEMENT-SYSTEM-USING-PHP-AND-MYSQL-PHPMYADMIN v1.0 was discovered to contain a SQL injection vulnerability in the scost parameter in /grocery/search_products.php. This vulnerability allows attackers to access sensitive database information via a crafted SQL statement.

- [https://github.com/pateldhyeyit/CVE-2026-37149](https://github.com/pateldhyeyit/CVE-2026-37149) :  ![starts](https://img.shields.io/github/stars/pateldhyeyit/CVE-2026-37149.svg) ![forks](https://img.shields.io/github/forks/pateldhyeyit/CVE-2026-37149.svg)


## CVE-2026-35603
 Claude Code is an agentic coding tool. In versions prior to 2.1.75 on Windows, Claude Code loaded the system-wide default configuration from C:\ProgramData\ClaudeCode\managed-settings.json without validating directory ownership or access permissions. Because the ProgramData directory is writable by non-administrative users by default and the ClaudeCode subdirectory was not pre-created or access-restricted, a low-privileged local user could create this directory and place a malicious configuration file that would be automatically loaded for any user launching Claude Code on the same machine. Exploiting this would have required a shared multi-user Windows system and a victim user to launch Claude Code after the malicious configuration was placed. This issue has been fixed on version 2.1.75.

- [https://github.com/jchable/miasma-toolkit](https://github.com/jchable/miasma-toolkit) :  ![starts](https://img.shields.io/github/stars/jchable/miasma-toolkit.svg) ![forks](https://img.shields.io/github/forks/jchable/miasma-toolkit.svg)


## CVE-2026-23111
skip active elements, process inactive ones.

- [https://github.com/Baba01hacker666/CVE-2026-23111](https://github.com/Baba01hacker666/CVE-2026-23111) :  ![starts](https://img.shields.io/github/stars/Baba01hacker666/CVE-2026-23111.svg) ![forks](https://img.shields.io/github/forks/Baba01hacker666/CVE-2026-23111.svg)


## CVE-2026-20230
 Note: To exploit this vulnerability, the WebDialer service must be enabled. WebDialer is disabled by default.

- [https://github.com/W5M1n9/Cisco-Unified-Communications-Manager-Server-Side-Forgery-Request-Vulnerability-CVE-2026-20230](https://github.com/W5M1n9/Cisco-Unified-Communications-Manager-Server-Side-Forgery-Request-Vulnerability-CVE-2026-20230) :  ![starts](https://img.shields.io/github/stars/W5M1n9/Cisco-Unified-Communications-Manager-Server-Side-Forgery-Request-Vulnerability-CVE-2026-20230.svg) ![forks](https://img.shields.io/github/forks/W5M1n9/Cisco-Unified-Communications-Manager-Server-Side-Forgery-Request-Vulnerability-CVE-2026-20230.svg)


## CVE-2026-8181
 The Burst Statistics – Privacy-Friendly WordPress Analytics (Google Analytics Alternative) plugin for WordPress is vulnerable to Authentication Bypass in versions 3.4.0 to 3.4.1.1. This is due to incorrect return-value handling in the `is_mainwp_authenticated()` function when validating application passwords from the Authorization header. This makes it possible for unauthenticated attackers, with knowledge of an administrator username, to impersonate that administrator for the duration of the request by supplying any random Basic Authentication password achieving privilege escalation.

- [https://github.com/Squamity/CVE-2026-8181-PoC](https://github.com/Squamity/CVE-2026-8181-PoC) :  ![starts](https://img.shields.io/github/stars/Squamity/CVE-2026-8181-PoC.svg) ![forks](https://img.shields.io/github/forks/Squamity/CVE-2026-8181-PoC.svg)


## CVE-2026-7574
 Anthropic Claude Desktop Cowork VM image handling (confirmed across v1.1348.0 through v1.2278.0, including v1.1348.0, v1.1617.0, and v1.2278.0) validates only file presence and a version marker string before booting rootfs.img, but does not verify image content integrity at time-of-use. A local attacker with unprivileged code execution as the victim macOS user can modify the VM root filesystem image and have it trusted on subsequent Cowork VM boots, enabling persistent arbitrary code execution in the VM and access to host-mounted directories. The estimated CWE mapping is CWE-353 (Missing Support for Integrity Check).

- [https://github.com/0xBlackash/CVE-2026-7574](https://github.com/0xBlackash/CVE-2026-7574) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-7574.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-7574.svg)


## CVE-2026-5558
 A flaw has been found in PHPGurukul PHPGurukul Online Shopping Portal Project up to 2.1. Impacted is an unknown function of the file /pending-orders.php of the component Parameter Handler. This manipulation of the argument ID causes sql injection. The attack is possible to be carried out remotely. The exploit has been published and may be used.

- [https://github.com/mirackayikci/CVE-2026-55584](https://github.com/mirackayikci/CVE-2026-55584) :  ![starts](https://img.shields.io/github/stars/mirackayikci/CVE-2026-55584.svg) ![forks](https://img.shields.io/github/forks/mirackayikci/CVE-2026-55584.svg)


## CVE-2026-4253
 A security flaw has been discovered in Tenda AC8 16.03.50.11. This affects the function route_set_user_policy_rule of the file /cgi-bin/UploadCfg of the component Web Interface. The manipulation of the argument wans.policy.list1 results in os command injection. It is possible to launch the attack remotely. The exploit has been released to the public and may be used for attacks.

- [https://github.com/renzi25031469/CVE-2026-4253-Scanner](https://github.com/renzi25031469/CVE-2026-4253-Scanner) :  ![starts](https://img.shields.io/github/stars/renzi25031469/CVE-2026-4253-Scanner.svg) ![forks](https://img.shields.io/github/forks/renzi25031469/CVE-2026-4253-Scanner.svg)


## CVE-2026-3227
Successful exploitation allows an authenticated attacker to execute system commands with root privileges, leading to full device compromise.

- [https://github.com/do4choo/CVE-2026-3227](https://github.com/do4choo/CVE-2026-3227) :  ![starts](https://img.shields.io/github/stars/do4choo/CVE-2026-3227.svg) ![forks](https://img.shields.io/github/forks/do4choo/CVE-2026-3227.svg)


## CVE-2026-0091
 In multiple locations, there is a possible way to execute code in the launcher process due to an over-privileged shell user. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/canyie/TransitionPlayer](https://github.com/canyie/TransitionPlayer) :  ![starts](https://img.shields.io/github/stars/canyie/TransitionPlayer.svg) ![forks](https://img.shields.io/github/forks/canyie/TransitionPlayer.svg)


## CVE-2025-67038
 An issue was discovered in Lantronix EDS5000 2.1.0.0R3. The HTTP RPC module executes a shell command to write logs when user's authantication fails. The username is directly concatenated with the command without any sanitization. This allow attackers to inject arbitrary OS commands into the username parameter. Injected commands are executed with root privileges.

- [https://github.com/HORKimhab/CVE-2025-67038](https://github.com/HORKimhab/CVE-2025-67038) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2025-67038.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2025-67038.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-15x](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-15x) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-15x.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-15x.svg)


## CVE-2025-61155
 The GameDriverX64.sys kernel-mode anti-cheat driver (v7.23.4.7 and earlier) contains an access control vulnerability in one of its IOCTL handlers. A user-mode process can open a handle to the driver device and send specially crafted IOCTL requests. These requests are executed in kernel-mode context without proper authentication or access validation, allowing the attacker to terminate arbitrary processes, including critical system and security services, without requiring administrative privileges.

- [https://github.com/sys0xFF/CVE-2025-61155](https://github.com/sys0xFF/CVE-2025-61155) :  ![starts](https://img.shields.io/github/stars/sys0xFF/CVE-2025-61155.svg) ![forks](https://img.shields.io/github/forks/sys0xFF/CVE-2025-61155.svg)


## CVE-2025-8110
 Improper Symbolic link handling in the PutContents API in Gogs allows Local Execution of Code.

- [https://github.com/joaquinrrr/CVE-2025-8110](https://github.com/joaquinrrr/CVE-2025-8110) :  ![starts](https://img.shields.io/github/stars/joaquinrrr/CVE-2025-8110.svg) ![forks](https://img.shields.io/github/forks/joaquinrrr/CVE-2025-8110.svg)


## CVE-2025-4524
 The Madara – Responsive and modern WordPress theme for manga sites theme for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 2.2.2 via the 'template' parameter. This makes it possible for unauthenticated attackers to include and execute arbitrary files on the server, allowing the execution of any PHP code in those files. This can be used to bypass access controls, obtain sensitive data, or achieve code execution in cases where images and other “safe” file types can be uploaded and included.

- [https://github.com/CyruxSec/CVE-2025-4524](https://github.com/CyruxSec/CVE-2025-4524) :  ![starts](https://img.shields.io/github/stars/CyruxSec/CVE-2025-4524.svg) ![forks](https://img.shields.io/github/forks/CyruxSec/CVE-2025-4524.svg)


## CVE-2024-4367
 A type check was missing when handling fonts in PDF.js, which would allow arbitrary JavaScript execution in the PDF.js context. This vulnerability affects Firefox  126, Firefox ESR  115.11, and Thunderbird  115.11.

- [https://github.com/veronimo669/pdf.js-CVE-2024-4367](https://github.com/veronimo669/pdf.js-CVE-2024-4367) :  ![starts](https://img.shields.io/github/stars/veronimo669/pdf.js-CVE-2024-4367.svg) ![forks](https://img.shields.io/github/forks/veronimo669/pdf.js-CVE-2024-4367.svg)


## CVE-2023-48795
 The SSH transport protocol with certain OpenSSH extensions, found in OpenSSH before 9.6 and other products, allows remote attackers to bypass integrity checks such that some packets are omitted (from the extension negotiation message), and a client and server may consequently end up with a connection for which some security features have been downgraded or disabled, aka a Terrapin attack. This occurs because the SSH Binary Packet Protocol (BPP), implemented by these extensions, mishandles the handshake phase and mishandles use of sequence numbers. For example, there is an effective attack against SSH's use of ChaCha20-Poly1305 (and CBC with Encrypt-then-MAC). The bypass occurs in chacha20-poly1305@openssh.com and (if CBC is used) the -etm@openssh.com MAC algorithms. This also affects Maverick Synergy Java SSH API before 3.1.0-SNAPSHOT, Dropbear through 2022.83, Ssh before 5.1.1 in Erlang/OTP, PuTTY before 0.80, AsyncSSH before 2.14.2, golang.org/x/crypto before 0.17.0, libssh before 0.10.6, libssh2 through 1.11.0, Thorn Tech SFTP Gateway before 3.4.6, Tera Term before 5.1, Paramiko before 3.4.0, jsch before 0.2.15, SFTPGo before 2.5.6, Netgate pfSense Plus through 23.09.1, Netgate pfSense CE through 2.7.2, HPN-SSH through 18.2.0, ProFTPD before 1.3.8b (and before 1.3.9rc2), ORYX CycloneSSH before 2.3.4, NetSarang XShell 7 before Build 0144, CrushFTP before 10.6.0, ConnectBot SSH library before 2.2.22, Apache MINA sshd through 2.11.0, sshj through 0.37.0, TinySSH through 20230101, trilead-ssh2 6401, LANCOM LCOS and LANconfig, FileZilla before 3.66.4, Nova before 11.8, PKIX-SSH before 14.4, SecureCRT before 9.4.3, Transmit5 before 5.10.4, Win32-OpenSSH before 9.5.0.0p1-Beta, WinSCP before 6.2.2, Bitvise SSH Server before 9.32, Bitvise SSH Client before 9.33, KiTTY through 0.76.1.13, the net-ssh gem 7.2.0 for Ruby, the mscdex ssh2 module before 1.15.0 for Node.js, the thrussh library before 0.35.1 for Rust, and the Russh crate before 0.40.2 for Rust.

- [https://github.com/kabiri-labs/sshfinder](https://github.com/kabiri-labs/sshfinder) :  ![starts](https://img.shields.io/github/stars/kabiri-labs/sshfinder.svg) ![forks](https://img.shields.io/github/forks/kabiri-labs/sshfinder.svg)


## CVE-2014-6271
 GNU Bash through 4.3 processes trailing strings after function definitions in the values of environment variables, which allows remote attackers to execute arbitrary code via a crafted environment, as demonstrated by vectors involving the ForceCommand feature in OpenSSH sshd, the mod_cgi and mod_cgid modules in the Apache HTTP Server, scripts executed by unspecified DHCP clients, and other situations in which setting the environment occurs across a privilege boundary from Bash execution, aka "ShellShock."  NOTE: the original fix for this issue was incorrect; CVE-2014-7169 has been assigned to cover the vulnerability that is still present after the incorrect fix.

- [https://github.com/J0hnTh3Kn1ght/CVE-2014-6271](https://github.com/J0hnTh3Kn1ght/CVE-2014-6271) :  ![starts](https://img.shields.io/github/stars/J0hnTh3Kn1ght/CVE-2014-6271.svg) ![forks](https://img.shields.io/github/forks/J0hnTh3Kn1ght/CVE-2014-6271.svg)


## CVE-2007-2447
 The MS-RPC functionality in smbd in Samba 3.0.0 through 3.0.25rc3 allows remote attackers to execute arbitrary commands via shell metacharacters involving the (1) SamrChangePassword function, when the "username map script" smb.conf option is enabled, and allows remote authenticated users to execute commands via shell metacharacters involving other MS-RPC functions in the (2) remote printer and (3) file share management.

- [https://github.com/EthicalHackingLabs/metasploitable2-exploitation-metasploit](https://github.com/EthicalHackingLabs/metasploitable2-exploitation-metasploit) :  ![starts](https://img.shields.io/github/stars/EthicalHackingLabs/metasploitable2-exploitation-metasploit.svg) ![forks](https://img.shields.io/github/forks/EthicalHackingLabs/metasploitable2-exploitation-metasploit.svg)

