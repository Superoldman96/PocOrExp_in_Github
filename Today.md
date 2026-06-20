# Update 2026-06-20
## CVE-2026-54420
 LiteSpeed cPanel plugin before 2.4.8 (as distributed in LiteSpeed WHM PlugIn before 5.3.2.0) mishandles symlinks provided by a user with FTP or web shell access on a shared hosting server running CloudLinux/CageFS, as exploited in the wild in May 2026.

- [https://github.com/fevar54/CVE-2026-54420-LiteSpeed-Symlink-Exploit](https://github.com/fevar54/CVE-2026-54420-LiteSpeed-Symlink-Exploit) :  ![starts](https://img.shields.io/github/stars/fevar54/CVE-2026-54420-LiteSpeed-Symlink-Exploit.svg) ![forks](https://img.shields.io/github/forks/fevar54/CVE-2026-54420-LiteSpeed-Symlink-Exploit.svg)


## CVE-2026-50752
 A weakness in the certificate validation logic of the deprecated IKEv1 key exchange may allow an unauthenticated attacker positioned as a man-in-the-middle to bypass certificate validation in VPN site-to-site connections that use certificate-based authentication. Successful exploitation could allow interception or modification of traffic traversing the VPN tunnel.

- [https://github.com/WadesWeaponShed/CheckPoint-CVE-Webscanner](https://github.com/WadesWeaponShed/CheckPoint-CVE-Webscanner) :  ![starts](https://img.shields.io/github/stars/WadesWeaponShed/CheckPoint-CVE-Webscanner.svg) ![forks](https://img.shields.io/github/forks/WadesWeaponShed/CheckPoint-CVE-Webscanner.svg)


## CVE-2026-50751
 A logic flow weakness in Remote Access and Mobile Access certificate validation in deprecated IKEv1 key exchange allows an unauthenticated remote attacker to bypass user authentication and establish a remote access VPN connection without a valid user password.

- [https://github.com/WadesWeaponShed/CheckPoint-CVE-Webscanner](https://github.com/WadesWeaponShed/CheckPoint-CVE-Webscanner) :  ![starts](https://img.shields.io/github/stars/WadesWeaponShed/CheckPoint-CVE-Webscanner.svg) ![forks](https://img.shields.io/github/forks/WadesWeaponShed/CheckPoint-CVE-Webscanner.svg)


## CVE-2026-50656
 Microsoft is aware of an elevation of privilege in the Microsoft Malware Protection Engine in Microsoft Defender publicly referred to as &quot;RoguePlanet &quot;. We are working to provide a high quality security update that addresses this vulnerability. We will provide information in this CVE when the update is available.

- [https://github.com/0xBlackash/CVE-2026-50656](https://github.com/0xBlackash/CVE-2026-50656) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-50656.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-50656.svg)


## CVE-2026-49975
This issue affects Apache HTTP Server: from 2.4.17 through 2.4.67.

- [https://github.com/0xc03307b/CVE-2026-49975](https://github.com/0xc03307b/CVE-2026-49975) :  ![starts](https://img.shields.io/github/stars/0xc03307b/CVE-2026-49975.svg) ![forks](https://img.shields.io/github/forks/0xc03307b/CVE-2026-49975.svg)


## CVE-2026-48907
 A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

- [https://github.com/g0thamRabb1t/joomla-jce-cve-2026-48907-detection](https://github.com/g0thamRabb1t/joomla-jce-cve-2026-48907-detection) :  ![starts](https://img.shields.io/github/stars/g0thamRabb1t/joomla-jce-cve-2026-48907-detection.svg) ![forks](https://img.shields.io/github/forks/g0thamRabb1t/joomla-jce-cve-2026-48907-detection.svg)


## CVE-2026-46368
 luci-app-https-dns-proxy through 2025.12.29-5 — an optional LuCI web UI add-on for the https-dns-proxy package, distributed through the OpenWrt community packages feed and not installed by default — contains a command injection vulnerability in the setInitAction function. An authenticated user holding the luci.https-dns-proxy ACL permission can inject shell metacharacters through the 'name' parameter of a ubus RPC call to luci.https-dns-proxy setInitAction, resulting in arbitrary command execution as root on the underlying device. Core OpenWrt is not affected; only installations that have opted in to the luci-app-https-dns-proxy package are vulnerable.

- [https://github.com/iwallplace/CVE-2026-46368-OpenWrt-Exploit](https://github.com/iwallplace/CVE-2026-46368-OpenWrt-Exploit) :  ![starts](https://img.shields.io/github/stars/iwallplace/CVE-2026-46368-OpenWrt-Exploit.svg) ![forks](https://img.shields.io/github/forks/iwallplace/CVE-2026-46368-OpenWrt-Exploit.svg)


## CVE-2026-46215
v2: cleanups of error paths

- [https://github.com/0xCyberstan/CVE-2026-46215-POC](https://github.com/0xCyberstan/CVE-2026-46215-POC) :  ![starts](https://img.shields.io/github/stars/0xCyberstan/CVE-2026-46215-POC.svg) ![forks](https://img.shields.io/github/forks/0xCyberstan/CVE-2026-46215-POC.svg)


## CVE-2026-44963
 A vulnerability allowing remote code execution (RCE) on the Backup Server by an authenticated domain user.

- [https://github.com/SentinelXofficial/CVE-2026-44963](https://github.com/SentinelXofficial/CVE-2026-44963) :  ![starts](https://img.shields.io/github/stars/SentinelXofficial/CVE-2026-44963.svg) ![forks](https://img.shields.io/github/forks/SentinelXofficial/CVE-2026-44963.svg)


## CVE-2026-42588
Users are recommended to upgrade to version 5.19.7 or 6.2.6, which fixes the issue.

- [https://github.com/gentleman567/POC](https://github.com/gentleman567/POC) :  ![starts](https://img.shields.io/github/stars/gentleman567/POC.svg) ![forks](https://img.shields.io/github/forks/gentleman567/POC.svg)


## CVE-2026-42208
 LiteLLM is a proxy server (AI Gateway) to call LLM APIs in OpenAI (or native) format. From version 1.81.16 to before version 1.83.7, a database query used during proxy API key checks mixed the caller-supplied key value into the query text instead of passing it as a separate parameter. An unauthenticated attacker could send a specially crafted Authorization header to any LLM API route (for example POST /chat/completions) and reach this query through the proxy's error-handling path. An attacker could read data from the proxy's database and may be able to modify it, leading to unauthorised access to the proxy and the credentials it manages. This issue has been patched in version 1.83.7.

- [https://github.com/yendpoint/CVE-2026-42208-LAB](https://github.com/yendpoint/CVE-2026-42208-LAB) :  ![starts](https://img.shields.io/github/stars/yendpoint/CVE-2026-42208-LAB.svg) ![forks](https://img.shields.io/github/forks/yendpoint/CVE-2026-42208-LAB.svg)


## CVE-2026-40369
 Heap-based buffer overflow in Windows Kernel allows an authorized attacker to elevate privileges locally.

- [https://github.com/0xBlackash/CVE-2026-40369](https://github.com/0xBlackash/CVE-2026-40369) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-40369.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-40369.svg)


## CVE-2026-39808
 A improper neutralization of special elements used in an os command ('os command injection') vulnerability in Fortinet FortiSandbox 4.4.0 through 4.4.8 may allow attacker to execute unauthorized code or commands via insert attack vector here

- [https://github.com/error-inside/CVE-2026-39808](https://github.com/error-inside/CVE-2026-39808) :  ![starts](https://img.shields.io/github/stars/error-inside/CVE-2026-39808.svg) ![forks](https://img.shields.io/github/forks/error-inside/CVE-2026-39808.svg)


## CVE-2026-31431
AD directly.

- [https://github.com/waltrone1/copyfail-safe-check](https://github.com/waltrone1/copyfail-safe-check) :  ![starts](https://img.shields.io/github/stars/waltrone1/copyfail-safe-check.svg) ![forks](https://img.shields.io/github/forks/waltrone1/copyfail-safe-check.svg)


## CVE-2026-10520
 An OS Command Injection vulnerability in Ivanti Sentry before the R10.5.2, R10.6.2 and R10.7.1 versions allows a remote unauthenticated user to achieve root-level remote code execution

- [https://github.com/error-inside/CVE-2026-10520](https://github.com/error-inside/CVE-2026-10520) :  ![starts](https://img.shields.io/github/stars/error-inside/CVE-2026-10520.svg) ![forks](https://img.shields.io/github/forks/error-inside/CVE-2026-10520.svg)


## CVE-2026-3816
 A security vulnerability has been detected in OWASP DefectDojo up to 2.55.4. This vulnerability affects the function input_zip.read of the file parser.py of the component SonarQubeParser/MSDefenderParser. The manipulation leads to denial of service. The attack can be initiated remotely. The exploit has been disclosed publicly and may be used. Upgrading to version 2.56.0 is able to resolve this issue. The identifier of the patch is e8f1e5131535b8fd80a7b1b3085d676295fdcd41. Upgrading the affected component is recommended.

- [https://github.com/AT190510-Cuong/CVE-2026-38165-SSTI-](https://github.com/AT190510-Cuong/CVE-2026-38165-SSTI-) :  ![starts](https://img.shields.io/github/stars/AT190510-Cuong/CVE-2026-38165-SSTI-.svg) ![forks](https://img.shields.io/github/forks/AT190510-Cuong/CVE-2026-38165-SSTI-.svg)


## CVE-2026-3359
 The Form Maker by 10Web – Mobile-Friendly Drag & Drop Contact Form Builder plugin for WordPress is vulnerable to SQL Injection via the 'inputs' parameter in versions up to, and including, 1.15.42 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query. This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/itsthalisman/cve-2026-3359-exp](https://github.com/itsthalisman/cve-2026-3359-exp) :  ![starts](https://img.shields.io/github/stars/itsthalisman/cve-2026-3359-exp.svg) ![forks](https://img.shields.io/github/forks/itsthalisman/cve-2026-3359-exp.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-patch-package](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-patch-package) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-patch-package.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-patch-package.svg)


## CVE-2025-57819
 FreePBX is an open-source web-based graphical user interface. FreePBX 15, 16, and 17 endpoints are vulnerable due to insufficiently sanitized user-supplied data allowing unauthenticated access to FreePBX Administrator leading to arbitrary database manipulation and remote code execution. This issue has been patched in endpoint versions 15.0.66, 16.0.89, and 17.0.3.

- [https://github.com/ozcanpng/CVE-2025-57819-FreePBX-RCE2Root](https://github.com/ozcanpng/CVE-2025-57819-FreePBX-RCE2Root) :  ![starts](https://img.shields.io/github/stars/ozcanpng/CVE-2025-57819-FreePBX-RCE2Root.svg) ![forks](https://img.shields.io/github/forks/ozcanpng/CVE-2025-57819-FreePBX-RCE2Root.svg)


## CVE-2025-53024
 Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.1.10. Easily exploitable vulnerability allows high privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox.  While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products (scope change).  Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.1 Base Score 8.2 (Confidentiality, Integrity and Availability impacts).  CVSS Vector: (CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:H/I:H/A:H).

- [https://github.com/minq0x1412/CVE-2025-53024](https://github.com/minq0x1412/CVE-2025-53024) :  ![starts](https://img.shields.io/github/stars/minq0x1412/CVE-2025-53024.svg) ![forks](https://img.shields.io/github/forks/minq0x1412/CVE-2025-53024.svg)


## CVE-2025-43300
 An out-of-bounds write issue was addressed with improved bounds checking. This issue is fixed in iOS 15.8.5 and iPadOS 15.8.5, iOS 16.7.12 and iPadOS 16.7.12, iOS 18.6.2 and iPadOS 18.6.2, iPadOS 17.7.10, macOS Sequoia 15.6.1, macOS Sonoma 14.7.8, macOS Ventura 13.7.8. Processing a malicious image file may result in memory corruption. Apple is aware of a report that this issue may have been exploited in an extremely sophisticated attack against specific targeted individuals.

- [https://github.com/Shakai-Dev/CVE-2025-43300-exp](https://github.com/Shakai-Dev/CVE-2025-43300-exp) :  ![starts](https://img.shields.io/github/stars/Shakai-Dev/CVE-2025-43300-exp.svg) ![forks](https://img.shields.io/github/forks/Shakai-Dev/CVE-2025-43300-exp.svg)


## CVE-2025-21479
 Memory corruption due to unauthorized command execution in GPU micronode while executing specific sequence of commands.

- [https://github.com/ma4the/omae-wa-cheese-da](https://github.com/ma4the/omae-wa-cheese-da) :  ![starts](https://img.shields.io/github/stars/ma4the/omae-wa-cheese-da.svg) ![forks](https://img.shields.io/github/forks/ma4the/omae-wa-cheese-da.svg)


## CVE-2025-6254
 The Doctreat Core plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.6.8. This is due to the doctreat_process_registration() function not properly restricting the roles that a user can register with. This makes it possible for unauthenticated attackers to register as an administrator user.

- [https://github.com/Yucaerin/CVE-2025-6254](https://github.com/Yucaerin/CVE-2025-6254) :  ![starts](https://img.shields.io/github/stars/Yucaerin/CVE-2025-6254.svg) ![forks](https://img.shields.io/github/forks/Yucaerin/CVE-2025-6254.svg)


## CVE-2024-27198
 In JetBrains TeamCity before 2023.11.4 authentication bypass allowing to perform admin actions was possible

- [https://github.com/ptd200110/CVE-2024-27198-SOC-Lab](https://github.com/ptd200110/CVE-2024-27198-SOC-Lab) :  ![starts](https://img.shields.io/github/stars/ptd200110/CVE-2024-27198-SOC-Lab.svg) ![forks](https://img.shields.io/github/forks/ptd200110/CVE-2024-27198-SOC-Lab.svg)


## CVE-2024-24945
 A stored cross-site scripting (XSS) vulnerability in Travel Journal Using PHP and MySQL with Source Code v1.0 allows attackers to execute arbitrary web scripts or HTML via a crafted payload injected into the Share Your Moments parameter at /travel-journal/write-journal.php.

- [https://github.com/BenedictEjepu/CVE-2024-24945-NGINX-RIFT---TryHackMe-Lab-Walkthrough](https://github.com/BenedictEjepu/CVE-2024-24945-NGINX-RIFT---TryHackMe-Lab-Walkthrough) :  ![starts](https://img.shields.io/github/stars/BenedictEjepu/CVE-2024-24945-NGINX-RIFT---TryHackMe-Lab-Walkthrough.svg) ![forks](https://img.shields.io/github/forks/BenedictEjepu/CVE-2024-24945-NGINX-RIFT---TryHackMe-Lab-Walkthrough.svg)


## CVE-2024-1813
 The Simple Job Board plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 2.11.0 via deserialization of untrusted input in the job_board_applicant_list_columns_value function. This makes it possible for unauthenticated attackers to inject a PHP Object. If a POP chain is present via an additional plugin or theme installed on the target system, it could allow the attacker to delete arbitrary files, retrieve sensitive data, or execute code when a submitted job application is viewed.

- [https://github.com/MobetaSec/CVE-2024-1813-POC](https://github.com/MobetaSec/CVE-2024-1813-POC) :  ![starts](https://img.shields.io/github/stars/MobetaSec/CVE-2024-1813-POC.svg) ![forks](https://img.shields.io/github/forks/MobetaSec/CVE-2024-1813-POC.svg)


## CVE-2023-21991
 Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).  Supported versions that are affected are Prior to 6.1.44 and  Prior to 7.0.8. Easily exploitable vulnerability allows high privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox.  While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products (scope change).  Successful attacks of this vulnerability can result in  unauthorized read access to a subset of Oracle VM VirtualBox accessible data. CVSS 3.1 Base Score 3.2 (Confidentiality impacts).  CVSS Vector: (CVSS:3.1/AV:L/AC:L/PR:H/UI:N/S:C/C:L/I:N/A:N).

- [https://github.com/minq0x1412/CVE-2023-21987-and-CVE-2023-21991](https://github.com/minq0x1412/CVE-2023-21987-and-CVE-2023-21991) :  ![starts](https://img.shields.io/github/stars/minq0x1412/CVE-2023-21987-and-CVE-2023-21991.svg) ![forks](https://img.shields.io/github/forks/minq0x1412/CVE-2023-21987-and-CVE-2023-21991.svg)


## CVE-2023-21987
 Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).  Supported versions that are affected are Prior to 6.1.44 and  Prior to 7.0.8. Difficult to exploit vulnerability allows low privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox.  While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products (scope change).  Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.1 Base Score 7.8 (Confidentiality, Integrity and Availability impacts).  CVSS Vector: (CVSS:3.1/AV:L/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H).

- [https://github.com/minq0x1412/CVE-2023-21987-and-CVE-2023-21991](https://github.com/minq0x1412/CVE-2023-21987-and-CVE-2023-21991) :  ![starts](https://img.shields.io/github/stars/minq0x1412/CVE-2023-21987-and-CVE-2023-21991.svg) ![forks](https://img.shields.io/github/forks/minq0x1412/CVE-2023-21987-and-CVE-2023-21991.svg)


## CVE-2021-4034
 A local privilege escalation vulnerability was found on polkit's pkexec utility. The pkexec application is a setuid tool designed to allow unprivileged users to run commands as privileged users according predefined policies. The current version of pkexec doesn't handle the calling parameters count correctly and ends trying to execute environment variables as commands. An attacker can leverage this by crafting environment variables in such a way it'll induce pkexec to execute arbitrary code. When successfully executed the attack can cause a local privilege escalation given unprivileged users administrative rights on the target machine.

- [https://github.com/devianntsec/CVE-2021-4034](https://github.com/devianntsec/CVE-2021-4034) :  ![starts](https://img.shields.io/github/stars/devianntsec/CVE-2021-4034.svg) ![forks](https://img.shields.io/github/forks/devianntsec/CVE-2021-4034.svg)


## CVE-2007-2447
 The MS-RPC functionality in smbd in Samba 3.0.0 through 3.0.25rc3 allows remote attackers to execute arbitrary commands via shell metacharacters involving the (1) SamrChangePassword function, when the "username map script" smb.conf option is enabled, and allows remote authenticated users to execute commands via shell metacharacters involving other MS-RPC functions in the (2) remote printer and (3) file share management.

- [https://github.com/harshiys/cybersecurity-home-lab-btp](https://github.com/harshiys/cybersecurity-home-lab-btp) :  ![starts](https://img.shields.io/github/stars/harshiys/cybersecurity-home-lab-btp.svg) ![forks](https://img.shields.io/github/forks/harshiys/cybersecurity-home-lab-btp.svg)

