# Update 2026-07-02
## CVE-2026-58138
 Orkes Conductor 3.21.21 before 3.30.2 contains an unauthenticated remote code execution vulnerability that allows remote attackers to execute arbitrary OS commands by submitting inline workflow definitions containing malicious JavaScript or Python expressions to the workflow API endpoint prior to authentication. Attackers can exploit unsandboxed GraalVM evaluators configured with HostAccess.ALL or allowAllAccess(true) through INLINE, LAMBDA, DO_WHILE, and SWITCH task types to invoke arbitrary system commands via Java reflection or direct subprocess calls.

- [https://github.com/BiiTts/CVE-2026-58138-Conductor-Unauth-RCE](https://github.com/BiiTts/CVE-2026-58138-Conductor-Unauth-RCE) :  ![starts](https://img.shields.io/github/stars/BiiTts/CVE-2026-58138-Conductor-Unauth-RCE.svg) ![forks](https://img.shields.io/github/forks/BiiTts/CVE-2026-58138-Conductor-Unauth-RCE.svg)


## CVE-2026-56121
 Feast before 0.63.0 contains an unsafe deserialization vulnerability that allows unauthenticated or unauthorized attackers to achieve remote code execution by sending a crafted gRPC request to the registry server. The user_defined_function.body field of an OnDemandFeatureView spec is decoded from base64 and passed to dill.loads() before any authorization check is performed, enabling attackers to embed a malicious serialized Python object with an arbitrary __reduce__ method to execute OS commands as the feast service account.

- [https://github.com/BiiTts/CVE-2026-56121-Feast-Unauth-RCE](https://github.com/BiiTts/CVE-2026-56121-Feast-Unauth-RCE) :  ![starts](https://img.shields.io/github/stars/BiiTts/CVE-2026-56121-Feast-Unauth-RCE.svg) ![forks](https://img.shields.io/github/forks/BiiTts/CVE-2026-56121-Feast-Unauth-RCE.svg)


## CVE-2026-55488
 motionEye (mEye) is an online interface for a piece of software called "motion," which is a video surveillance program with motion detection. Versions prior to 0.44.0 contain an absolute path traversal vulnerability in multiple media file handlers that allows an attacker to read arbitrary files from the filesystem. The affected handlers accept a user-controlled filename parameter and construct filesystem paths using `os.path.join()`. When an absolute path is supplied, Python discards the configured media directory and returns the attacker-supplied path directly. The application then bypasses Tornado's built-in path validation by overriding the relevant safety checks. As a result, an attacker can access files outside of the configured camera media directory, subject to the permissions of the motionEye process. Version 0.44.0 fixes the issue.

- [https://github.com/thecodeb0ss/CVE-2026-55488](https://github.com/thecodeb0ss/CVE-2026-55488) :  ![starts](https://img.shields.io/github/stars/thecodeb0ss/CVE-2026-55488.svg) ![forks](https://img.shields.io/github/forks/thecodeb0ss/CVE-2026-55488.svg)


## CVE-2026-55255
 Langflow is a tool for building and deploying AI-powered agents and workflows. Prior to 1.9.2, an Insecure Direct Object Reference (IDOR) vulnerability in /api/v1/responses endpoint allows an authenticated attacker to execute any flow belonging to another user by specifying the victim's flow ID in the request. This vulnerability is fixed in 1.9.2.

- [https://github.com/rootdirective-sec/CVE-2026-55255-Lab](https://github.com/rootdirective-sec/CVE-2026-55255-Lab) :  ![starts](https://img.shields.io/github/stars/rootdirective-sec/CVE-2026-55255-Lab.svg) ![forks](https://img.shields.io/github/forks/rootdirective-sec/CVE-2026-55255-Lab.svg)


## CVE-2026-49869
 Kestra is an open-source, event-driven orchestration platform. Prior to 1.0.45 and 1.3.21, AuthenticationFilter in Kestra OSS uses request.getPath().endsWith("/configs") to whitelist the public configuration endpoint from Basic Auth. Because the check is a suffix match rather than an exact path match, any API path whose last segment is configs bypasses authentication entirely. An unauthenticated remote attacker can exploit this to create and execute arbitrary workflows without credentials. Because Kestra ships with script execution plugins (plugin-script-shell, plugin-script-python, etc.) enabled by default, this directly results in unauthenticated Remote Code Execution as root inside the Kestra worker container.  This vulnerability is fixed in 1.0.45 and 1.3.21.

- [https://github.com/Ap0dexMe0/CVE-2026-49869](https://github.com/Ap0dexMe0/CVE-2026-49869) :  ![starts](https://img.shields.io/github/stars/Ap0dexMe0/CVE-2026-49869.svg) ![forks](https://img.shields.io/github/forks/Ap0dexMe0/CVE-2026-49869.svg)


## CVE-2026-48907
 A vulnerability in the JCE editor extension for Joomla allows the creation of new editor profiles for unauthenticated users, ultimately resulting in PHP code upload and execution.

- [https://github.com/pssec-io/CVE-2026-48907](https://github.com/pssec-io/CVE-2026-48907) :  ![starts](https://img.shields.io/github/stars/pssec-io/CVE-2026-48907.svg) ![forks](https://img.shields.io/github/forks/pssec-io/CVE-2026-48907.svg)


## CVE-2026-46817
 Vulnerability in the Oracle Payments product of Oracle E-Business Suite (component: File Transmission).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle Payments.  Successful attacks of this vulnerability can result in takeover of Oracle Payments. CVSS 3.1 Base Score 9.8 (Confidentiality, Integrity and Availability impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H).

- [https://github.com/HORKimhab/CVE-2026-46817](https://github.com/HORKimhab/CVE-2026-46817) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-46817.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-46817.svg)


## CVE-2026-46490
 samlify is a Node.js library for SAML single sign-on. Prior to version 2.13.0, samlify’s template substitution only escapes attribute contexts. Values inserted into element text (e.g., saml:AttributeValue) are not escaped. A normal user can inject XML markup into an attribute value (e.g., email, name) and add new saml:Attribute elements inside the signed assertion. The IdP then signs the tampered assertion and the SP accepts the injected attributes as trusted. This allows privilege escalation when attributes are used for authorization (roles/groups). This issue has been patched in version 2.13.0.

- [https://github.com/BiiTts/CVE-2026-46490-samlify-SAML-Attribute-Injection](https://github.com/BiiTts/CVE-2026-46490-samlify-SAML-Attribute-Injection) :  ![starts](https://img.shields.io/github/stars/BiiTts/CVE-2026-46490-samlify-SAML-Attribute-Injection.svg) ![forks](https://img.shields.io/github/forks/BiiTts/CVE-2026-46490-samlify-SAML-Attribute-Injection.svg)


## CVE-2026-46331
offset_valid() against INT_MIN, where negation is undefined.

- [https://github.com/seguridadentrerios/CVE-2026-46331](https://github.com/seguridadentrerios/CVE-2026-46331) :  ![starts](https://img.shields.io/github/stars/seguridadentrerios/CVE-2026-46331.svg) ![forks](https://img.shields.io/github/forks/seguridadentrerios/CVE-2026-46331.svg)
- [https://github.com/g0thamRabb1t/cve-2026-46331-pedit-cow-auditd-detection](https://github.com/g0thamRabb1t/cve-2026-46331-pedit-cow-auditd-detection) :  ![starts](https://img.shields.io/github/stars/g0thamRabb1t/cve-2026-46331-pedit-cow-auditd-detection.svg) ![forks](https://img.shields.io/github/forks/g0thamRabb1t/cve-2026-46331-pedit-cow-auditd-detection.svg)


## CVE-2026-46300
bytes into @to's linear data rather than transferring frag descriptors.

- [https://github.com/MadExploits/CVE-2026-46300](https://github.com/MadExploits/CVE-2026-46300) :  ![starts](https://img.shields.io/github/stars/MadExploits/CVE-2026-46300.svg) ![forks](https://img.shields.io/github/forks/MadExploits/CVE-2026-46300.svg)


## CVE-2026-44789
 n8n is an open source workflow automation platform. Prior to 1.123.43, 2.22.1, and 2.20.7, an authenticated user with permission to create or modify workflows could achieve global prototype pollution via an unvalidated pagination parameter in the HTTP Request node. Combined with other techniques this could lead to RCE on the instance. This vulnerability is fixed in 1.123.43, 2.22.1, and 2.20.7.

- [https://github.com/BiiTts/CVE-2026-44789-n8n-PrototypePollution-RCE](https://github.com/BiiTts/CVE-2026-44789-n8n-PrototypePollution-RCE) :  ![starts](https://img.shields.io/github/stars/BiiTts/CVE-2026-44789-n8n-PrototypePollution-RCE.svg) ![forks](https://img.shields.io/github/forks/BiiTts/CVE-2026-44789-n8n-PrototypePollution-RCE.svg)


## CVE-2026-43700
 A cross-origin issue was addressed with improved tracking of security origins. This issue is fixed in Safari 26.5.2, iOS 26.5.2 and iPadOS 26.5.2, macOS Tahoe 26.5.2. Processing maliciously crafted web content may disclose sensitive user information.

- [https://github.com/dem0ns/CVE-2026-43700](https://github.com/dem0ns/CVE-2026-43700) :  ![starts](https://img.shields.io/github/stars/dem0ns/CVE-2026-43700.svg) ![forks](https://img.shields.io/github/forks/dem0ns/CVE-2026-43700.svg)


## CVE-2026-43500
page_pool RX, GRO).  The OOM/trace handling already in place is reused.

- [https://github.com/MadExploits/CVE-2026-46300](https://github.com/MadExploits/CVE-2026-46300) :  ![starts](https://img.shields.io/github/stars/MadExploits/CVE-2026-46300.svg) ![forks](https://img.shields.io/github/forks/MadExploits/CVE-2026-46300.svg)


## CVE-2026-43284
destination-frag path or fall back to skb_cow_data().

- [https://github.com/MadExploits/CVE-2026-46300](https://github.com/MadExploits/CVE-2026-46300) :  ![starts](https://img.shields.io/github/stars/MadExploits/CVE-2026-46300.svg) ![forks](https://img.shields.io/github/forks/MadExploits/CVE-2026-46300.svg)


## CVE-2026-31694
the readdir cache.

- [https://github.com/0xCyberstan/CVE-2026-31694-POC](https://github.com/0xCyberstan/CVE-2026-31694-POC) :  ![starts](https://img.shields.io/github/stars/0xCyberstan/CVE-2026-31694-POC.svg) ![forks](https://img.shields.io/github/forks/0xCyberstan/CVE-2026-31694-POC.svg)


## CVE-2026-27626
 OliveTin gives access to predefined shell commands from a web interface. In versions up to and including 3000.10.0, OliveTin's shell mode safety check (`checkShellArgumentSafety`) blocks several dangerous argument types but not `password`. A user supplying a `password`-typed argument can inject shell metacharacters that execute arbitrary OS commands. A second independent vector allows unauthenticated RCE via webhook-extracted JSON values that skip type safety checks entirely before reaching `sh -c`. When exploiting vector 1, any authenticated user (registration enabled by default, `authType: none` by default) can execute arbitrary OS commands on the OliveTin host with the permissions of the OliveTin process. When exploiting vector 2, an unauthenticated attacker can achieve the same if the instance receives webhooks from external sources, which is a primary OliveTin use case. When an attacker exploits both vectors, this results in unauthenticated RCE on any OliveTin instance using Shell mode with webhook-triggered actions. As of time of publication, a patched version is not available.

- [https://github.com/0xh7ml/CVE-2026-27626-PoC](https://github.com/0xh7ml/CVE-2026-27626-PoC) :  ![starts](https://img.shields.io/github/stars/0xh7ml/CVE-2026-27626-PoC.svg) ![forks](https://img.shields.io/github/forks/0xh7ml/CVE-2026-27626-PoC.svg)


## CVE-2026-22557
 A malicious actor with access to the network could exploit a Path Traversal vulnerability found in the UniFi Network Application to access files on the underlying system that could be manipulated to access an underlying account.

- [https://github.com/gagaltotal/CVE-2026-22557-Path-Traversal-Ubiquti-UniFi](https://github.com/gagaltotal/CVE-2026-22557-Path-Traversal-Ubiquti-UniFi) :  ![starts](https://img.shields.io/github/stars/gagaltotal/CVE-2026-22557-Path-Traversal-Ubiquti-UniFi.svg) ![forks](https://img.shields.io/github/forks/gagaltotal/CVE-2026-22557-Path-Traversal-Ubiquti-UniFi.svg)


## CVE-2026-21509
 Reliance on untrusted inputs in a security decision in Microsoft Office allows an unauthorized attacker to bypass a security feature locally.

- [https://github.com/sentinel-aidefense/CVE-2026-21509](https://github.com/sentinel-aidefense/CVE-2026-21509) :  ![starts](https://img.shields.io/github/stars/sentinel-aidefense/CVE-2026-21509.svg) ![forks](https://img.shields.io/github/forks/sentinel-aidefense/CVE-2026-21509.svg)


## CVE-2026-13474
 Denial of service via malformed HTTP/2 requests in NetScaler ADC and NetScaler Gateway if HTTP/2 is enabled in HTTP Profile and associated with the virtual server (of type LB, CS, VPN) or the service configured on NetScaler

- [https://github.com/derekpreston81/CVE_ADC_IOC_2026](https://github.com/derekpreston81/CVE_ADC_IOC_2026) :  ![starts](https://img.shields.io/github/stars/derekpreston81/CVE_ADC_IOC_2026.svg) ![forks](https://img.shields.io/github/forks/derekpreston81/CVE_ADC_IOC_2026.svg)


## CVE-2026-10817
 Insufficient input validation leading to memory overread in NetScaler ADC and NetScaler Gateway if the TCP TimeStamp is enabled in TCP Profile and is associated with the virtual server (of type LB, CS, VPN) or the service configured on NetScaler

- [https://github.com/derekpreston81/CVE_ADC_IOC_2026](https://github.com/derekpreston81/CVE_ADC_IOC_2026) :  ![starts](https://img.shields.io/github/stars/derekpreston81/CVE_ADC_IOC_2026.svg) ![forks](https://img.shields.io/github/forks/derekpreston81/CVE_ADC_IOC_2026.svg)


## CVE-2026-10816
 Arbitrary File Read (Unauthenticated) in NetScaler ADC and NetScaler Gateway if the access to NSIP, Cluster Management IP or SNIP with management access is enabled

- [https://github.com/derekpreston81/CVE_ADC_IOC_2026](https://github.com/derekpreston81/CVE_ADC_IOC_2026) :  ![starts](https://img.shields.io/github/stars/derekpreston81/CVE_ADC_IOC_2026.svg) ![forks](https://img.shields.io/github/forks/derekpreston81/CVE_ADC_IOC_2026.svg)


## CVE-2026-10580
 The Hippoo Mobile App for WooCommerce plugin for WordPress is vulnerable to Authentication Bypass leading to Administrator Account Takeover in all versions up to and including 1.9.4. This is due to a logic conflation in HippooPermissions::get_user_permissions(), which returns the same null sentinel for both administrators and unauthenticated visitors — a value that HippooPermissions::has_role_access() unconditionally interprets as full administrator access — causing override_extension_permission_callback() to assign __return_true as the permission callback for every WordPress and WooCommerce REST route cloned under /wc-hippoo/v1/ext/ by HippooControllerWithAuth::re_register_external_routes(), while the block_unauthorized_access() pre-dispatch guard fails to block unauthenticated users for the same reason. This makes it possible for unauthenticated attackers to invoke any core REST endpoint without credentials — most critically, sending a POST request to /wc-hippoo/v1/ext/wp/v2/users/id with a {"password":"new_password"} body to reset the password of any WordPress user, including the site administrator, and gain full administrative control of the site.

- [https://github.com/0xgh057r3c0n/CVE-2026-10580](https://github.com/0xgh057r3c0n/CVE-2026-10580) :  ![starts](https://img.shields.io/github/stars/0xgh057r3c0n/CVE-2026-10580.svg) ![forks](https://img.shields.io/github/forks/0xgh057r3c0n/CVE-2026-10580.svg)


## CVE-2026-8655
 Multiple Memory overflow vulnerabilities in NetScaler ADC and NetScaler Gateway leading to unpredictable or erroneous behavior and Denial of Service if NetScaler ADC is configured as an LB of type Oracle OR NetScaler ADC is configured as a DNS Proxy OR NetScaler ADC is configured as a DNS recursive resolver deployment

- [https://github.com/derekpreston81/CVE_ADC_IOC_2026](https://github.com/derekpreston81/CVE_ADC_IOC_2026) :  ![starts](https://img.shields.io/github/stars/derekpreston81/CVE_ADC_IOC_2026.svg) ![forks](https://img.shields.io/github/forks/derekpreston81/CVE_ADC_IOC_2026.svg)


## CVE-2026-8452
 Memory overflow vulnerability NetScaler ADC and NetScaler Gateway leading to unpredictable or erroneous behavior and Denial of Service if the appliance is configured as a Gateway (SSL VPN, ICA Proxy, CVPN, RDP Proxy) or AAA virtual server

- [https://github.com/derekpreston81/CVE_ADC_IOC_2026](https://github.com/derekpreston81/CVE_ADC_IOC_2026) :  ![starts](https://img.shields.io/github/stars/derekpreston81/CVE_ADC_IOC_2026.svg) ![forks](https://img.shields.io/github/forks/derekpreston81/CVE_ADC_IOC_2026.svg)


## CVE-2026-8451
 Insufficient input validation in NetScaler ADC and NetScaler Gateway leading to memory overread if NetScaler ADC or NetScaler Gateway is configured as a SAML IDP

- [https://github.com/watchtowrlabs/watchTowr-vs-Netscaler-CVE-2026-8451](https://github.com/watchtowrlabs/watchTowr-vs-Netscaler-CVE-2026-8451) :  ![starts](https://img.shields.io/github/stars/watchtowrlabs/watchTowr-vs-Netscaler-CVE-2026-8451.svg) ![forks](https://img.shields.io/github/forks/watchtowrlabs/watchTowr-vs-Netscaler-CVE-2026-8451.svg)
- [https://github.com/derekpreston81/CVE_ADC_IOC_2026](https://github.com/derekpreston81/CVE_ADC_IOC_2026) :  ![starts](https://img.shields.io/github/stars/derekpreston81/CVE_ADC_IOC_2026.svg) ![forks](https://img.shields.io/github/forks/derekpreston81/CVE_ADC_IOC_2026.svg)


## CVE-2026-8037
 OS Command Injection Remote Code Execution Vulnerability in API in Progress ADC Products allows an un-authenticated attacker to execute arbitrary commands on the LoadMaster appliance by exploiting unsanitized input in multiple command endpoints

- [https://github.com/HORKimhab/CVE-2026-8037](https://github.com/HORKimhab/CVE-2026-8037) :  ![starts](https://img.shields.io/github/stars/HORKimhab/CVE-2026-8037.svg) ![forks](https://img.shields.io/github/forks/HORKimhab/CVE-2026-8037.svg)


## CVE-2026-4020
 The Gravity SMTP plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and including, 2.1.4. This is due to a REST API endpoint registered at /wp-json/gravitysmtp/v1/tests/mock-data with a permission_callback that unconditionally returns true, allowing any unauthenticated visitor to access it. When the ?page=gravitysmtp-settings query parameter is appended, the plugin's register_connector_data() method populates internal connector data, causing the endpoint to return approximately 365 KB of JSON containing the full System Report. This makes it possible for unauthenticated attackers to retrieve detailed system configuration data including PHP version, loaded extensions, web server version, document root path, database server type and version, WordPress version, all active plugins with versions, active theme, WordPress configuration details, database table names, and any API keys/tokens configured in the plugin.

- [https://github.com/faizdotid/CVE-2026-4020](https://github.com/faizdotid/CVE-2026-4020) :  ![starts](https://img.shields.io/github/stars/faizdotid/CVE-2026-4020.svg) ![forks](https://img.shields.io/github/forks/faizdotid/CVE-2026-4020.svg)


## CVE-2025-69212
 OpenSTAManager is an open source management software for technical assistance and invoicing. In 2.9.8 and earlier, a critical OS Command Injection vulnerability exists in the P7M (signed XML) file decoding functionality. An authenticated attacker can upload a ZIP file containing a .p7m file with a malicious filename to execute arbitrary system commands on the server.

- [https://github.com/BridgerAlderson/CVE-2025-69212-PoC](https://github.com/BridgerAlderson/CVE-2025-69212-PoC) :  ![starts](https://img.shields.io/github/stars/BridgerAlderson/CVE-2025-69212-PoC.svg) ![forks](https://img.shields.io/github/forks/BridgerAlderson/CVE-2025-69212-PoC.svg)
- [https://github.com/xorandd/CVE-2025-69212-PoC](https://github.com/xorandd/CVE-2025-69212-PoC) :  ![starts](https://img.shields.io/github/stars/xorandd/CVE-2025-69212-PoC.svg) ![forks](https://img.shields.io/github/forks/xorandd/CVE-2025-69212-PoC.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-monorepo-nextjs-yarn-workspaces](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-monorepo-nextjs-yarn-workspaces) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-monorepo-nextjs-yarn-workspaces.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-monorepo-nextjs-yarn-workspaces.svg)
- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-rsc-webpack.svg)


## CVE-2025-40271
                  NULL  pde(tun2)

- [https://github.com/MadExploits/CVE-2025-40271](https://github.com/MadExploits/CVE-2025-40271) :  ![starts](https://img.shields.io/github/stars/MadExploits/CVE-2025-40271.svg) ![forks](https://img.shields.io/github/forks/MadExploits/CVE-2025-40271.svg)


## CVE-2025-32434
 PyTorch is a Python package that provides tensor computation with strong GPU acceleration and deep neural networks built on a tape-based autograd system. In version 2.5.1 and prior, a Remote Command Execution (RCE) vulnerability exists in PyTorch when loading a model using torch.load with weights_only=True. This issue has been patched in version 2.6.0.

- [https://github.com/AlexanderGumeniuk/CVE-2025-32434](https://github.com/AlexanderGumeniuk/CVE-2025-32434) :  ![starts](https://img.shields.io/github/stars/AlexanderGumeniuk/CVE-2025-32434.svg) ![forks](https://img.shields.io/github/forks/AlexanderGumeniuk/CVE-2025-32434.svg)


## CVE-2025-6357
 A vulnerability was found in code-projects Simple Pizza Ordering System 1.0. It has been classified as critical. Affected is an unknown function of the file /paymentportal.php. The manipulation of the argument person leads to sql injection. It is possible to launch the attack remotely. The exploit has been disclosed to the public and may be used.

- [https://github.com/barisbaydur/CVE-2025-63579](https://github.com/barisbaydur/CVE-2025-63579) :  ![starts](https://img.shields.io/github/stars/barisbaydur/CVE-2025-63579.svg) ![forks](https://img.shields.io/github/forks/barisbaydur/CVE-2025-63579.svg)


## CVE-2025-4542
 A vulnerability, which was classified as problematic, has been found in Freeebird Hotel 酒店管理系统 API up to 1.2. Affected by this issue is some unknown functionality of the file /src/main/java/cn/mafangui/hotel/tool/SessionInterceptor.java. The manipulation leads to permissive cross-domain policy with untrusted domains. The attack may be launched remotely. The complexity of an attack is rather high. The exploitation is known to be difficult. The exploit has been disclosed to the public and may be used.

- [https://github.com/Cedrico03/CVE-2025-45422---Bbox](https://github.com/Cedrico03/CVE-2025-45422---Bbox) :  ![starts](https://img.shields.io/github/stars/Cedrico03/CVE-2025-45422---Bbox.svg) ![forks](https://img.shields.io/github/forks/Cedrico03/CVE-2025-45422---Bbox.svg)


## CVE-2024-31317
 In multiple functions of ZygoteProcess.java, there is a possible way to achieve code execution as any app via WRITE_SECURE_SETTINGS due to unsafe deserialization. This could lead to local escalation of privilege with User execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/Tinnci/cve-2024-31317](https://github.com/Tinnci/cve-2024-31317) :  ![starts](https://img.shields.io/github/stars/Tinnci/cve-2024-31317.svg) ![forks](https://img.shields.io/github/forks/Tinnci/cve-2024-31317.svg)


## CVE-2024-28397
 An issue in the component js2py.disable_pyimport() of js2py up to v0.74 allows attackers to execute arbitrary code via a crafted API call.

- [https://github.com/somisec/CVE-2024-28397-Reverse-Shell](https://github.com/somisec/CVE-2024-28397-Reverse-Shell) :  ![starts](https://img.shields.io/github/stars/somisec/CVE-2024-28397-Reverse-Shell.svg) ![forks](https://img.shields.io/github/forks/somisec/CVE-2024-28397-Reverse-Shell.svg)


## CVE-2024-27198
 In JetBrains TeamCity before 2023.11.4 authentication bypass allowing to perform admin actions was possible

- [https://github.com/BilalAlshiekh912/Incident-Response-Report-TeamCity-Compromise-CVE-2024-27198-](https://github.com/BilalAlshiekh912/Incident-Response-Report-TeamCity-Compromise-CVE-2024-27198-) :  ![starts](https://img.shields.io/github/stars/BilalAlshiekh912/Incident-Response-Report-TeamCity-Compromise-CVE-2024-27198-.svg) ![forks](https://img.shields.io/github/forks/BilalAlshiekh912/Incident-Response-Report-TeamCity-Compromise-CVE-2024-27198-.svg)


## CVE-2021-41773
 A flaw was found in a change made to path normalization in Apache HTTP Server 2.4.49. An attacker could use a path traversal attack to map URLs to files outside the directories configured by Alias-like directives. If files outside of these directories are not protected by the usual default configuration "require all denied", these requests can succeed. If CGI scripts are also enabled for these aliased pathes, this could allow for remote code execution. This issue is known to be exploited in the wild. This issue only affects Apache 2.4.49 and not earlier versions. The fix in Apache HTTP Server 2.4.50 was found to be incomplete, see CVE-2021-42013.

- [https://github.com/wolf1892/CVE-2021-41773](https://github.com/wolf1892/CVE-2021-41773) :  ![starts](https://img.shields.io/github/stars/wolf1892/CVE-2021-41773.svg) ![forks](https://img.shields.io/github/forks/wolf1892/CVE-2021-41773.svg)

