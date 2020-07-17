# Table of contents

* [HackTricks](README.md)
* [Pentesting Methodology](pentesting-methodology.md)
* [About the author](about-the-author.md)
* [Exfiltration](exfiltration.md)
* [Tunneling and Port Forwarding](tunneling-and-port-forwarding.md)
* [Brute Force - CheatSheet](brute-force.md)
* [Search Exploits](search-exploits.md)

## Shells

* [Shells \(Linux, Windows, MSFVenom\)](shells/shells/README.md)
  * [MSFVenom - CheatSheet](shells/shells/untitled.md)
  * [Shells - Windows](shells/shells/windows.md)
  * [Shells - Linux](shells/shells/linux.md)

## Linux/Unix

* [Checklist - Linux Privilege Escalation](linux-unix/linux-privilege-escalation-checklist.md)
* [Linux Privilege Escalation](linux-unix/privilege-escalation/README.md)
  * [Interesting Groups - Linux PE](linux-unix/privilege-escalation/interesting-groups-linux-pe.md)
  * [NFS no\_root\_squash/no\_all\_squash misconfiguration PE](linux-unix/privilege-escalation/nfs-no_root_squash-misconfiguration-pe.md)
  * [lxc - Privilege escalation](linux-unix/privilege-escalation/lxd-privilege-escalation.md)
  * [Escaping from restricted shells - Jails](linux-unix/privilege-escalation/escaping-from-limited-bash.md)
  * [SSH Forward Agent exploitation](linux-unix/privilege-escalation/ssh-forward-agent-exploitation.md)
  * [Payloads to execute](linux-unix/privilege-escalation/payloads-to-execute.md)
  * [Wildcards Spare tricks](linux-unix/privilege-escalation/wildcards-spare-tricks.md)
* [Useful Linux Commands](linux-unix/useful-linux-commands/README.md)
  * [Bypass Bash Restrictions](linux-unix/useful-linux-commands/bypass-bash-restrictions.md)
* [Linux Environment Variables](linux-unix/linux-environment-variables.md)

## Windows

* [Checklist - Local Windows Privilege Escalation](windows/checklist-windows-privilege-escalation.md)
* [Windows Local Privilege Escalation](windows/windows-local-privilege-escalation/README.md)
  * [Dll Hijacking](windows/windows-local-privilege-escalation/dll-hijacking.md)
  * [From High Integrity to SYSTEM with Name Pipes](windows/windows-local-privilege-escalation/from-high-integrity-to-system-with-name-pipes.md)
  * [Named Pipe Client Impersonation](windows/windows-local-privilege-escalation/named-pipe-client-impersonation.md)
  * [Leaked Handle Exploitation](windows/windows-local-privilege-escalation/leaked-handle-exploitation.md)
  * [SeDebug + SeImpersonate copy token](windows/windows-local-privilege-escalation/sedebug-+-seimpersonate-copy-token.md)
  * [MSI Wrapper](windows/windows-local-privilege-escalation/msi-wrapper.md)
  * [JuicyPotato](windows/windows-local-privilege-escalation/juicypotato.md)
  * [Windows C Payloads](windows/windows-local-privilege-escalation/windows-c-payloads.md)
  * [PowerUp](windows/windows-local-privilege-escalation/powerup.md)
  * [JAWS](windows/windows-local-privilege-escalation/jaws.md)
  * [Seatbelt](windows/windows-local-privilege-escalation/seatbelt.md)
  * [RottenPotato](windows/windows-local-privilege-escalation/rottenpotato.md)
