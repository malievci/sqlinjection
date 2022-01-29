# sqlinjection
Sql injection is one of top 10 vulnerabilities of Owasp.
Any type of injection occurs when user supplied data send to an interpreter as part of a command or query
It can be Sql, Ldap or any type of script injection

- Sql injection with Postgresql where use attack payloads
- NoSql injection with MongoDB where show different type of nosql injections
- Ldap injection with OpenLDAP where different attack payloads that can be used as LDAP injection attack
- Log injection with various attack payloads
- CSV Injection (Formule injection attack with Excel file)

Programming language is Java and I will use Spring boot
First, I develop vulnerable web applications (exploitable), then mitigate the vulnerability and prevent the attaack.
Note that I create a reusable login module to use it from the applications that will do the real exploiting in the injections section
