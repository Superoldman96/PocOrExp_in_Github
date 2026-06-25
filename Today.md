# Update 2026-06-25
## CVE-2026-55200
 libssh2 through 1.11.1, fixed in commit 7acf3df contains an out-of-bounds write vulnerability in ssh2_transport_read() that fails to enforce upper bounds on packet_length field. Remote attackers can send crafted SSH packets with excessively large packet_length values to corrupt heap memory and achieve remote code execution.

- [https://github.com/0xBlackash/CVE-2026-55200](https://github.com/0xBlackash/CVE-2026-55200) :  ![starts](https://img.shields.io/github/stars/0xBlackash/CVE-2026-55200.svg) ![forks](https://img.shields.io/github/forks/0xBlackash/CVE-2026-55200.svg)


## CVE-2026-54761
 Traefik is an HTTP reverse proxy and load balancer. Prior to 3.6.21 and 3.7.5, there is a high severity vulnerability in Traefik's Kubernetes Gateway provider affecting the crossProviderNamespaces allowlist. For HTTPRoute rules that declare multiple (WRR) backendRefs, Traefik evaluates the allowlist against the target backendRef.namespace instead of the route's own namespace. As a result, an HTTPRoute created in a namespace that is not allow-listed can reference a cross-provider TraefikService such as api@internal, dashboard@internal or rest@internal by pointing backendRef.namespace at an allow-listed namespace covered by a Gateway API ReferenceGrant, exposing internal Traefik services on the data plane. Exploitation requires the ability to create an accepted HTTPRoute and a matching ReferenceGrant from an allow-listed namespace; it does not require any change to Traefik static configuration, RBAC, or the deployment itself. This vulnerability is fixed in 3.6.21 and 3.7.5.

- [https://github.com/Saku0512/CVE-2026-54761-poc](https://github.com/Saku0512/CVE-2026-54761-poc) :  ![starts](https://img.shields.io/github/stars/Saku0512/CVE-2026-54761-poc.svg) ![forks](https://img.shields.io/github/forks/Saku0512/CVE-2026-54761-poc.svg)


## CVE-2026-54316
 Claude Code is an agentic coding tool.  From 0.2.54 until 2.1.163, because the hostname huggingface.co was pre-approved as a bare hostname for the WebFetch tool, any path on that domain—including attacker-controlled model repositories—was auto-approved without a permission prompt or being subject to --allowedTools restrictions. An attacker able to inject untrusted content into a Claude Code context could direct it to issue WebFetch requests against attacker-controlled repository files (e.g. /resolve/main/config.json), which HuggingFace counts as downloads server-side, creating a covert out-of-band channel for encoding and exfiltrating data Claude can access such as files, environment variables, or command output. Reliably exploiting this required the ability to add untrusted content into a Claude Code context window. This vulnerability is fixed in 2.1.163.

- [https://github.com/InertFluid/cve-2026-54316-lab](https://github.com/InertFluid/cve-2026-54316-lab) :  ![starts](https://img.shields.io/github/stars/InertFluid/cve-2026-54316-lab.svg) ![forks](https://img.shields.io/github/forks/InertFluid/cve-2026-54316-lab.svg)


## CVE-2026-46552
 NocoDB is software for building databases as spreadsheets. Prior to 2026.04.1, shared-base sessions were granted the same base-member capabilities as authenticated viewers. Using only the shared-base UUID (xc-shared-base-id), an attacker could enumerate base members and invite an arbitrary email into the base as a real member. The invited user could then redeem the invite via the normal signup flow and retain authenticated access even after the owner revoked the shared link. Shared-base sessions were mapped to ProjectRoles.VIEWER in packages/nocodb/src/strategies/base-view.strategy/base-view.strategy.ts, and packages/nocodb/src/utils/acl.ts granted baseUserList and userInvite to that role. The shared frontend (packages/nc-gui/composables/useApi/interceptors.ts) deliberately removed auth headers in favour of the shared-base header, but the ACL middleware did not distinguish shared sessions from genuine viewers. This vulnerability is fixed in 2026.04.1.

- [https://github.com/0xmrma/CVE-2026-46552](https://github.com/0xmrma/CVE-2026-46552) :  ![starts](https://img.shields.io/github/stars/0xmrma/CVE-2026-46552.svg) ![forks](https://img.shields.io/github/forks/0xmrma/CVE-2026-46552.svg)


## CVE-2026-45156
 Nextcloud is an open source content collaboration platform. From versions 0.3.0 to before 3.1.0, 5.0.0 to before 5.1.0, and 6.0.0 to before 6.4.0, a missing signature verification in User OIDC allowed a malicious ID4me authority to identify as any user. This issue has been patched in versions 3.1.0, 4.1.0, 5.1.0, 6.4.0 and 8.3.0.

- [https://github.com/cybertechajju/CVE-2026-45156-POC](https://github.com/cybertechajju/CVE-2026-45156-POC) :  ![starts](https://img.shields.io/github/stars/cybertechajju/CVE-2026-45156-POC.svg) ![forks](https://img.shields.io/github/forks/cybertechajju/CVE-2026-45156-POC.svg)


## CVE-2026-42978
 Concurrent execution using shared resource with improper synchronization ('race condition') in Windows Push Notifications allows an authorized attacker to elevate privileges locally.

- [https://github.com/grizzzer/CVE-2026-42978-PoC-Research](https://github.com/grizzzer/CVE-2026-42978-PoC-Research) :  ![starts](https://img.shields.io/github/stars/grizzzer/CVE-2026-42978-PoC-Research.svg) ![forks](https://img.shields.io/github/forks/grizzzer/CVE-2026-42978-PoC-Research.svg)


## CVE-2026-42238
 Nginx UI is a web user interface for the Nginx web server. Prior to version 2.3.8, nginx-ui exposes a backup restore endpoint (POST /api/restore) that is completely unauthenticated during the first 10 minutes after process startup on any fresh installation. An unauthenticated remote attacker can upload a crafted backup archive that overwrites the application's configuration file (app.ini) and SQLite database. Because the attacker controls the restored app.ini, they can inject an arbitrary OS command into the TestConfigCmd setting. After the application automatically restarts to apply the restored config, a single follow-up request triggers that command as the user running nginx-ui — typically root in Docker deployments. This issue has been patched in version 2.3.8.

- [https://github.com/fuchiuebusi-lab/nginx-ui-CVE-2026-42221-CVE-2026-42238-](https://github.com/fuchiuebusi-lab/nginx-ui-CVE-2026-42221-CVE-2026-42238-) :  ![starts](https://img.shields.io/github/stars/fuchiuebusi-lab/nginx-ui-CVE-2026-42221-CVE-2026-42238-.svg) ![forks](https://img.shields.io/github/forks/fuchiuebusi-lab/nginx-ui-CVE-2026-42221-CVE-2026-42238-.svg)


## CVE-2026-42221
 Nginx UI is a web user interface for the Nginx web server. From version 2.0.0 to before version 2.3.8, an unauthenticated network attacker can claim the initial administrator account on a fresh nginx-ui instance during the first-run setup window. The public /api/install endpoint is reachable without authentication, and the request-encryption flow only protects payload confidentiality in transit; it does not authenticate who is allowed to perform installation. A remote attacker who reaches the service before the legitimate operator can set the admin email, username, and password, causing permanent initial-instance takeover. This issue has been patched in version 2.3.8.

- [https://github.com/fuchiuebusi-lab/nginx-ui-CVE-2026-42221-CVE-2026-42238-](https://github.com/fuchiuebusi-lab/nginx-ui-CVE-2026-42221-CVE-2026-42238-) :  ![starts](https://img.shields.io/github/stars/fuchiuebusi-lab/nginx-ui-CVE-2026-42221-CVE-2026-42238-.svg) ![forks](https://img.shields.io/github/forks/fuchiuebusi-lab/nginx-ui-CVE-2026-42221-CVE-2026-42238-.svg)


## CVE-2026-41096
 Heap-based buffer overflow in Microsoft Windows DNS allows an unauthorized attacker to execute code over a network.

- [https://github.com/personnumber3377/dns_client_fuzzing](https://github.com/personnumber3377/dns_client_fuzzing) :  ![starts](https://img.shields.io/github/stars/personnumber3377/dns_client_fuzzing.svg) ![forks](https://img.shields.io/github/forks/personnumber3377/dns_client_fuzzing.svg)


## CVE-2026-40369
 Heap-based buffer overflow in Windows Kernel allows an authorized attacker to elevate privileges locally.

- [https://github.com/CCELEND/CVE-2026-40369](https://github.com/CCELEND/CVE-2026-40369) :  ![starts](https://img.shields.io/github/stars/CCELEND/CVE-2026-40369.svg) ![forks](https://img.shields.io/github/forks/CCELEND/CVE-2026-40369.svg)


## CVE-2026-39253
 An issue in Pivotal CRM v.6.6.04.08 allows a remote attacker to execute arbitrary code via the Pivotal.Core.Common.dll and Pivotal.Engine.Client.Services.Conversion.dll components.

- [https://github.com/timtimxs/CVE-2026-39253-Advisory](https://github.com/timtimxs/CVE-2026-39253-Advisory) :  ![starts](https://img.shields.io/github/stars/timtimxs/CVE-2026-39253-Advisory.svg) ![forks](https://img.shields.io/github/forks/timtimxs/CVE-2026-39253-Advisory.svg)


## CVE-2026-31431
AD directly.

- [https://github.com/parmstro/cfDr](https://github.com/parmstro/cfDr) :  ![starts](https://img.shields.io/github/stars/parmstro/cfDr.svg) ![forks](https://img.shields.io/github/forks/parmstro/cfDr.svg)


## CVE-2026-24061
 telnetd in GNU Inetutils through 2.7 allows remote authentication bypass via a "-f root" value for the USER environment variable.

- [https://github.com/anxs3c/CVE-2026-24061-GNU-InetUtils-telnetd](https://github.com/anxs3c/CVE-2026-24061-GNU-InetUtils-telnetd) :  ![starts](https://img.shields.io/github/stars/anxs3c/CVE-2026-24061-GNU-InetUtils-telnetd.svg) ![forks](https://img.shields.io/github/forks/anxs3c/CVE-2026-24061-GNU-InetUtils-telnetd.svg)


## CVE-2026-11837
 A local privilege escalation vulnerability was found in the ansible.posix authorized_key module. The module's keyfile() function uses os.chown() instead of os.lchown() and opens files without O_NOFOLLOW when managing SSH authorized keys. An unprivileged local user can pre-stage symbolic links in their ~/.ssh directory to redirect file ownership changes to arbitrary system paths when an operator runs the authorized_key task as root, leading to local privilege escalation.

- [https://github.com/M8seven/cve-2026-11837-ansible-posix-authorized-key](https://github.com/M8seven/cve-2026-11837-ansible-posix-authorized-key) :  ![starts](https://img.shields.io/github/stars/M8seven/cve-2026-11837-ansible-posix-authorized-key.svg) ![forks](https://img.shields.io/github/forks/M8seven/cve-2026-11837-ansible-posix-authorized-key.svg)


## CVE-2026-11834
compromise of the affected device and unauthorized administrative control.

- [https://github.com/mattgsys/CVE-2026-11834](https://github.com/mattgsys/CVE-2026-11834) :  ![starts](https://img.shields.io/github/stars/mattgsys/CVE-2026-11834.svg) ![forks](https://img.shields.io/github/forks/mattgsys/CVE-2026-11834.svg)


## CVE-2026-9082
This issue affects Drupal core: from 8.9.0 before 10.4.10, from 10.5.0 before 10.5.10, from 10.6.0 before 10.6.9, from 11.0.0 before 11.1.10, from 11.2.0 before 11.2.12, from 11.3.0 before 11.3.10.

- [https://github.com/eliHiHo/portfolio-drupal-cve-2026-9082](https://github.com/eliHiHo/portfolio-drupal-cve-2026-9082) :  ![starts](https://img.shields.io/github/stars/eliHiHo/portfolio-drupal-cve-2026-9082.svg) ![forks](https://img.shields.io/github/forks/eliHiHo/portfolio-drupal-cve-2026-9082.svg)


## CVE-2026-8461
This issue affects FFmpeg before version 8.1.2.

- [https://github.com/anyanything/CVE-2026-8461-PoC](https://github.com/anyanything/CVE-2026-8461-PoC) :  ![starts](https://img.shields.io/github/stars/anyanything/CVE-2026-8461-PoC.svg) ![forks](https://img.shields.io/github/forks/anyanything/CVE-2026-8461-PoC.svg)


## CVE-2025-66478
 This CVE is a duplicate of CVE-2025-55182.

- [https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x](https://github.com/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x) :  ![starts](https://img.shields.io/github/stars/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x.svg) ![forks](https://img.shields.io/github/forks/react2shell-repo-menagerie/CVE-2025-66478-single-nextjs-npm-canary-14x.svg)


## CVE-2025-24893
 XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Any guest can perform arbitrary remote code execution through a request to `SolrSearch`. This impacts the confidentiality, integrity and availability of the whole XWiki installation. To reproduce on an instance, without being logged in, go to `host/xwiki/bin/get/Main/SolrSearch?media=rss&text=%7D%7D%7D%7B%7Basync%20async%3Dfalse%7D%7D%7B%7Bgroovy%7D%7Dprintln%28"Hello%20from"%20%2B%20"%20search%20text%3A"%20%2B%20%2823%20%2B%2019%29%29%7B%7B%2Fgroovy%7D%7D%7B%7B%2Fasync%7D%7D%20`. If there is an output, and the title of the RSS feed contains `Hello from search text:42`, then the instance is vulnerable. This vulnerability has been patched in XWiki 15.10.11, 16.4.1 and 16.5.0RC1. Users are advised to upgrade. Users unable to upgrade may edit `Main.SolrSearchMacros` in `SolrSearchMacros.xml` on line 955 to match the `rawResponse` macro in `macros.vm#L2824` with a content type of `application/xml`, instead of simply outputting the content of the feed.

- [https://github.com/anxs3c/Editor-CTF-writre-up](https://github.com/anxs3c/Editor-CTF-writre-up) :  ![starts](https://img.shields.io/github/stars/anxs3c/Editor-CTF-writre-up.svg) ![forks](https://img.shields.io/github/forks/anxs3c/Editor-CTF-writre-up.svg)


## CVE-2024-21413
 Microsoft Outlook Remote Code Execution Vulnerability

- [https://github.com/H1ssBl1tz/Blind-Trust-CVE-2024-21413-Research](https://github.com/H1ssBl1tz/Blind-Trust-CVE-2024-21413-Research) :  ![starts](https://img.shields.io/github/stars/H1ssBl1tz/Blind-Trust-CVE-2024-21413-Research.svg) ![forks](https://img.shields.io/github/forks/H1ssBl1tz/Blind-Trust-CVE-2024-21413-Research.svg)


## CVE-2024-9902
 A flaw was found in Ansible. The ansible-core `user` module can allow an unprivileged user to silently create or replace the contents of any file on any system path and take ownership of it when a privileged user executes the `user` module against the unprivileged user's home directory. If the unprivileged user has traversal permissions on the directory containing the exploited target file, they retain full control over the contents of the file as its owner.

- [https://github.com/M8seven/cve-2026-11837-ansible-posix-authorized-key](https://github.com/M8seven/cve-2026-11837-ansible-posix-authorized-key) :  ![starts](https://img.shields.io/github/stars/M8seven/cve-2026-11837-ansible-posix-authorized-key.svg) ![forks](https://img.shields.io/github/forks/M8seven/cve-2026-11837-ansible-posix-authorized-key.svg)


## CVE-2023-0386
 A flaw was found in the Linux kernel, where unauthorized access to the execution of the setuid file with capabilities was found in the Linux kernel’s OverlayFS subsystem in how a user copies a capable file from a nosuid mount into another mount. This uid mapping bug allows a local user to escalate their privileges on the system.

- [https://github.com/anxs3c/TwoMillion-Machine](https://github.com/anxs3c/TwoMillion-Machine) :  ![starts](https://img.shields.io/github/stars/anxs3c/TwoMillion-Machine.svg) ![forks](https://img.shields.io/github/forks/anxs3c/TwoMillion-Machine.svg)


## CVE-2022-29800
 A time-of-check-time-of-use (TOCTOU) race condition vulnerability was found in networkd-dispatcher. This flaw exists because there is a certain time between the scripts being discovered and them being run. An attacker can abuse this vulnerability to replace scripts that networkd-dispatcher believes to be owned by root with ones that are not.

- [https://github.com/pansyhebephrenic23/pansyhebephrenic23.github.io](https://github.com/pansyhebephrenic23/pansyhebephrenic23.github.io) :  ![starts](https://img.shields.io/github/stars/pansyhebephrenic23/pansyhebephrenic23.github.io.svg) ![forks](https://img.shields.io/github/forks/pansyhebephrenic23/pansyhebephrenic23.github.io.svg)
- [https://github.com/pansyhebephrenic23/NimbusPWN-CVE-2022-29799-29800](https://github.com/pansyhebephrenic23/NimbusPWN-CVE-2022-29799-29800) :  ![starts](https://img.shields.io/github/stars/pansyhebephrenic23/NimbusPWN-CVE-2022-29799-29800.svg) ![forks](https://img.shields.io/github/forks/pansyhebephrenic23/NimbusPWN-CVE-2022-29799-29800.svg)


## CVE-2022-29799
 A vulnerability was found in networkd-dispatcher. This flaw exists because no functions are sanitized by the OperationalState or the AdministrativeState of networkd-dispatcher. This attack leads to a directory traversal to escape from the “/etc/networkd-dispatcher” base directory.

- [https://github.com/pansyhebephrenic23/NimbusPWN-CVE-2022-29799-29800](https://github.com/pansyhebephrenic23/NimbusPWN-CVE-2022-29799-29800) :  ![starts](https://img.shields.io/github/stars/pansyhebephrenic23/NimbusPWN-CVE-2022-29799-29800.svg) ![forks](https://img.shields.io/github/forks/pansyhebephrenic23/NimbusPWN-CVE-2022-29799-29800.svg)
- [https://github.com/pansyhebephrenic23/pansyhebephrenic23.github.io](https://github.com/pansyhebephrenic23/pansyhebephrenic23.github.io) :  ![starts](https://img.shields.io/github/stars/pansyhebephrenic23/pansyhebephrenic23.github.io.svg) ![forks](https://img.shields.io/github/forks/pansyhebephrenic23/pansyhebephrenic23.github.io.svg)


## CVE-2021-42013
 It was found that the fix for CVE-2021-41773 in Apache HTTP Server 2.4.50 was insufficient. An attacker could use a path traversal attack to map URLs to files outside the directories configured by Alias-like directives. If files outside of these directories are not protected by the usual default configuration "require all denied", these requests can succeed. If CGI scripts are also enabled for these aliased pathes, this could allow for remote code execution. This issue only affects Apache 2.4.49 and Apache 2.4.50 and not earlier versions.

- [https://github.com/Joapath/CVE-2021-42013](https://github.com/Joapath/CVE-2021-42013) :  ![starts](https://img.shields.io/github/stars/Joapath/CVE-2021-42013.svg) ![forks](https://img.shields.io/github/forks/Joapath/CVE-2021-42013.svg)


## CVE-2021-21425
 Grav Admin Plugin is an HTML user interface that provides a way to configure Grav and create and modify pages. In versions 1.10.7 and earlier, an unauthenticated user can execute some methods of administrator controller without needing any credentials. Particular method execution will result in arbitrary YAML file creation or content change of existing YAML files on the system. Successfully exploitation of that vulnerability results in configuration changes, such as general site information change, custom scheduler job definition, etc. Due to the nature of the vulnerability, an adversary can change some part of the webpage, or hijack an administrator account, or execute operating system command under the context of the web-server user. This vulnerability is fixed in version 1.10.8. Blocking access to the `/admin` path from untrusted sources can be applied as a workaround.

- [https://github.com/s1lentf00thold/CVE-2021-21425-RCE](https://github.com/s1lentf00thold/CVE-2021-21425-RCE) :  ![starts](https://img.shields.io/github/stars/s1lentf00thold/CVE-2021-21425-RCE.svg) ![forks](https://img.shields.io/github/forks/s1lentf00thold/CVE-2021-21425-RCE.svg)


## CVE-2020-2026
 A malicious guest compromised before a container creation (e.g. a malicious guest image or a guest running multiple containers) can trick the kata runtime into mounting the untrusted container filesystem on any host path, potentially allowing for code execution on the host. This issue affects: Kata Containers 1.11 versions earlier than 1.11.1; Kata Containers 1.10 versions earlier than 1.10.5; Kata Containers 1.9 and earlier versions.

- [https://github.com/blackjack550/vigil](https://github.com/blackjack550/vigil) :  ![starts](https://img.shields.io/github/stars/blackjack550/vigil.svg) ![forks](https://img.shields.io/github/forks/blackjack550/vigil.svg)


## CVE-2019-2215
 A use-after-free in binder.c allows an elevation of privilege from an application to the Linux Kernel. No user interaction is required to exploit this vulnerability, however exploitation does require either the installation of a malicious local application or a separate vulnerability in a network facing application.Product: AndroidAndroid ID: A-141720095

- [https://github.com/mythicaltree/CVE-2019-2215](https://github.com/mythicaltree/CVE-2019-2215) :  ![starts](https://img.shields.io/github/stars/mythicaltree/CVE-2019-2215.svg) ![forks](https://img.shields.io/github/forks/mythicaltree/CVE-2019-2215.svg)


## CVE-2019-0232
 When running on Windows with enableCmdLineArguments enabled, the CGI Servlet in Apache Tomcat 9.0.0.M1 to 9.0.17, 8.5.0 to 8.5.39 and 7.0.0 to 7.0.93 is vulnerable to Remote Code Execution due to a bug in the way the JRE passes command line arguments to Windows. The CGI Servlet is disabled by default. The CGI option enableCmdLineArguments is disable by default in Tomcat 9.0.x (and will be disabled by default in all versions in response to this vulnerability). For a detailed explanation of the JRE behaviour, see Markus Wulftange's blog (https://codewhitesec.blogspot.com/2016/02/java-and-command-line-injections-in-windows.html) and this archived MSDN blog (https://web.archive.org/web/20161228144344/https://blogs.msdn.microsoft.com/twistylittlepassagesallalike/2011/04/23/everyone-quotes-command-line-arguments-the-wrong-way/).

- [https://github.com/blackjuker2/CVE-2019-0232](https://github.com/blackjuker2/CVE-2019-0232) :  ![starts](https://img.shields.io/github/stars/blackjuker2/CVE-2019-0232.svg) ![forks](https://img.shields.io/github/forks/blackjuker2/CVE-2019-0232.svg)


## CVE-2015-4852
 The WLS Security component in Oracle WebLogic Server 10.3.6.0, 12.1.2.0, 12.1.3.0, and 12.2.1.0 allows remote attackers to execute arbitrary commands via a crafted serialized Java object in T3 protocol traffic to TCP port 7001, related to oracle_common/modules/com.bea.core.apache.commons.collections.jar. NOTE: the scope of this CVE is limited to the WebLogic Server product.

- [https://github.com/roo7break/serialator](https://github.com/roo7break/serialator) :  ![starts](https://img.shields.io/github/stars/roo7break/serialator.svg) ![forks](https://img.shields.io/github/forks/roo7break/serialator.svg)
- [https://github.com/zhzhdoai/Weblogic_Vuln](https://github.com/zhzhdoai/Weblogic_Vuln) :  ![starts](https://img.shields.io/github/stars/zhzhdoai/Weblogic_Vuln.svg) ![forks](https://img.shields.io/github/forks/zhzhdoai/Weblogic_Vuln.svg)
- [https://github.com/minhangxiaohui/Weblogic_direct_T3_Rces](https://github.com/minhangxiaohui/Weblogic_direct_T3_Rces) :  ![starts](https://img.shields.io/github/stars/minhangxiaohui/Weblogic_direct_T3_Rces.svg) ![forks](https://img.shields.io/github/forks/minhangxiaohui/Weblogic_direct_T3_Rces.svg)
- [https://github.com/AndersonSingh/serialization-vulnerability-scanner](https://github.com/AndersonSingh/serialization-vulnerability-scanner) :  ![starts](https://img.shields.io/github/stars/AndersonSingh/serialization-vulnerability-scanner.svg) ![forks](https://img.shields.io/github/forks/AndersonSingh/serialization-vulnerability-scanner.svg)
- [https://github.com/nex1less/CVE-2015-4852](https://github.com/nex1less/CVE-2015-4852) :  ![starts](https://img.shields.io/github/stars/nex1less/CVE-2015-4852.svg) ![forks](https://img.shields.io/github/forks/nex1less/CVE-2015-4852.svg)