* [Active Directory Methodology](windows/active-directory-methodology/README.md)
  * [Abusing Active Directory ACLs/ACEs](windows/active-directory-methodology/acl-persistence-abuse.md)
  * [AD information in printers](windows/active-directory-methodology/ad-information-in-printers.md)
  * [ASREPRoast](windows/active-directory-methodology/asreproast.md)
  * [BloodHound](windows/active-directory-methodology/bloodhound.md)
  * [Constrained Delegation](windows/active-directory-methodology/constrained-delegation.md)
  * [Custom SSP](windows/active-directory-methodology/custom-ssp.md)
  * [DCShadow](windows/active-directory-methodology/dcshadow.md)
  * [DCSync](windows/active-directory-methodology/dcsync.md)
  * [DSRM Credentials](windows/active-directory-methodology/dsrm-credentials.md)
  * [Golden Ticket](windows/active-directory-methodology/golden-ticket.md)
  * [Kerberos Authentication](windows/active-directory-methodology/kerberos-authentication.md)
  * [Kerberoast](windows/active-directory-methodology/kerberoast.md)
  * [MSSQL Trusted Links](windows/active-directory-methodology/mssql-trusted-links.md)
  * [Over Pass the Hash/Pass the Key](windows/active-directory-methodology/over-pass-the-hash-pass-the-key.md)
  * [Pass the Ticket](windows/active-directory-methodology/pass-the-ticket.md)
  * [Password Spraying](windows/active-directory-methodology/password-spraying.md)
  * [Printers Spooler Service abuse](windows/active-directory-methodology/printers-spooler-service-abuse.md)
  * [Privileged Accounts and Token Privileges](windows/active-directory-methodology/privileged-accounts-and-token-privileges.md)
  * [Resource-based Constrained Delegation](windows/active-directory-methodology/resource-based-constrained-delegation.md)
  * [Security Descriptors](windows/active-directory-methodology/security-descriptors.md)
  * [Silver Ticket](windows/active-directory-methodology/silver-ticket.md)
  * [Skeleton Key](windows/active-directory-methodology/skeleton-key.md)
  * [Unconstrained Delegation](windows/active-directory-methodology/unconstrained-delegation.md)
* [NTLM](windows/ntlm/README.md)
  * [Places to steal NTLM creds](windows/ntlm/places-to-steal-ntlm-creds.md)
  * [PsExec/Winexec/ScExec](windows/ntlm/psexec-and-winexec.md)
  * [SmbExec/ScExec](windows/ntlm/smbexec.md)
  * [WmicExec](windows/ntlm/wmicexec.md)
  * [AtExec / SchtasksExec](windows/ntlm/atexec.md)
  * [WinRM](windows/ntlm/winrm.md)
* [Stealing Credentials](windows/stealing-credentials/README.md)
  * [Credentials Protections](windows/stealing-credentials/credentials-protections.md)
  * [Mimikatz](windows/stealing-credentials/credentials-mimikatz.md)
* [Authentication, Credentials, Token privileges, UAC and EFS](windows/credentials.md)
* [Basic CMD for Pentesters](windows/basic-cmd-for-pentesters.md)
* [Basic PowerShell for Pentesters](windows/basic-powershell-for-pentesters/README.md)
  * [PowerView](windows/basic-powershell-for-pentesters/powerview.md)
* [AV Bypass](windows/av-bypass.md)

## Mobile Apps Pentesting

* [Android APK Checklist](mobile-apps-pentesting/android-checklist.md)
* [Android Applications Pentesting](mobile-apps-pentesting/android-app-pentesting/README.md)
  * [ADB Commands](mobile-apps-pentesting/android-app-pentesting/adb-commands.md)
  * [APK decompilers](mobile-apps-pentesting/android-app-pentesting/apk-decompilers.md)
  * [Burp Suite Configuration for Android](mobile-apps-pentesting/android-app-pentesting/android-burp-suite-settings.md)
  * [Drozer Tutorial](mobile-apps-pentesting/android-app-pentesting/drozer-tutorial/README.md)
    * [Exploiting Content Providers](mobile-apps-pentesting/android-app-pentesting/drozer-tutorial/exploiting-content-providers.md)
  * [Exploiting a debuggeable applciation](mobile-apps-pentesting/android-app-pentesting/exploiting-a-debuggeable-applciation.md)
  * [Frida Tutorial](mobile-apps-pentesting/android-app-pentesting/frida-tutorial/README.md)
    * [Frida Tutorial 1](mobile-apps-pentesting/android-app-pentesting/frida-tutorial/frida-tutorial-1.md)
    * [Frida Tutorial 2](mobile-apps-pentesting/android-app-pentesting/frida-tutorial/frida-tutorial-2.md)
    * [Frida Tutorial 3](mobile-apps-pentesting/android-app-pentesting/frida-tutorial/owaspuncrackable-1.md)
    * [Objection Tutorial](mobile-apps-pentesting/android-app-pentesting/frida-tutorial/objection-tutorial.md)
  * [Google CTF 2018 - Shall We Play a Game?](mobile-apps-pentesting/android-app-pentesting/google-ctf-2018-shall-we-play-a-game.md)
  * [Manual DeObfuscation](mobile-apps-pentesting/android-app-pentesting/manual-deobfuscation.md)
  * [Reversing Native Libraries](mobile-apps-pentesting/android-app-pentesting/reversing-native-libraries.md)
  * [Smali - Decompiling/\[Modifying\]/Compiling](mobile-apps-pentesting/android-app-pentesting/smali-changes.md)
  * [Spoofing your location in Play Store](mobile-apps-pentesting/android-app-pentesting/spoofing-your-location-in-play-store.md)
  * [Webview Attacks](mobile-apps-pentesting/android-app-pentesting/webview-attacks.md)
  * [What are Intents](mobile-apps-pentesting/android-app-pentesting/what-are-intents.md)

