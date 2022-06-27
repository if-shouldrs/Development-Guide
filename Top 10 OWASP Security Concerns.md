Check the official link [here](https://owasp.org/Top10/).

# 1. Broken Access Control
Users cannot act outside their intended permissions. Can lead to unauthorized information disclosure, modification or destruction of all data, or simply performing tasks they shouldn't be able to perform.

# 2. Cryptographic Failures
If you're working with sensitive data (determine that first) you have to ensure all cryptographic measures are working as intended. You should keep track of everywhere you handle sensitive data on all projects you maintain to ensure you know to update it when necessary.

Check a more detailed list of steps [here](https://owasp.org/Top10/A02_2021-Cryptographic_Failures/).

# 3. Injection
The most common form is non-validated user input, but can happen anywhere where data is processed even within internal calls where user input is not expected but can land. Read more [here](https://owasp.org/Top10/A03_2021-Injection/).

# 4. Insecure Design
Even with perfect implementation, an insecurely designed application remains insecure. Secure software requires a secure development lifecycle, paved road methodology, tooling, and threat modeling. Reach out for your security specialists if you have doubts about the security of your design. Read more [here]().

# 5. Security Misconfiguration
The more different pieces of configurable software you use the more likely it is one of them will not be configured securely and that may compromise your security. Make sure you pay attention to configuration permissions of everything you add, but for more read [here](https://owasp.org/Top10/A05_2021-Security_Misconfiguration/).

# 6. Vulnerable and Outdated Components
Please read [the official documentation](https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/), I can't do it justice. Basically vet every component you use and automate processes so that when an update happens or a vulnerability is discovered you are notified to act accordingly. But please read the documentation.

# 7. Identification and Authentication Failures
Ensure only secure passwords are accepted, protect against bruteforcing and automated attacks, use proper password recovery mechanisms, properly validate session IDs, always generate new IDs on login and don't expose session IDs in the URL. Read more [here](https://owasp.org/Top10/A07_2021-Identification_and_Authentication_Failures/).

# 8. Software and Data Integrity Failures
This is similar to Injection, but applies more broadly as imported data and software/libraries can have vulnerabilities and should be confirmed as secure. Feels very similar to #6 too but the official documentation has different points so read it [here](https://owasp.org/Top10/A08_2021-Software_and_Data_Integrity_Failures/).

# 9. Security Logging and Monitoring Failures
You need proper logging and monitoring of your software to know if a security breach is being exploited or if there's an attack being performed. Proper guidelines are described [here](https://owasp.org/Top10/A09_2021-Security_Logging_and_Monitoring_Failures/).

# 10. Server-Side Request Forgery (SSRF)
SSRF flaws occur whenever a web application is fetching a remote resource without validating the user-supplied URL. It allows an attacker to coerce the application to send a crafted request to an unexpected destination, even when protected by a firewall, VPN, or another type of network access control list (ACL). Read more [here](https://owasp.org/Top10/A10_2021-Server-Side_Request_Forgery_%28SSRF%29/).
