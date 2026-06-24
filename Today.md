# Update 2026-06-24
## CVE-2026-54806
 Unauthenticated PHP Object Injection in WP Activity Log = 5.6.3.1 versions.

- [https://github.com/joshuavanderpoll/CVE-2026-54806](https://github.com/joshuavanderpoll/CVE-2026-54806) :  ![starts](https://img.shields.io/github/stars/joshuavanderpoll/CVE-2026-54806.svg) ![forks](https://img.shields.io/github/forks/joshuavanderpoll/CVE-2026-54806.svg)


## CVE-2026-49772
This issue affects The Events Calendar: from 6.15.12 through 6.16.2.

- [https://github.com/joshuavanderpoll/CVE-2026-49772](https://github.com/joshuavanderpoll/CVE-2026-49772) :  ![starts](https://img.shields.io/github/stars/joshuavanderpoll/CVE-2026-49772.svg) ![forks](https://img.shields.io/github/forks/joshuavanderpoll/CVE-2026-49772.svg)


## CVE-2026-48908
 A vulnerability in SP Page Builder for Joomla allows unauthenticated users to upload arbitrary files, ultimately resulting in the upload and execution of PHP code.

- [https://github.com/papageo75/CVE-2026-48908-PoC](https://github.com/papageo75/CVE-2026-48908-PoC) :  ![starts](https://img.shields.io/github/stars/papageo75/CVE-2026-48908-PoC.svg) ![forks](https://img.shields.io/github/forks/papageo75/CVE-2026-48908-PoC.svg)


## CVE-2026-48907
 A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

- [https://github.com/0xgh057r3c0n/CVE-2026-48907](https://github.com/0xgh057r3c0n/CVE-2026-48907) :  ![starts](https://img.shields.io/github/stars/0xgh057r3c0n/CVE-2026-48907.svg) ![forks](https://img.shields.io/github/forks/0xgh057r3c0n/CVE-2026-48907.svg)


## CVE-2026-46300
bytes into @to's linear data rather than transferring frag descriptors.

- [https://github.com/azilRababe/CVE-2026-46300](https://github.com/azilRababe/CVE-2026-46300) :  ![starts](https://img.shields.io/github/stars/azilRababe/CVE-2026-46300.svg) ![forks](https://img.shields.io/github/forks/azilRababe/CVE-2026-46300.svg)


## CVE-2026-45034
 PhpSpreadsheet is a pure PHP library for reading and writing spreadsheet files. Prior to 1.30.5, CVE-2026-34084 was patched by the helper File::prohibitWrappers. The helper calls parse_url($filename, PHP_URL_SCHEME) and then checks is_string($scheme) && strlen($scheme)  1 to reject stream wrappers such as phar://, php://, data:// or expect://. The check is not equivalent to "does the path contain a wrapper". When the input has the form phar:///path/file.phar/inner with three or more slashes after the scheme, parse_url returns boolean false instead of returning the scheme string. The is_string($scheme) branch is therefore skipped, the helper returns without throwing, and the caller proceeds. PHP's stream layer, however, still treats phar:///... as a valid phar wrapper and opens the underlying phar file. The result is that IOFactory::load($attackerPath) walks past the patch and still touches the phar wrapper. On PHP 7.x, simply reaching the phar wrapper via is_file is enough for PHP to automatically deserialize the phar metadata, which in turn invokes the magic methods __wakeup and __destruct of an attacker controlled object and gives full RCE. On PHP 8.x, automatic metadata deserialization for plain file ops was removed, so the chain at the PhpSpreadsheet layer reduces to a phar wrapper file read primitive, and RCE only resurfaces if the downstream consumer ever calls Phar::getMetadata. This vulnerability is fixed in 1.30.5.

- [https://github.com/Cyber-DarkNay/CVE-2026-45034](https://github.com/Cyber-DarkNay/CVE-2026-45034) :  ![starts](https://img.shields.io/github/stars/Cyber-DarkNay/CVE-2026-45034.svg) ![forks](https://img.shields.io/github/forks/Cyber-DarkNay/CVE-2026-45034.svg)


## CVE-2026-42945
 NGINX Plus and NGINX Open Source have a vulnerability in the ngx_http_rewrite_module module. This vulnerability exists when the rewrite directive is followed by a rewrite, if, or set directive and an unnamed Perl-Compatible Regular Expression (PCRE) capture (for example, $1, $2) with a replacement string that includes a question mark (?). An unauthenticated attacker along with conditions beyond its control can exploit this vulnerability by sending crafted HTTP requests. This may cause a heap buffer overflow in the NGINX worker process leading to a restart. Additionally, attackers can execute code on systems with Address Space Layout Randomization (ASLR) disabled or when the attacker can bypass ASLR.  Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

- [https://github.com/azilRababe/CVE-2026-42945](https://github.com/azilRababe/CVE-2026-42945) :  ![starts](https://img.shields.io/github/stars/azilRababe/CVE-2026-42945.svg) ![forks](https://img.shields.io/github/forks/azilRababe/CVE-2026-42945.svg)


## CVE-2026-39338
 ChurchCRM is an open-source church management system. Prior to 7.1.0, a Blind Reflected Cross-Site Scripting vulnerability exists in the search parameter accepted by the ChurchCRM dashboard. The application fails to sanitize or encode user-supplied input prior to rendering it within the browser's DOM. Although the application ultimately returns an HTTP 500 error due to the malformed API request caused by the payload, the browser's JavaScript engine parses and executes the injected script tags before the error response is returned — resulting in successful code execution regardless of the server-side error. This vulnerability is fixed in 7.1.0.

- [https://github.com/HackinKraken/Security-Research-and-CVE](https://github.com/HackinKraken/Security-Research-and-CVE) :  ![starts](https://img.shields.io/github/stars/HackinKraken/Security-Research-and-CVE.svg) ![forks](https://img.shields.io/github/forks/HackinKraken/Security-Research-and-CVE.svg)


## CVE-2026-26030
 Semantic Kernel, Microsoft's semantic kernel Python SDK, has a remote code execution vulnerability in versions prior to 1.39.4, specifically within the `InMemoryVectorStore` filter functionality. The problem has been fixed in version `python-1.39.4`. Users should upgrade this version or higher. As a workaround, avoid using `InMemoryVectorStore` for production scenarios.

- [https://github.com/InertFluid/sk-cve-2026-26030-lab](https://github.com/InertFluid/sk-cve-2026-26030-lab) :  ![starts](https://img.shields.io/github/stars/InertFluid/sk-cve-2026-26030-lab.svg) ![forks](https://img.shields.io/github/forks/InertFluid/sk-cve-2026-26030-lab.svg)


## CVE-2026-25541
 Bytes is a utility library for working with bytes. From version 1.2.1 to before 1.11.1, Bytes is vulnerable to integer overflow in BytesMut::reserve. In the unique reclaim path of BytesMut::reserve, if the condition "v_capacity = new_cap + offset" uses an unchecked addition. When new_cap + offset overflows usize in release builds, this condition may incorrectly pass, causing self.cap to be set to a value that exceeds the actual allocated capacity. Subsequent APIs such as spare_capacity_mut() then trust this corrupted cap value and may create out-of-bounds slices, leading to UB. This behavior is observable in release builds (integer overflow wraps), whereas debug builds panic due to overflow checks. This issue has been patched in version 1.11.1.

- [https://github.com/hanyvert/cve-2026-25541-fuel-analysis](https://github.com/hanyvert/cve-2026-25541-fuel-analysis) :  ![starts](https://img.shields.io/github/stars/hanyvert/cve-2026-25541-fuel-analysis.svg) ![forks](https://img.shields.io/github/forks/hanyvert/cve-2026-25541-fuel-analysis.svg)


## CVE-2026-23744
 MCPJam inspector is the local-first development platform for MCP servers. Versions 1.4.2 and earlier are vulnerable to remote code execution (RCE) vulnerability, which allows an attacker to send a crafted HTTP request that triggers the installation of an MCP server, leading to RCE. Since MCPJam inspector by default listens on 0.0.0.0 instead of 127.0.0.1, an attacker can trigger the RCE remotely via a simple HTTP request. Version 1.4.3 contains a patch.

- [https://github.com/daemoncibsec/mcpExec](https://github.com/daemoncibsec/mcpExec) :  ![starts](https://img.shields.io/github/stars/daemoncibsec/mcpExec.svg) ![forks](https://img.shields.io/github/forks/daemoncibsec/mcpExec.svg)


## CVE-2026-21018
 Out-of-bounds write in SveService prior to SMR May-2026 Release 1 allows local privileged attackers to execute arbitrary code.

- [https://github.com/Filipemendonca1978/CVE-2026-21018](https://github.com/Filipemendonca1978/CVE-2026-21018) :  ![starts](https://img.shields.io/github/stars/Filipemendonca1978/CVE-2026-21018.svg) ![forks](https://img.shields.io/github/forks/Filipemendonca1978/CVE-2026-21018.svg)


## CVE-2026-20817
 Improper handling of insufficient permissions or privileges in Windows Error Reporting allows an authorized attacker to elevate privileges locally.

- [https://github.com/RDTUTORIAL/GhostUSB](https://github.com/RDTUTORIAL/GhostUSB) :  ![starts](https://img.shields.io/github/stars/RDTUTORIAL/GhostUSB.svg) ![forks](https://img.shields.io/github/forks/RDTUTORIAL/GhostUSB.svg)


## CVE-2026-4020
 The Gravity SMTP plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and including, 2.1.4. This is due to a REST API endpoint registered at /wp-json/gravitysmtp/v1/tests/mock-data with a permission_callback that unconditionally returns true, allowing any unauthenticated visitor to access it. When the ?page=gravitysmtp-settings query parameter is appended, the plugin's register_connector_data() method populates internal connector data, causing the endpoint to return approximately 365 KB of JSON containing the full System Report. This makes it possible for unauthenticated attackers to retrieve detailed system configuration data including PHP version, loaded extensions, web server version, document root path, database server type and version, WordPress version, all active plugins with versions, active theme, WordPress configuration details, database table names, and any API keys/tokens configured in the plugin.

- [https://github.com/HORKimhab/CVE-2026-4020](https://github.com/HORKimhab/CVE-2026-4020) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-4020.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-4020.svg)


## CVE-2026-3903
 The Modular DS: Monitor, update, and backup multiple websites plugin for WordPress is vulnerable to Cross-Site Request Forgery in all versions up to, and including, 2.5.1. This is due to missing nonce validation on the postConfirmOauth() function. This makes it possible for unauthenticated attackers to disconnect the plugin's OAuth/SSO connection via a forged request granted they can trick a site administrator into performing an action such as clicking on a link.

- [https://github.com/user6400/cve-2026-39031-lansweeper-lsrunase2-lsencrypt2](https://github.com/user6400/cve-2026-39031-lansweeper-lsrunase2-lsencrypt2) :  ![starts](https://img.shields.io/github/stars/user6400/cve-2026-39031-lansweeper-lsrunase2-lsencrypt2.svg) ![forks](https://img.shields.io/github/forks/user6400/cve-2026-39031-lansweeper-lsrunase2-lsencrypt2.svg)


## CVE-2026-2002
 The Forminator Forms – Contact Form, Payment Form & Custom Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the form_name parameter in all versions up to, and including, 1.50.2 due to insufficient input sanitization and output escaping. This makes it possible for authenticated attackers, with administrator-level access, to inject arbitrary web scripts in pages that will execute whenever a user accesses an injected page. The plugin allows admins to give form management permissions to lower level users, which could make this exploitable by users such as subscribers.

- [https://github.com/typedefabcd1234ntd/CVE-2026-2002-poc](https://github.com/typedefabcd1234ntd/CVE-2026-2002-poc) :  ![starts](https://img.shields.io/github/stars/typedefabcd1234ntd/CVE-2026-2002-poc.svg) ![forks](https://img.shields.io/github/forks/typedefabcd1234ntd/CVE-2026-2002-poc.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-monorepo-nextjs-yarn-workspaces](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-monorepo-nextjs-yarn-workspaces) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-monorepo-nextjs-yarn-workspaces.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-monorepo-nextjs-yarn-workspaces.svg)


## CVE-2025-48907
Impact: Successful exploitation of this vulnerability may affect availability.

- [https://github.com/0xgh057r3c0n/CVE-2026-48907](https://github.com/0xgh057r3c0n/CVE-2026-48907) :  ![starts](https://img.shields.io/github/stars/0xgh057r3c0n/CVE-2026-48907.svg) ![forks](https://img.shields.io/github/forks/0xgh057r3c0n/CVE-2026-48907.svg)


## CVE-2024-3094
Through a series of complex obfuscations, the liblzma build process extracts a prebuilt object file from a disguised test file existing in the source code, which is then used to modify specific functions in the liblzma code. This results in a modified liblzma library that can be used by any software linked against this library, intercepting and modifying the data interaction with this library.

- [https://github.com/Bryn018/Semantic-Backdoor-Detector](https://github.com/Bryn018/Semantic-Backdoor-Detector) :  ![starts](https://img.shields.io/github/stars/Bryn018/Semantic-Backdoor-Detector.svg) ![forks](https://img.shields.io/github/forks/Bryn018/Semantic-Backdoor-Detector.svg)


## CVE-2023-31290
 Trust Wallet Core before 3.1.1, as used in the Trust Wallet browser extension before 0.0.183, allows theft of funds because the entropy is 32 bits, as exploited in the wild in December 2022 and March 2023. This occurs because the mt19937 Mersenne Twister takes a single 32-bit value as an input seed, resulting in only four billion possible mnemonics. The affected versions of the browser extension are 0.0.172 through 0.0.182. To steal funds efficiently, an attacker can identify all Ethereum addresses created since the 0.0.172 release, and check whether they are Ethereum addresses that could have been created by this extension. To respond to the risk, affected users need to upgrade the product version and also move funds to a new wallet address.

- [https://github.com/ethicbrudhack/CVE-2023-31290-Scanner-](https://github.com/ethicbrudhack/CVE-2023-31290-Scanner-) :  ![starts](https://img.shields.io/github/stars/ethicbrudhack/CVE-2023-31290-Scanner-.svg) ![forks](https://img.shields.io/github/forks/ethicbrudhack/CVE-2023-31290-Scanner-.svg)


## CVE-2022-40769
 profanity through 1.60 has only four billion possible RNG initializations. Thus, attackers can recover private keys from Ethereum vanity addresses and steal cryptocurrency, as exploited in the wild in June 2022.

- [https://github.com/ethicbrudhack/CVE-2022-40769---Profanity](https://github.com/ethicbrudhack/CVE-2022-40769---Profanity) :  ![starts](https://img.shields.io/github/stars/ethicbrudhack/CVE-2022-40769---Profanity.svg) ![forks](https://img.shields.io/github/forks/ethicbrudhack/CVE-2022-40769---Profanity.svg)


## CVE-2021-41773
 A flaw was found in a change made to path normalization in Apache HTTP Server 2.4.49. An attacker could use a path traversal attack to map URLs to files outside the directories configured by Alias-like directives. If files outside of these directories are not protected by the usual default configuration "require all denied", these requests can succeed. If CGI scripts are also enabled for these aliased pathes, this could allow for remote code execution. This issue is known to be exploited in the wild. This issue only affects Apache 2.4.49 and not earlier versions. The fix in Apache HTTP Server 2.4.50 was found to be incomplete, see CVE-2021-42013.

- [https://github.com/Joapath/CVE-2021-41773](https://github.com/Joapath/CVE-2021-41773) :  ![starts](https://img.shields.io/github/stars/Joapath/CVE-2021-41773.svg) ![forks](https://img.shields.io/github/forks/Joapath/CVE-2021-41773.svg)


## CVE-2021-37840
 aaPanel through 6.8.12 allows Cross-Site WebSocket Hijacking (CSWH) involving OS commands within WebSocket messages at a ws:// URL for /webssh (the victim must have configured Terminal with at least one host). Successful exploitation depends on the browser used by a potential victim (e.g., exploitation can occur with Firefox but not Chrome).

- [https://github.com/EonSecurity/aapanel-ws-bypass](https://github.com/EonSecurity/aapanel-ws-bypass) :  ![starts](https://img.shields.io/github/stars/EonSecurity/aapanel-ws-bypass.svg) ![forks](https://img.shields.io/github/forks/EonSecurity/aapanel-ws-bypass.svg)


## CVE-2021-4034
 A local privilege escalation vulnerability was found on polkit's pkexec utility. The pkexec application is a setuid tool designed to allow unprivileged users to run commands as privileged users according predefined policies. The current version of pkexec doesn't handle the calling parameters count correctly and ends trying to execute environment variables as commands. An attacker can leverage this by crafting environment variables in such a way it'll induce pkexec to execute arbitrary code. When successfully executed the attack can cause a local privilege escalation given unprivileged users administrative rights on the target machine.

- [https://github.com/ropydev/CVE-2021-4034-PwnKit](https://github.com/ropydev/CVE-2021-4034-PwnKit) :  ![starts](https://img.shields.io/github/stars/ropydev/CVE-2021-4034-PwnKit.svg) ![forks](https://img.shields.io/github/forks/ropydev/CVE-2021-4034-PwnKit.svg)


## CVE-2021-3450
 The X509_V_FLAG_X509_STRICT flag enables additional security checks of the certificates present in a certificate chain. It is not set by default. Starting from OpenSSL version 1.1.1h a check to disallow certificates in the chain that have explicitly encoded elliptic curve parameters was added as an additional strict check. An error in the implementation of this check meant that the result of a previous check to confirm that certificates in the chain are valid CA certificates was overwritten. This effectively bypasses the check that non-CA certificates must not be able to issue other certificates. If a "purpose" has been configured then there is a subsequent opportunity for checks that the certificate is a valid CA. All of the named "purpose" values implemented in libcrypto perform this check. Therefore, where a purpose is set the certificate chain will still be rejected even when the strict flag has been used. A purpose is set by default in libssl client and server certificate verification routines, but it can be overridden or removed by an application. In order to be affected, an application must explicitly set the X509_V_FLAG_X509_STRICT verification flag and either not set a purpose for the certificate verification or, in the case of TLS client or server applications, override the default purpose. OpenSSL versions 1.1.1h and newer are affected by this issue. Users of these versions should upgrade to OpenSSL 1.1.1k. OpenSSL 1.0.2 is not impacted by this issue. Fixed in OpenSSL 1.1.1k (Affected 1.1.1h-1.1.1j).

- [https://github.com/dedellix/MUT-BC-SS-01](https://github.com/dedellix/MUT-BC-SS-01) :  ![starts](https://img.shields.io/github/stars/dedellix/MUT-BC-SS-01.svg) ![forks](https://img.shields.io/github/forks/dedellix/MUT-BC-SS-01.svg)


## CVE-2020-26233
 Git Credential Manager Core (GCM Core) is a secure Git credential helper built on .NET Core that runs on Windows and macOS. In Git Credential Manager Core before version 2.0.289, when recursively cloning a Git repository on Windows with submodules, Git will first clone the top-level repository and then recursively clone all submodules by starting new Git processes from the top-level working directory. If a malicious git.exe executable is present in the top-level repository then this binary will be started by Git Credential Manager Core when attempting to read configuration, and not git.exe as found on the %PATH%. This only affects GCM Core on Windows, not macOS or Linux-based distributions. GCM Core version 2.0.289 contains the fix for this vulnerability, and is available from the project's GitHub releases page. GCM Core 2.0.289 is also bundled in the latest Git for Windows release; version 2.29.2(3). As a workaround, users should avoid recursively cloning untrusted repositories with the --recurse-submodules option.

- [https://github.com/an1p3lg5/CVE-2020-26233](https://github.com/an1p3lg5/CVE-2020-26233) :  ![starts](https://img.shields.io/github/stars/an1p3lg5/CVE-2020-26233.svg) ![forks](https://img.shields.io/github/forks/an1p3lg5/CVE-2020-26233.svg)
- [https://github.com/whr819987540/test_CVE-2020-26233](https://github.com/whr819987540/test_CVE-2020-26233) :  ![starts](https://img.shields.io/github/stars/whr819987540/test_CVE-2020-26233.svg) ![forks](https://img.shields.io/github/forks/whr819987540/test_CVE-2020-26233.svg)


## CVE-2020-12928
 A vulnerability in a dynamically loaded AMD driver in AMD Ryzen Master V15 may allow any authenticated user to escalate privileges to NT authority system.

- [https://github.com/ch4rli3kop/CVE-2020-12928](https://github.com/ch4rli3kop/CVE-2020-12928) :  ![starts](https://img.shields.io/github/stars/ch4rli3kop/CVE-2020-12928.svg) ![forks](https://img.shields.io/github/forks/ch4rli3kop/CVE-2020-12928.svg)


## CVE-2020-11651
 An issue was discovered in SaltStack Salt before 2019.2.4 and 3000 before 3000.2. The salt-master process ClearFuncs class does not properly validate method calls. This allows a remote user to access some methods without authentication. These methods can be used to retrieve user tokens from the salt master and/or run arbitrary commands on salt minions.

- [https://github.com/s1lentf00thold/CVE-2020-11651-Poc](https://github.com/s1lentf00thold/CVE-2020-11651-Poc) :  ![starts](https://img.shields.io/github/stars/s1lentf00thold/CVE-2020-11651-Poc.svg) ![forks](https://img.shields.io/github/forks/s1lentf00thold/CVE-2020-11651-Poc.svg)