## Pentesting

* [Pentesting Network](pentesting/pentesting-network/README.md)
  * [Spoofing LLMNR, NBT-NS, mDNS/DNS and WPAD and Relay Attacks](pentesting/pentesting-network/spoofing-llmnr-nbt-ns-mdns-dns-and-wpad-and-relay-attacks.md)
  * [Spoofing SSDP and UPnP Devices with EvilSSDP](pentesting/pentesting-network/spoofing-ssdp-and-upnp-devices.md)
  * [Wifi Attacks](pentesting/pentesting-network/wifi-attacks/README.md)
    * [Evil Twin EAP-TLS](pentesting/pentesting-network/wifi-attacks/evil-twin-eap-tls.md)
  * [Pentesting IPv6](pentesting/pentesting-network/pentesting-ipv6.md)
  * [Nmap Summary \(ESP\)](pentesting/pentesting-network/nmap-summary-esp.md)
  * [Network Protocols Explained \(ESP\)](pentesting/pentesting-network/network-protocols-explained-esp.md)
  * [IDS and IPS Evasion](pentesting/pentesting-network/ids-evasion.md)
  * [DHCPv6](pentesting/pentesting-network/dhcpv6.md)
* [Pentesting JDWP - Java Debug Wire Protocol](pentesting/pentesting-jdwp-java-debug-wire-protocol.md)
* [Pentesting Printers](pentesting/pentesting-printers/README.md)
  * [Accounting bypass](pentesting/pentesting-printers/accounting-bypass.md)
  * [Buffer Overflows](pentesting/pentesting-printers/buffer-overflows.md)
  * [Credentials Disclosure / Brute-Force](pentesting/pentesting-printers/credentials-disclosure-brute-force.md)
  * [Cross-Site Printing](pentesting/pentesting-printers/cross-site-printing.md)
  * [Document Processing](pentesting/pentesting-printers/document-processing.md)
  * [Factory Defaults](pentesting/pentesting-printers/factory-defaults.md)
  * [File system access](pentesting/pentesting-printers/file-system-access.md)
  * [Firmware updates](pentesting/pentesting-printers/firmware-updates.md)
  * [Memory Access](pentesting/pentesting-printers/memory-access.md)
  * [Physical Damage](pentesting/pentesting-printers/physical-damage.md)
  * [Software packages](pentesting/pentesting-printers/software-packages.md)
  * [Transmission channel](pentesting/pentesting-printers/transmission-channel.md)
  * [Print job manipulation](pentesting/pentesting-printers/print-job-manipulation.md)
  * [Print Job Retention](pentesting/pentesting-printers/print-job-retention.md)
  * [Scanner and Fax](pentesting/pentesting-printers/scanner-and-fax.md)
* [7/tcp/udp - Pentesting Echo](pentesting/7-tcp-udp-pentesting-echo.md)
* [21 - Pentesting FTP](pentesting/pentesting-ftp/README.md)
  * [FTP Bounce attack - Scan](pentesting/pentesting-ftp/ftp-bounce-attack.md)
  * [FTP Bounce - Download 2ºFTP file](pentesting/pentesting-ftp/ftp-bounce-download-2oftp-file.md)
* [22 - Pentesting SSH/SFTP](pentesting/pentesting-ssh.md)
* [23 - Pentesting Telnet](pentesting/pentesting-telnet.md)
* [25,465,587 - Pentesting SMTP/s](pentesting/pentesting-smtp/README.md)
  * [SMTP - Commands](pentesting/pentesting-smtp/smtp-commands.md)
