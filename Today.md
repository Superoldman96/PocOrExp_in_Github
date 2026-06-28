# Update 2026-06-28
## CVE-2026-54807
 Unauthenticated Privilege Escalation in Registration Form for WooCommerce = 1.0.9 versions.

- [https://github.com/izxci/CVE-2026-54807](https://github.com/izxci/CVE-2026-54807) :  ![starts](https://img.shields.io/github/stars/izxci/CVE-2026-54807.svg) ![forks](https://img.shields.io/github/forks/izxci/CVE-2026-54807.svg)


## CVE-2026-52885
 Notepad++ is a free and open-source source code editor. Prior to 8.9.6.4, NppCommands.cpp checks the HMAC of the on-disk shortcuts.xml at the moment a user command fires (Time-of-Check). However, the command payload is taken from the in-memory _userCommands vector, which is populated at application startup and never re-synchronized with the on-disk file (Time-of-Use). Swapping shortcuts.xml between startup and command execution causes the HMAC check to validate a clean file while a malicious command runs. An attacker with write access to shortcuts.xml places a malicious version on disk before launch, then immediately restores the legitimate file. The HMAC check at execution time validates the restored legitimate file (check passes), while the malicious payload executes from memory. This vulnerability is fixed in 8.9.6.4.

- [https://github.com/v3s9er/CVE-2026-52885](https://github.com/v3s9er/CVE-2026-52885) :  ![starts](https://img.shields.io/github/stars/v3s9er/CVE-2026-52885.svg) ![forks](https://img.shields.io/github/forks/v3s9er/CVE-2026-52885.svg)


## CVE-2026-48800
 Notepad++ is a free and open-source source code editor. Prior to 8.9.6.1, the Command tag text content inside UserDefinedCommands in shortcuts.xml is read by NppXml::value(aNode) (Parameters.cpp:3658) in the feedUserCmds() function and stored in UserCommand._cmd without any validation. When the user clicks the corresponding entry in the Run menu, NppCommands.cpp:4264 creates a Command object with string2wstring(ucmd.getCmd()) and calls run(), which invokes ShellExecute (RunDlg.cpp:221) with the attacker-controlled string as the executable path. The injected command appears as a normal menu item in the Run menu, making it a viable persistence mechanism.  This vulnerability is fixed in 8.9.6.1.

- [https://github.com/atiilla/Notepad-8.9.6-PoC](https://github.com/atiilla/Notepad-8.9.6-PoC) :  ![starts](https://img.shields.io/github/stars/atiilla/Notepad-8.9.6-PoC.svg) ![forks](https://img.shields.io/github/forks/atiilla/Notepad-8.9.6-PoC.svg)
- [https://github.com/kavin-jindal/CVE-2026-48800-PoC](https://github.com/kavin-jindal/CVE-2026-48800-PoC) :  ![starts](https://img.shields.io/github/stars/kavin-jindal/CVE-2026-48800-PoC.svg) ![forks](https://img.shields.io/github/forks/kavin-jindal/CVE-2026-48800-PoC.svg)


## CVE-2026-48778
 Notepad++ is a free and open-source source code editor. Prior to 8.9.6.1, the GUIConfig name="commandLineInterpreter" tag in config.xml is read by NppXml::value() (Parameters.cpp:6430) and stored in _nppGUI._commandLineInterpreter without any validation, whitelist, or digital signature check. When the user triggers IDM_FILE_OPEN_CMD (File → Open Containing Folder → cmd), NppCommands.cpp:228 creates a Command object with this value and calls run(), which invokes ShellExecute (RunDlg.cpp:221) with the attacker-controlled string as the executable path. This vulnerability is fixed in 8.9.6.1.

- [https://github.com/XK3NF4/CVE-2026-48778](https://github.com/XK3NF4/CVE-2026-48778) :  ![starts](https://img.shields.io/github/stars/XK3NF4/CVE-2026-48778.svg) ![forks](https://img.shields.io/github/forks/XK3NF4/CVE-2026-48778.svg)
- [https://github.com/atiilla/Notepad-8.9.6-PoC](https://github.com/atiilla/Notepad-8.9.6-PoC) :  ![starts](https://img.shields.io/github/stars/atiilla/Notepad-8.9.6-PoC.svg) ![forks](https://img.shields.io/github/forks/atiilla/Notepad-8.9.6-PoC.svg)
- [https://github.com/kavin-jindal/CVE-2026-48778-PoC](https://github.com/kavin-jindal/CVE-2026-48778-PoC) :  ![starts](https://img.shields.io/github/stars/kavin-jindal/CVE-2026-48778-PoC.svg) ![forks](https://img.shields.io/github/forks/kavin-jindal/CVE-2026-48778-PoC.svg)


## CVE-2026-48770
 Notepad++ is a free and open-source source code editor. Prior to 8.9.6.1, a local process in the same interactive Windows session can send a malformed WM_COPYDATA message to Notepad++ using the COPYDATA_FULL_CMDLINE path. The handler appears to process COPYDATASTRUCT.lpData as an unbounded NUL-terminated wchar_t* instead of enforcing COPYDATASTRUCT.cbData. This vulnerability is fixed in 8.9.6.1.

- [https://github.com/atiilla/Notepad-8.9.6-PoC](https://github.com/atiilla/Notepad-8.9.6-PoC) :  ![starts](https://img.shields.io/github/stars/atiilla/Notepad-8.9.6-PoC.svg) ![forks](https://img.shields.io/github/forks/atiilla/Notepad-8.9.6-PoC.svg)


## CVE-2026-46558
 Plane is an open-source project management tool. Prior to version 1.3.1, there is a cross-workspace asset authorization bypass lets any authenticated user read, copy, delete, and overwrite assets in other Plane workspaces. This issue has been patched in version 1.3.1.

- [https://github.com/0xmrma/CVE-2026-46558](https://github.com/0xmrma/CVE-2026-46558) :  ![starts](https://img.shields.io/github/stars/0xmrma/CVE-2026-46558.svg) ![forks](https://img.shields.io/github/forks/0xmrma/CVE-2026-46558.svg)


## CVE-2026-46331
offset_valid() against INT_MIN, where negation is undefined.

- [https://github.com/0xBlackash/CVE-2026-46331](https://github.com/0xBlackash/CVE-2026-46331) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-46331.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-46331.svg)


## CVE-2026-44788
 SharpCompress is a fully managed C# library to deal with many compression types and formats. In 0.47.4 and earlier, a path traversal vulnerability in IArchive.WriteToDirectory() allows a malicious archive to create directories outside the intended extraction root. For TAR archives, this can be escalated to arbitrary file writes by chaining with a symlink entry, giving a full write primitive on the target filesystem subject to the permissions of the running process.

- [https://github.com/e-corp-demo/CVE-2026-44788](https://github.com/e-corp-demo/CVE-2026-44788) :  ![starts](https://img.shields.io/github/stars/e-corp-demo/CVE-2026-44788.svg) ![forks](https://img.shields.io/github/forks/e-corp-demo/CVE-2026-44788.svg)


## CVE-2026-43503
so segments drawing frags from frag_list members carry the marker.

- [https://github.com/sec0x/CVE-2026-43503](https://github.com/sec0x/CVE-2026-43503) :  ![starts](https://img.shields.io/github/stars/sec0x/CVE-2026-43503.svg) ![forks](https://img.shields.io/github/forks/sec0x/CVE-2026-43503.svg)
- [https://github.com/aexdyhaxor/CVE-2026-43503-DirtyClone](https://github.com/aexdyhaxor/CVE-2026-43503-DirtyClone) :  ![starts](https://img.shields.io/github/stars/aexdyhaxor/CVE-2026-43503-DirtyClone.svg) ![forks](https://img.shields.io/github/forks/aexdyhaxor/CVE-2026-43503-DirtyClone.svg)


## CVE-2026-42089
 Yeoman Environment provides an API to discover, create, and run generators, and to configure where and how a generator is resolved. Versions 2.9.0 through 6.0.0 install missing local generator packages from caller-supplied package names without user confirmation. In downstream consumers that pass attacker-controlled project configuration into this path, this can result in arbitrary package installation and code execution during CLI bootstrap. The vulnerable method is installLocalGenerators(), which calls repository.install() directly without prompting the user. This issue has been fixed in version 6.0.0.

- [https://github.com/0xmrma/CVE-2026-42089](https://github.com/0xmrma/CVE-2026-42089) :  ![starts](https://img.shields.io/github/stars/0xmrma/CVE-2026-42089.svg) ![forks](https://img.shields.io/github/forks/0xmrma/CVE-2026-42089.svg)


## CVE-2026-39938
 Cacti is an open source performance and fault management framework. Versions 1.2.30 and prior have unauthenticated LFI through graph_theme and rrdtool IPC serialization hardening. This issue has been resolved in version 1.2.31.

- [https://github.com/Polosss/By-Poloss..-..CVE-2026-39938](https://github.com/Polosss/By-Poloss..-..CVE-2026-39938) :  ![starts](https://img.shields.io/github/stars/Polosss/By-Poloss..-..CVE-2026-39938.svg) ![forks](https://img.shields.io/github/forks/Polosss/By-Poloss..-..CVE-2026-39938.svg)


## CVE-2026-39031
 Lansweeper lsrunase 2.0 and lsencrypt 2.0 use RC4 encryption with a hardcoded 142-byte static key array to encrypt credentials. An 8-character prefix is stored in cleartext alongside the ciphertext. This allows an attacker with local access to recover any encrypted password to plaintext using a single SHA-1 hash and RC4 decryption operation, with no brute force required.

- [https://github.com/user6400/cve-2026-39031-lansweeper-lsrunase2-lsencrypt2](https://github.com/user6400/cve-2026-39031-lansweeper-lsrunase2-lsencrypt2) :  ![starts](https://img.shields.io/github/stars/user6400/cve-2026-39031-lansweeper-lsrunase2-lsencrypt2.svg) ![forks](https://img.shields.io/github/forks/user6400/cve-2026-39031-lansweeper-lsrunase2-lsencrypt2.svg)


## CVE-2026-35273
 Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Updates Environment Management). Supported versions that are affected are 8.61 and 8.62. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise PeopleSoft Enterprise PeopleTools. Successful attacks of this vulnerability can result in takeover of PeopleSoft Enterprise PeopleTools. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

- [https://github.com/12hrformat/CVE-2026-35273-POC](https://github.com/12hrformat/CVE-2026-35273-POC) :  ![starts](https://img.shields.io/github/stars/12hrformat/CVE-2026-35273-POC.svg) ![forks](https://img.shields.io/github/forks/12hrformat/CVE-2026-35273-POC.svg)


## CVE-2026-34213
 Docmost is open-source collaborative wiki and documentation software. Starting in version 0.3.0 and prior to version 0.71.0, improper authorization in Docmost allows a low-privileged authenticated user to overwrite another page's attachment within the same workspace by supplying a victim `attachmentId` to `POST /api/files/upload`. This is a remote integrity issue requiring no victim interaction. Version 0.71.0 contains a patch.

- [https://github.com/0xmrma/CVE-2026-34213](https://github.com/0xmrma/CVE-2026-34213) :  ![starts](https://img.shields.io/github/stars/0xmrma/CVE-2026-34213.svg) ![forks](https://img.shields.io/github/forks/0xmrma/CVE-2026-34213.svg)


## CVE-2026-34212
 Docmost is open-source collaborative wiki and documentation software. In versions prior to 0.71.0, improper neutralization of attachment URLs in Docmost allows a low-privileged authenticated user to store a malicious `javascript:` URL inside an attachment node in page content. When another user views the page and activates the attachment link/icon, attacker-controlled JavaScript executes in the context of the Docmost origin. Version 0.71.0 patches the issue.

- [https://github.com/0xmrma/CVE-2026-34212](https://github.com/0xmrma/CVE-2026-34212) :  ![starts](https://img.shields.io/github/stars/0xmrma/CVE-2026-34212.svg) ![forks](https://img.shields.io/github/forks/0xmrma/CVE-2026-34212.svg)


## CVE-2026-34207
 TypeBot is a chatbot builder tool. In versions prior to 3.16.0, SSRF protection for Webhook / HTTP Request blocks validates only the URL string, blocked hostname literals, and literal IP formats. It does not resolve DNS before allowing the request. As a result, a hostname such as ssrf-repro.example that resolves to 127.0.0.1, 169.254.169.254, or RFC1918/private space passes validation and is later fetched by the backend HTTP client. This enables server-side request forgery to loopback, cloud metadata, and private network targets. This issue has been resolved in version 3.16.0.

- [https://github.com/0xmrma/CVE-2026-34207](https://github.com/0xmrma/CVE-2026-34207) :  ![starts](https://img.shields.io/github/stars/0xmrma/CVE-2026-34207.svg) ![forks](https://img.shields.io/github/forks/0xmrma/CVE-2026-34207.svg)


## CVE-2026-33146
 Docmost is open-source collaborative wiki and documentation software. An authorization bypass vulnerability in versions 0.70.0 through 0.70.2 exposes restricted child page titles and text snippets through the public search endpoint (`POST /api/search/share-search`) for publicly shared content. This flaw allows unauthenticated users to enumerate and retrieve content that should remain hidden from public share viewers, leading to a confidentiality breach. Version 0.70.3 contains a patch.

- [https://github.com/0xmrma/CVE-2026-33146](https://github.com/0xmrma/CVE-2026-33146) :  ![starts](https://img.shields.io/github/stars/0xmrma/CVE-2026-33146.svg) ![forks](https://img.shields.io/github/forks/0xmrma/CVE-2026-33146.svg)


## CVE-2026-26980
 Ghost is a Node.js content management system. Versions 3.24.0 through 6.19.0 allow unauthenticated attackers to perform arbitrary reads from the database. This issue has been fixed in version 6.19.1.

- [https://github.com/gagaltotal/CVE-2026-26980-Ghost-CMS-Api](https://github.com/gagaltotal/CVE-2026-26980-Ghost-CMS-Api) :  ![starts](https://img.shields.io/github/stars/gagaltotal/CVE-2026-26980-Ghost-CMS-Api.svg) ![forks](https://img.shields.io/github/forks/gagaltotal/CVE-2026-26980-Ghost-CMS-Api.svg)
- [https://github.com/n0bitaemon/CVE-2026-26980-PoC](https://github.com/n0bitaemon/CVE-2026-26980-PoC) :  ![starts](https://img.shields.io/github/stars/n0bitaemon/CVE-2026-26980-PoC.svg) ![forks](https://img.shields.io/github/forks/n0bitaemon/CVE-2026-26980-PoC.svg)


## CVE-2026-24207
 NVIDIA Triton Inference Server contains a vulnerability where an attacker could cause an authentication bypass. A successful exploit of this vulnerability might lead to code execution, escalation of privileges, data tampering, denial of service, or information disclosure.

- [https://github.com/offseckit/CVE-2026-24207](https://github.com/offseckit/CVE-2026-24207) :  ![starts](https://img.shields.io/github/stars/offseckit/CVE-2026-24207.svg) ![forks](https://img.shields.io/github/forks/offseckit/CVE-2026-24207.svg)


## CVE-2026-24206
 NVIDIA Triton Inference Server contains a vulnerability where an attacker could cause an authentication bypass. A successful exploit of this vulnerability might lead to escalation of privileges, denial of service, or information disclosure.

- [https://github.com/offseckit/CVE-2026-24207](https://github.com/offseckit/CVE-2026-24207) :  ![starts](https://img.shields.io/github/stars/offseckit/CVE-2026-24207.svg) ![forks](https://img.shields.io/github/forks/offseckit/CVE-2026-24207.svg)


## CVE-2026-20253
 In Splunk Enterprise 10.2 versions below 10.2.4 and 10 versions below 10.0.7, an unauthenticated user could create or truncate arbitrary files through a PostgreSQL sidecar service endpoint. The vulnerability exists because the PostgreSQL sidecar service endpoint lacks authentication controls, allowing any network-reachable user to invoke file operations without credentials. Splunk Enterprise versions 9.4 and earlier are not affected. If you cannot immediately upgrade to a fixed version, you can mitigate this vulnerability by disabling the PostgreSQL sidecar service.

- [https://github.com/fevar54/CVE-2026-20253-Splunk-Enterprise-Pre-Auth-RCE-](https://github.com/fevar54/CVE-2026-20253-Splunk-Enterprise-Pre-Auth-RCE-) :  ![starts](https://img.shields.io/github/stars/fevar54/CVE-2026-20253-Splunk-Enterprise-Pre-Auth-RCE-.svg) ![forks](https://img.shields.io/github/forks/fevar54/CVE-2026-20253-Splunk-Enterprise-Pre-Auth-RCE-.svg)


## CVE-2026-20251
 In Splunk Enterprise versions below 10.2.4, 10.0.7, 9.4.12, and 9.3.13, Splunk Cloud Platform versions below 10.3.2512.12, 10.2.2510.14, 10.1.2507.22, and 9.3.2411.132, and Splunk Secure Gateway versions below 3.10.6, 3.9.20, and 3.8.67, a low-privileged user that does not hold the 'admin' or 'power' Splunk roles could perform a Remote Code Execution (RCE) through the Splunk Secure Gateway app.brbrThe Remote Code Execution is possible because of unsafe deserialization of App Key Value Store (KV Store) data through the ‘jsonpickle’ Python library, which reconstructs arbitrary Python objects from specially crafted JavaScript Object Notation (JSON) without adequate validation.

- [https://github.com/reactivezero/CVE-2026-20251](https://github.com/reactivezero/CVE-2026-20251) :  ![starts](https://img.shields.io/github/stars/reactivezero/CVE-2026-20251.svg) ![forks](https://img.shields.io/github/forks/reactivezero/CVE-2026-20251.svg)


## CVE-2026-12416
 The Invoice Generator plugin for WordPress is vulnerable to Account Takeover via Password Reset in all versions up to, and including, 1.0.0. This is due to the `pravel_invoice_change_password()` function being registered as a nopriv AJAX handler with no nonce verification and no authorization check, and performing a loose equality comparison between the supplied `reset_activation_code` POST parameter and the target user's stored `forgot_email` user meta — a check that trivially evaluates to true (`'' == ''`) for any user who has never initiated a forgot-password request, which applies to administrators under normal conditions. This makes it possible for unauthenticated attackers to supply an arbitrary user ID via the `reset_user_id` POST parameter, bypass the activation code check entirely by omitting `reset_activation_code`, and set the target account's password to an attacker-chosen value, enabling full takeover of any account on the site, including administrator accounts.

- [https://github.com/xxconi/CVE-2026-12415-or-CVE-2026-12416.py](https://github.com/xxconi/CVE-2026-12415-or-CVE-2026-12416.py) :  ![starts](https://img.shields.io/github/stars/xxconi/CVE-2026-12415-or-CVE-2026-12416.py.svg) ![forks](https://img.shields.io/github/forks/xxconi/CVE-2026-12415-or-CVE-2026-12416.py.svg)


## CVE-2026-8461
This issue affects FFmpeg before version 8.1.2.

- [https://github.com/0xBlackash/CVE-2026-8461](https://github.com/0xBlackash/CVE-2026-8461) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-8461.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-8461.svg)


## CVE-2026-8380
 The Frontend File Manager Plugin WordPress plugin through 23.6 does not properly verify ownership of every targeted post before permanent deletion, allowing authenticated users with author-level access and above to permanently delete arbitrary posts and pages. When the Frontend File Manager Plugin WordPress plugin through 23.6's "Allow guest uploads" setting is enabled by an administrator, the same deletion primitive becomes reachable by unauthenticated users.

- [https://github.com/tiagob0b/CVE-2026-8380](https://github.com/tiagob0b/CVE-2026-8380) :  ![starts](https://img.shields.io/github/stars/tiagob0b/CVE-2026-8380.svg) ![forks](https://img.shields.io/github/forks/tiagob0b/CVE-2026-8380.svg)


## CVE-2026-4580
 A security flaw has been discovered in code-projects Simple Laundry System 1.0. This impacts an unknown function of the file /checkupdatestatus.php of the component Parameters Handler. The manipulation of the argument serviceId results in sql injection. The attack can be executed remotely. The exploit has been released to the public and may be used for attacks.

- [https://github.com/0xmrma/CVE-2026-45806](https://github.com/0xmrma/CVE-2026-45806) :  ![starts](https://img.shields.io/github/stars/0xmrma/CVE-2026-45806.svg) ![forks](https://img.shields.io/github/forks/0xmrma/CVE-2026-45806.svg)


## CVE-2026-0828
 Kernel driver ProcessMonitorDriver.sys in Safetica's endpoint client x64 , versions 10.5.75.0 and 11.11.4.0, allows unprivileged user to abuse IOCTL path and terminate protected system processes.

- [https://github.com/ANYLNK/STProcessMonitorBYOVD](https://github.com/ANYLNK/STProcessMonitorBYOVD) :  ![starts](https://img.shields.io/github/stars/ANYLNK/STProcessMonitorBYOVD.svg) ![forks](https://img.shields.io/github/forks/ANYLNK/STProcessMonitorBYOVD.svg)
- [https://github.com/DeathShotXD/0xKern3lCrush](https://github.com/DeathShotXD/0xKern3lCrush) :  ![starts](https://img.shields.io/github/stars/DeathShotXD/0xKern3lCrush.svg) ![forks](https://img.shields.io/github/forks/DeathShotXD/0xKern3lCrush.svg)
- [https://github.com/oxfemale/KillChain](https://github.com/oxfemale/KillChain) :  ![starts](https://img.shields.io/github/stars/oxfemale/KillChain.svg) ![forks](https://img.shields.io/github/forks/oxfemale/KillChain.svg)
- [https://github.com/I3r1h0n/Sigurd](https://github.com/I3r1h0n/Sigurd) :  ![starts](https://img.shields.io/github/stars/I3r1h0n/Sigurd.svg) ![forks](https://img.shields.io/github/forks/I3r1h0n/Sigurd.svg)
- [https://github.com/KOSEC-LLC/BYOVD-Research](https://github.com/KOSEC-LLC/BYOVD-Research) :  ![starts](https://img.shields.io/github/stars/KOSEC-LLC/BYOVD-Research.svg) ![forks](https://img.shields.io/github/forks/KOSEC-LLC/BYOVD-Research.svg)
- [https://github.com/mein-0/cve-2026-0828](https://github.com/mein-0/cve-2026-0828) :  ![starts](https://img.shields.io/github/stars/mein-0/cve-2026-0828.svg) ![forks](https://img.shields.io/github/forks/mein-0/cve-2026-0828.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x.svg)


## CVE-2025-58434
 Flowise is a drag & drop user interface to build a customized large language model flow. In version 3.0.5 and earlier, the `forgot-password` endpoint in Flowise returns sensitive information including a valid password reset `tempToken` without authentication or verification. This enables any attacker to generate a reset token for arbitrary users and directly reset their password, leading to a complete account takeover (ATO). This vulnerability applies to both the cloud service (`cloud.flowiseai.com`) and self-hosted/local Flowise deployments that expose the same API. Commit 9e178d68873eb876073846433a596590d3d9c863 in version 3.0.6 secures password reset endpoints. Several recommended remediation steps are available. Do not return reset tokens or sensitive account details in API responses. Tokens must only be delivered securely via the registered email channel. Ensure `forgot-password` responds with a generic success message regardless of input, to avoid user enumeration. Require strong validation of the `tempToken` (e.g., single-use, short expiry, tied to request origin, validated against email delivery). Apply the same fixes to both cloud and self-hosted/local deployments. Log and monitor password reset requests for suspicious activity. Consider multi-factor verification for sensitive accounts.

- [https://github.com/00lucasm/CVE-2025-58434-Flowiseai-Auth-Bypass-PoC](https://github.com/00lucasm/CVE-2025-58434-Flowiseai-Auth-Bypass-PoC) :  ![starts](https://img.shields.io/github/stars/00lucasm/CVE-2025-58434-Flowiseai-Auth-Bypass-PoC.svg) ![forks](https://img.shields.io/github/forks/00lucasm/CVE-2025-58434-Flowiseai-Auth-Bypass-PoC.svg)


## CVE-2025-54352
 WordPress 3.5 through 6.8.2 allows remote attackers to guess titles of private and draft posts via pingback.ping XML-RPC requests. NOTE: the Supplier is not changing this behavior.

- [https://github.com/mufasa-noir/XML-RPC-Pingback-Vulnerability](https://github.com/mufasa-noir/XML-RPC-Pingback-Vulnerability) :  ![starts](https://img.shields.io/github/stars/mufasa-noir/XML-RPC-Pingback-Vulnerability.svg) ![forks](https://img.shields.io/github/forks/mufasa-noir/XML-RPC-Pingback-Vulnerability.svg)


## CVE-2025-8088
     from ESET.

- [https://github.com/Lewis-Ricardo/Amaranth-Project](https://github.com/Lewis-Ricardo/Amaranth-Project) :  ![starts](https://img.shields.io/github/stars/Lewis-Ricardo/Amaranth-Project.svg) ![forks](https://img.shields.io/github/forks/Lewis-Ricardo/Amaranth-Project.svg)


## CVE-2020-0796
 A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 3.1.1 (SMBv3) protocol handles certain requests, aka 'Windows SMBv3 Client/Server Remote Code Execution Vulnerability'.

- [https://github.com/p4ncontomat3/smbghost](https://github.com/p4ncontomat3/smbghost) :  ![starts](https://img.shields.io/github/stars/p4ncontomat3/smbghost.svg) ![forks](https://img.shields.io/github/forks/p4ncontomat3/smbghost.svg)


## CVE-2016-5195
 Race condition in mm/gup.c in the Linux kernel 2.x through 4.x before 4.8.3 allows local users to gain privileges by leveraging incorrect handling of a copy-on-write (COW) feature to write to a read-only memory mapping, as exploited in the wild in October 2016, aka "Dirty COW."

- [https://github.com/gogooma125732/CVE-2016-5195](https://github.com/gogooma125732/CVE-2016-5195) :  ![starts](https://img.shields.io/github/stars/gogooma125732/CVE-2016-5195.svg) ![forks](https://img.shields.io/github/forks/gogooma125732/CVE-2016-5195.svg)


## CVE-2010-0219
 Apache Axis2, as used in dswsbobje.war in SAP BusinessObjects Enterprise XI 3.2, CA ARCserve D2D r15, and other products, has a default password of axis2 for the admin account, which makes it easier for remote attackers to execute arbitrary code by uploading a crafted web service.

- [https://github.com/vvts-alpha/CVE-2010-0219](https://github.com/vvts-alpha/CVE-2010-0219) :  ![starts](https://img.shields.io/github/stars/vvts-alpha/CVE-2010-0219.svg) ![forks](https://img.shields.io/github/forks/vvts-alpha/CVE-2010-0219.svg)