* [43 - Pentesting WHOIS](pentesting/43-pentesting-whois.md)
* [53 - Pentesting DNS](pentesting/pentesting-dns.md)
* [69/UDP TFTP/Bittorrent-tracker](pentesting/69-udp-tftp.md)
* [79 - Pentesting Finger](pentesting/pentesting-finger.md)
* [80,443 - Pentesting Web Methodology](pentesting/pentesting-web/README.md)
  * [Apache](pentesting/pentesting-web/apache.md)
  * [JSP](pentesting/pentesting-web/jsp.md)
  * [API Pentesting](pentesting/pentesting-web/api-pentesting.md)
  * [Buckets](pentesting/pentesting-web/buckets/README.md)
    * [Firebase Database](pentesting/pentesting-web/buckets/firebase-database.md)
    * [AWS-S3](pentesting/pentesting-web/buckets/aws-s3.md)
  * [CGI](pentesting/pentesting-web/cgi.md)
  * [Drupal](pentesting/pentesting-web/drupal.md)
  * [Flask](pentesting/pentesting-web/flask.md)
  * [Git](pentesting/pentesting-web/git.md)
  * [GraphQL](pentesting/pentesting-web/graphql.md)
  * [H2 - Java SQL database](pentesting/pentesting-web/h2-java-sql-database.md)
  * [IIS - Internet Information Services](pentesting/pentesting-web/iis-internet-information-services.md)
  * [JBOSS](pentesting/pentesting-web/jboss.md)
  * [Jenkins](pentesting/pentesting-web/jenkins.md)
  * [JIRA](pentesting/pentesting-web/jira.md)
  * [Joomla](pentesting/pentesting-web/joomla.md)
  * [Nginx](pentesting/pentesting-web/nginx.md)
  * [PHP Tricks \(SPA\)](pentesting/pentesting-web/php-tricks-esp/README.md)
    * [PHP - Useful Functions \(disabled bypass\)](pentesting/pentesting-web/php-tricks-esp/php-useful-functions.md)
  * [Python](pentesting/pentesting-web/python.md)
  * [Tomcat](pentesting/pentesting-web/tomcat.md)
  * [VMWare \(ESX, VCenter...\)](pentesting/pentesting-web/vmware-esx-vcenter....md)
  * [WebDav](pentesting/pentesting-web/put-method-webdav.md)
  * [Wordpress](pentesting/pentesting-web/wordpress.md)
* [88tcp/udp - Pentesting Kerberos](pentesting/pentesting-kerberos-88/README.md)
  * [Harvesting tickets from Windows](pentesting/pentesting-kerberos-88/harvesting-tickets-from-windows.md)
  * [Harvesting tickets from Linux](pentesting/pentesting-kerberos-88/harvesting-tickets-from-linux.md)
* [110,995 - Pentesting POP](pentesting/pentesting-pop.md)
* [111/TCP/UDP - Pentesting Portmapper](pentesting/pentesting-rpcbind.md)
* [113 - Pentesting Ident](pentesting/113-pentesting-ident.md)
* [123/udp - Pentesting NTP](pentesting/pentesting-ntp.md)
* [135, 593 - Penstesting MSRPC](pentesting/135-penstesting-msrpc.md)
* [137,138,139 - Pentesting NetBios](pentesting/137-138-139-pentesting-netbios.md)
* [139,445 - Pentesting SMB](pentesting/pentesting-smb.md)
* [143,993 - Pentesting IMAP](pentesting/pentesting-imap.md)
* [161,162,10161,10162/udp - Pentesting SNMP](pentesting/pentesting-snmp.md)
* [194,6667,6660-7000 - Pentesting IRC](pentesting/pentesting-irc.md)
* [264 - Pentesting Check Point FireWall-1](pentesting/pentesting-264-check-point-firewall-1.md)
* [389, 636, 3268, 3269 - Pentesting LDAP](pentesting/pentesting-ldap.md)
* [500/udp - Pentesting IPsec/IKE VPN](pentesting/ipsec-ike-vpn-pentesting.md)
* [502 - Pentesting Modbus](pentesting/pentesting-modbus.md)
* [512 - Pentesting Rexec](pentesting/512-pentesting-rexec.md)
* [513 - Pentesting Rlogin](pentesting/pentesting-rlogin.md)
* [514 - Pentesting Rsh](pentesting/pentesting-rsh.md)
* [515 - Pentesting Line Printer Daemon \(LPD\)](pentesting/515-pentesting-line-printer-daemon-lpd.md)
* [548 - Pentesting Apple Filing Protocol \(AFP\)](pentesting/584-pentesting-afp.md)
* [554,8554 - Pentesting RTSP](pentesting/554-8554-pentesting-rtsp.md)
* [623/UDP/TCP - IPMI](pentesting/623-udp-ipmi.md)
* [631 - Internet Printing Protocol\(IPP\)](pentesting/pentesting-631-internet-printing-protocol-ipp.md)
* [873 - Pentesting Rsync](pentesting/873-pentesting-rsync.md)
* [1026 - Pentesting Rusersd](pentesting/1026-pentesting-rusersd.md)
* [1098/1099 - Pentesting Java RMI](pentesting/1099-pentesting-java-rmi.md)
* [1433 - Pentesting MSSQL - Microsoft SQL Server](pentesting/pentesting-mssql-microsoft-sql-server.md)
* [1521,1522-1529 - Pentesting Oracle TNS Listener](pentesting/1521-1522-1529-pentesting-oracle-listener/README.md)
  * [Oracle Pentesting requirements installation](pentesting/1521-1522-1529-pentesting-oracle-listener/oracle-pentesting-requirements-installation.md)
  * [TNS Poison](pentesting/1521-1522-1529-pentesting-oracle-listener/tns-poison.md)
  * [Remote stealth pass brute force](pentesting/1521-1522-1529-pentesting-oracle-listener/remote-stealth-pass-brute-force.md)
  * [Oracle RCE & more](pentesting/1521-1522-1529-pentesting-oracle-listener/oracle-rce-and-more.md)
* [1723 - Pentesting PPTP](pentesting/1723-pentesting-pptp.md)
* [1883 - Pentesting MQTT \(Mosquitto\)](pentesting/1883-pentesting-mqtt-mosquitto.md)
* [2049 - Pentesting NFS Service](pentesting/nfs-service-pentesting.md)
* [2301,2381 - Pentesting Compaq/HP Insight Manager](pentesting/pentesting-compaq-hp-insight-manager.md)
* [3260 - Pentesting ISCSI](pentesting/3260-pentesting-iscsi.md)
* [3299 - Pentesting SAPRouter](pentesting/3299-pentesting-saprouter.md)
* [3306 - Pentesting Mysql](pentesting/pentesting-mysql.md)
* [3389 - Pentesting RDP](pentesting/pentesting-rdp.md)
* [3632 - Pentesting distcc](pentesting/3632-pentesting-distcc.md)
* [4369 - Pentesting Erlang Port Mapper Daemon \(epmd\)](pentesting/4369-pentesting-erlang-port-mapper-daemon-epmd.md)
* [5353/UDP Multicast DNS \(mDNS\)](pentesting/5353-udp-multicast-dns-mdns.md)
* [5432,5433 - Pentesting Postgresql](pentesting/pentesting-postgresql.md)
* [5671,5672 - Pentesting AMQP](pentesting/5671-5672-pentesting-amqp.md)
* [5800,5801,5900,5901 - Pentesting VNC](pentesting/pentesting-vnc.md)
* [5984,6984 - Pentesting CouchDB](pentesting/5984-pentesting-couchdb.md)
* [5985,5986 - Pentesting WinRM](pentesting/5985-5986-pentesting-winrm.md)
* [6000 - Pentesting X11](pentesting/6000-pentesting-x11.md)
* [6379 - Pentesting Redis](pentesting/6379-pentesting-redis.md)
* [8009 - Pentesting Apache JServ Protocol \(AJP\)](pentesting/8009-pentesting-apache-jserv-protocol-ajp.md)
* [9042/9160 - Pentesting Cassandra](pentesting/cassandra.md)
* [9100 - Pentesting Raw Printing \(JetDirect, AppSocket, PDL-datastream\)](pentesting/9100-pjl.md)
* [9200 - Pentesting Elasticsearch](pentesting/9200-pentesting-elasticsearch.md)
* [10000 - Pentesting Network Data Management Protocol \(ndmp\)](pentesting/10000-network-data-management-protocol-ndmp.md)
* [11211 - Pentesting Memcache](pentesting/11211-memcache.md)
* [15672 - Pentesting RabbitMQ Management](pentesting/15672-pentesting-rabbitmq-management.md)
* [27017,27018 - Pentesting MongoDB](pentesting/27017-27018-mongodb.md)
* [44818/UDP/TCP - Pentesting EthernetIP](pentesting/44818-ethernetip.md)
* [47808/udp - Pentesting BACNet](pentesting/47808-udp-bacnet.md)
* [50030,50060,50070,50075,50090 - Pentesting Hadoop](pentesting/50030-50060-50070-50075-50090-pentesting-hadoop.md)

## Pentesting Web

* [2FA Bypass](pentesting-web/2fa-bypass.md)
* [Abusing hop-by-hop headers](pentesting-web/abusing-hop-by-hop-headers.md)
* [Captcha Bypass](pentesting-web/captcha-bypass.md)
* [Cache Poisoning and Cache Deception](pentesting-web/cache-deception.md)
* [Clickjacking](pentesting-web/clickjacking.md)
* [Client Side Template Injection \(CSTI\)](pentesting-web/client-side-template-injection-csti.md)
* [Command Injection](pentesting-web/command-injection.md)
* [Content Security Policy \(CSP\) Bypass](pentesting-web/content-security-policy-csp-bypass.md)
* [Cookies Hacking](pentesting-web/hacking-with-cookies.md)
* [CORS - Misconfigurations & Bypass](pentesting-web/cors-bypass.md)
* [CRLF \(%0D%0A\) Injection](pentesting-web/crlf-0d-0a.md)
* [Cross-site WebSocket hijacking \(CSWSH\)](pentesting-web/cross-site-websocket-hijacking-cswsh.md)
* [CSRF \(Cross Site Request Forgery\)](pentesting-web/csrf-cross-site-request-forgery.md)
* [Dangling Markup - HTML scriptless injection](pentesting-web/dangling-markup-html-scriptless-injection.md)
* [Deserialization](pentesting-web/deserialization/README.md)
  * [NodeJS deserialization \_\_proto\_\_ abuse](pentesting-web/deserialization/nodejs-deserialization-__proto__-abuse.md)
  * [Java JSF ViewState \(.faces\) Deserialization](pentesting-web/deserialization/java-jsf-viewstate-.faces-deserialization.md)
  * [Java DNS Deserialization, GadgetProbe and Java Deserialization Scanner](pentesting-web/deserialization/java-dns-deserialization-and-gadgetprobe.md)
  * [Basic Java Deserialization \(ObjectInputStream, readObject\)](pentesting-web/deserialization/basic-java-deserialization-objectinputstream-readobject.md)
  * [CommonsCollection1 Payload - Java Transformers to Rutime exec\(\) and Thread Sleep](pentesting-web/deserialization/java-transformers-to-rutime-exec-payload.md)
  * [Basic .Net deserialization \(ObjectDataProvider gadget, ExpandedWrapper, and Json.Net\)](pentesting-web/deserialization/basic-.net-deserialization-objectdataprovider-gadgets-expandedwrapper-and-json.net.md)
  * [Exploiting \_\_VIEWSTATE parameter](pentesting-web/deserialization/exploiting-__viewstate-parameter.md)
* [Email Header Injection](pentesting-web/email-header-injection.md)
* [File Inclusion/Path traversal](pentesting-web/file-inclusion.md)
* [File Upload](pentesting-web/file-upload.md)
* [HTTP Request Smuggling / HTTP Desync Attack](pentesting-web/http-request-smuggling.md)
* [IDOR](pentesting-web/idor.md)
* [JWT Vulnerabilities \(Json Web Tokens\)](pentesting-web/hacking-jwt-json-web-tokens.md)
* [NoSQL injection](pentesting-web/nosql-injection.md)
* [LDAP Injection](pentesting-web/ldap-injection.md)
* [OAuth to Account takeover](pentesting-web/oauth-to-account-takeover.md)
* [Open Redirect](pentesting-web/open-redirect.md)
* [Race Condition](pentesting-web/race-condition.md)
* [Rate Limit Bypass](pentesting-web/rate-limit-bypass.md)
* [SQL Injection](pentesting-web/sql-injection/README.md)
  * [MSSQL Injection](pentesting-web/sql-injection/mssql-injection.md)
  * [Oracle injection](pentesting-web/sql-injection/oracle-injection.md)
  * [PostgreSQL injection](pentesting-web/sql-injection/postgresql-injection/README.md)
    * [dblink/lo\_import data exfiltration](pentesting-web/sql-injection/postgresql-injection/dblink-lo_import-data-exfiltration.md)
    * [PL/pgSQL Password Bruteforce](pentesting-web/sql-injection/postgresql-injection/pl-pgsql-password-bruteforce.md)
    * [Network - Privesc, Port Scanner and NTLM chanllenge response disclosure](pentesting-web/sql-injection/postgresql-injection/network-privesc-port-scanner-and-ntlm-chanllenge-response-disclosure.md)
    * [Big Binary Files Upload \(PostgreSQL\)](pentesting-web/sql-injection/postgresql-injection/big-binary-files-upload-postgresql.md)
    * [RCE with PostgreSQL Extensions](pentesting-web/sql-injection/postgresql-injection/rce-with-postgresql-extensions.md)
  * [MySQL injection](pentesting-web/sql-injection/mysql-injection/README.md)
    * [Mysql SSRF](pentesting-web/sql-injection/mysql-injection/mysql-ssrf.md)
  * [SQLMap - Cheetsheat](pentesting-web/sql-injection/sqlmap.md)
* [SSRF \(Server Side Request Forgery\)](pentesting-web/ssrf-server-side-request-forgery.md)
* [SSTI \(Server Side Template Injection\)](pentesting-web/ssti-server-side-template-injection.md)
* [Domain/Subdomain takeover](pentesting-web/domain-subdomain-takeover.md)
* [Unicode Normalization vulnerability](pentesting-web/unicode-normalization-vulnerability.md)
* [Web Tool - WFuzz](pentesting-web/web-tool-wfuzz.md)
* [XPATH injection](pentesting-web/xpath-injection.md)
* [XSLT Server Side Injection \(Extensible Stylesheet Languaje Transformations\)](pentesting-web/xslt-server-side-injection-extensible-stylesheet-languaje-transformations.md)
* [XXE - XEE - XML External Entity](pentesting-web/xxe-xee-xml-external-entity.md)
* [XSS \(Cross Site Scripting\)](pentesting-web/xss-cross-site-scripting/README.md)
  * [DOM XSS](pentesting-web/xss-cross-site-scripting/dom-xss.md)
  * [Server Side XSS \(Dynamic PDF\)](pentesting-web/xss-cross-site-scripting/server-side-xss-dynamic-pdf.md)
  * [XSS Tools](pentesting-web/xss-cross-site-scripting/xss-tools.md)
* [XSSI \(Cross-Site Script Inclusion\)](pentesting-web/xssi-cross-site-script-inclusion.md)
* [XS-Search](pentesting-web/xs-search.md)

## Physical attacks

* [Physical Attacks](physical-attacks/physical-attacks.md)
* [Escaping from KIOSKs](physical-attacks/escaping-from-gui-applications/README.md)
  * [Show file extensions](physical-attacks/escaping-from-gui-applications/show-file-extensions.md)

## Exploiting

* [Linux Exploiting \(Basic\) \(SPA\)](exploiting/linux-exploiting-basic-esp/README.md)
  * [ROP - Syscall execv](exploiting/linux-exploiting-basic-esp/rop-syscall-execv.md)
  * [ROP - Leaking LIBC address](exploiting/linux-exploiting-basic-esp/rop-leaking-libc-address.md)
  * [Bypassing Canary & PIE](exploiting/linux-exploiting-basic-esp/bypassing-canary-and-pie.md)
  * [Ret2Lib](exploiting/linux-exploiting-basic-esp/ret2lib.md)
  * [Fusion](exploiting/linux-exploiting-basic-esp/fusion.md)
* [Exploiting Tools](exploiting/tools/README.md)
  * [PwnTools](exploiting/tools/pwntools.md)
* [Windows Exploiting \(Basic Guide - OSCP lvl\)](exploiting/windows-exploiting-basic-guide-oscp-lvl.md)
* [Reversing](exploiting/reversing.md)

## Forensics

* [Malware Analysis](forensics/malware-analysis.md)
* [Memory dump analysis](forensics/memory-dump-analysis.md)
* [Pcaps analysis](forensics/pcaps-analysis/README.md)
  * [USB Keyboard pcap analysis](forensics/pcaps-analysis/usb-keyboard-pcap-analysis.md)
  * [DNSCat pcap analysis](forensics/pcaps-analysis/dnscat-exfiltration.md)
  * [WireShark tricks](forensics/pcaps-analysis/wireshark-tricks.md)
* [Volatility - Examples](forensics/volatility-examples.md)
* [Basic Forensics \(ESP\)](forensics/basic-forensics-esp/README.md)
  * [USB logs analysis](forensics/basic-forensics-esp/usb-logs-analysis.md)
  * [Desofuscation vbs \(cscript.exe\)](forensics/basic-forensics-esp/desofuscation-vbs-cscript.exe.md)
  * [.pyc](forensics/basic-forensics-esp/.pyc.md)
  * [Office file analysis](forensics/basic-forensics-esp/office-file-analysis.md)
  * [Video and Audio file analysis](forensics/basic-forensics-esp/video-and-audio-file-analysis.md)
  * [PDF File analysis](forensics/basic-forensics-esp/pdf-file-analysis.md)
  * [File System Analysis](forensics/basic-forensics-esp/file-system-analysis.md)
  * [PNG tricks](forensics/basic-forensics-esp/png-tricks.md)
  * [ZIPs tricks](forensics/basic-forensics-esp/zips-tricks.md)

## Crypto

* [Electronic Code Book \(ECB\)](crypto/electronic-code-book-ecb.md)
* [Cipher Block Chaining CBC-MAC](crypto/cipher-block-chaining-cbc-mac-priv.md)
* [Padding Oracle](crypto/padding-oracle-priv.md)
* [RC4 - Encrypt&Decrypt](crypto/rc4-encrypt-and-decrypt.md)
* [Crypto CTFs Tricks](crypto/crypto-ctfs-tricks.md)

## BACKDOORS

* [Merlin](backdoors/merlin.md)
* [Empire](backdoors/empire.md)
* [Salseo](backdoors/salseo.md)
* [ICMPsh](backdoors/icmpsh.md)

## Stego

* [Stego Tricks](stego/stego-tricks.md)
* [Esoteric languages](stego/esoteric-languages.md)

## MISC

* [Basic Python](misc/basic-python/README.md)
  * [Bypass Python sandboxes](misc/basic-python/bypass-python-sandboxes.md)
  * [Magic Methods](misc/basic-python/magic-methods.md)
  * [Web Requests](misc/basic-python/web-requests.md)
  * [Bruteforce hash \(few chars\)](misc/basic-python/bruteforce-hash-few-chars.md)
  * [ROP-PWN template](misc/basic-python/rop-pwn-template.md)
* [Other Big References](misc/references.md)

## TODO

* [More Tools](todo/more-tools.md)
* [MISC](todo/misc.md)
* [Pentesting DNS](todo/pentesting-dns.md)

---

* [Burp Suite](burp-suite.md)
* [Other Web Tricks](other-web-tricks.md)
* [Interesting HTTP](interesting-http.md)
* [Emails Vulnerabilities](emails-vulns.md)
* [Bug Bounties Methodology](bug-bounties-methodology.md)
* [Cloud security review](cloud-security-review.md)
* [Android Forensics](android-forensics.md)
* [TR-069](tr-069.md)
* [6881/udp - Pentesting BitTorrent](6881-udp-pentesting-bittorrent.md)
* [CTF Write-ups](ctf-write-ups/README.md)
  * [Try Hack Me](ctf-write-ups/try-hack-me/README.md)
    * [hc0n Christmas CTF - 2019](ctf-write-ups/try-hack-me/hc0n-christmas-ctf-2019.md)
    * [Pickle Rick](ctf-write-ups/try-hack-me/pickle-rick.md)
* [1911 - Pentesting fox](1911-pentesting-fox.md)
* [Online Platforms with API](online-platforms-with-api.md)
