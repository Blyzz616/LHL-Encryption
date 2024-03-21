Report to be presented to the company's board, and delivered to all the tech teams.

## Executive Summary:
In today's world, it's crucial to keep our sensitive information safe and protect our employees. As the new Cyber Security Manager, I've reviewed our current security measures and come up with a solid plan to make them stronger. This report explains the important methods we'll use to keep our employees and company data secure.

## Password Re-Use Policy[^1]
Instituting a password re-use policy is essential to mitigate the risk of credential stuffing attacks, where cybercriminals exploit reused passwords across multiple accounts. By prohibiting the reuse of passwords across different platforms or systems, we can minimize the likelihood of unauthorized access in the event of a data breach.

### Recommendation
Implementing a password history policy that retains the previous 24 passwords used by users enhances security by preventing the reuse of recent passwords. By enforcing a robust password history requirement, we can minimize the risk of users cycling through a limited set of passwords, thereby increasing the likelihood of compromised credentials. This measure strengthens our overall password security posture and reduces the vulnerability to password-related attacks.

## Strong Passwords
Implementing strong password policies is foundational to cybersecurity. Passwords should be complex, comprising a combination of alphanumeric characters, symbols, and upper/lowercase letters. Additionally, enforcing regular password updates enhances security by minimizing the risk of compromised credentials. Remembering passwords is often seen as the main cause for using weak passwords. This can be addressed by the next point.

### Recommendation
Enforcing a minimum password length of 8 characters, including numbers, upper and lower case letters, and special characters, ensures that passwords are more resilient to brute-force attacks. By incorporating a diverse range of characters into passwords, we increase the entropy and make them more resistant to automated password cracking techniques. This approach enhances the overall security of our authentication system and reduces the likelihood of successful password-based attacks.

## Password Managers
Implementing password managers offers a convenient and secure solution for managing complex passwords across various accounts. Password managers generate and store unique, strong passwords for each user account, eliminating the need for users to remember multiple passwords. Additionally, password managers often incorporate features such as encrypted storage and two-factor authentication (2FA), further enhancing security.

### Recommendation
Bitwarden is a secure password management solution that offers encrypted storage for passwords, secure sharing options, and multi-device synchronization. By adopting Bitwarden as our password manager, we can centralize password management, streamline access to accounts, and strengthen password security practices across the organization. Bitwarden's robust encryption ensures that sensitive credentials are protected both in transit and at rest, mitigating the risk of unauthorized access or exposure.

## Incorporating Compromised Password Databases
Integrating compromised password databases, such as those compiled from data breaches, into our authentication systems can prevent users from utilizing passwords that have been compromised or exposed in previous security incidents. By cross-referencing user passwords with known compromised credentials, we can proactively identify and mitigate potential security risks associated with reused or compromised passwords.

### Recommendation
The "Have I Been Pwned" (HIBP) API provides access to a database of breached credentials, allowing organizations to check whether user passwords have been compromised in known data breaches. By integrating the HIBP API into our authentication systems, we can proactively identify compromised passwords and prevent users from using them, thereby reducing the risk of unauthorized access due to compromised credentials. This proactive approach strengthens our overall security posture and enhances our ability to mitigate the impact of data breaches.

## Password Expiration Policy
Enforcing password expiration policies ensures that passwords are regularly updated, reducing the likelihood of unauthorized access due to compromised credentials. Regularly changing passwords is a proactive measure to mitigate security risks associated with prolonged exposure.

### Recommendation
Enforcing a minimum password age of 1 day and a maximum password age of 90 days enhances security by ensuring that users regularly update their passwords while preventing frequent changes that could lead to predictable patterns or weak passwords. The minimum password age requirement prevents users from changing their passwords too frequently, reducing the risk of password cycling. Conversely, the maximum password age requirement ensures that passwords are regularly refreshed, minimizing the likelihood of compromised credentials due to prolonged exposure. By implementing these password age policies, we strike a balance between security and usability, promoting good password hygiene practices across the organization.

## Multi-Factor Authentication
MFA adds an additional layer of security by requiring users to verify their identity through multiple factors, such as passwords, biometrics, or one-time codes. This significantly reduces the risk of unauthorized access, even if passwords are compromised.

### Recommendation
Cisco Access by Duo is a multi-factor authentication solution that provides an additional layer of security for accessing our corporate network and resources. By leveraging Cisco Access by Duo, we can enhance authentication security by requiring users to verify their identities through multiple factors, such as passwords and biometrics, before granting access. This robust MFA solution strengthens our defenses against unauthorized access attempts and reduces the risk of credential-based attacks, such as phishing and brute force attacks. Additionally, Cisco Access by Duo offers seamless integration with existing systems and supports a wide range of authentication methods, ensuring compatibility and ease of use for our employees.

## Secure Email with Personal Certificate
Secure email protocols, coupled with personal certificates, provide end-to-end encryption, ensuring the confidentiality and integrity of sensitive information transmitted via email. Personal certificates authenticate the sender's identity and encrypt the email content, mitigating the risk of interception or tampering.

### Recommendation
ProtonMail is a secure email service that offers end-to-end encryption, ensuring the confidentiality and integrity of email communications. By leveraging ProtonMail, we can enhance the security of our email correspondence by encrypting messages and attachments, thereby mitigating the risk of interception or tampering. Additionally, ProtonMail provides features such as zero-access encryption, which means only the intended recipient can decrypt and access the contents of the email, further bolstering our email security posture.

## VPN IPSec on Laptops
Implementing VPNs (Virtual Private Networks) with IPSec (Internet Protocol Security) on laptops establishes a secure encrypted connection between remote devices and our corporate network. This safeguards data transmitted over public networks, mitigating the risk of interception or unauthorized access by malicious actors.

### Recommendation
Cisco AnyConnect VPN is a robust and versatile VPN solution that offers secure remote access to corporate networks and resources. By adopting Cisco AnyConnect, we can provide our employees with a reliable and flexible VPN client that supports multiple VPN protocols, including SSL/TLS and IPsec. This allows users to connect securely to our corporate network from anywhere, using any device, while ensuring data confidentiality, integrity, and authentication.

## Encrypted Hard and Flash Disks
Encrypting hard and flash disks on portable/mobile devices ensures that data stored on these devices remains protected, even if the devices are lost or stolen. Encryption converts data into ciphertext, rendering it unreadable without the corresponding decryption key, thereby safeguarding sensitive information.

### Recommendation
VeraCrypt is a highly secure, free, and open-source disk encryption software that offers strong encryption capabilities for protecting sensitive data on hard drives and flash disks. By adopting VeraCrypt, we can ensure that data stored on endpoints and portable devices remains encrypted and secure, even in the event of loss or theft. VeraCrypt supports a variety of encryption algorithms, including AES, Serpent, and Twofish, and provides features such as hidden volumes for added security.

## More on Bitwarden
**Centralized Security:** Easily manage access permissions and security policies, and maintain an eagle-eye view of user activity throughout your organization. By centralizing security management, we can ensure consistent enforcement of security policies and swiftly respond to any potential threats or breaches.

**Directory Integration:** Streamline IT operations by automatically provisioning and de-provisioning user accounts throughout the entire employee lifecycle. Integrating Bitwarden with our directory services enables seamless user management, ensuring that access permissions are accurately maintained and updated.

**Secure Sharing:** Empower employees to securely share credentials and other sensitive data from anywhere, on any device. Bitwarden's secure sharing capabilities facilitate collaboration while maintaining the confidentiality and integrity of shared information, reducing the risk of data leaks or unauthorized access.

**Two-Step Login (2FA):** Enable and enforce organization-wide two-factor authentication with Duo MFA. Double down on security without compromising convenience. By implementing two-factor authentication (2FA) with Bitwarden, we add an extra layer of protection to user accounts, significantly reducing the risk of unauthorized access, even in the event of compromised credentials.

**Note:** Bitwarden's Duo is not the same as Cisco's Duo.

## Conclusion:
Incorporating these additional cybersecurity measures further strengthens our defense against evolving threats and reinforces our commitment to protecting our employees and company information. By implementing comprehensive password policies, leveraging password managers, and integrating compromised password databases, we can mitigate the risk of unauthorized access and enhance our overall security posture.

Thank you for your continued support and commitment to cybersecurity. Should you have any further questions or require additional information, please feel free to reach out.

Sincerely,
Jim Sher 
Cyber Security Manager


##Citations
[^1]Microsoft (n.d.). Enforce Password History. Microsoft Learn. Retrieved March 20, 2024, from https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/security-policy-settings/enforce-password-history

Microsoft (n.d.). Minimum Password Length. Microsoft Learn. Retrieved March 20, 2024, from https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/security-policy-settings/minimum-password-length

Harvard (n.d.). Create a Strong Password. Use Strong Passwords. Retrieved March 20, 2024, from https://security.harvard.edu/use-strong-passwords

BitWarden (n.d.). The password manager trrusted by millions. Bitwarden. Retrieved March 20, 2024, from https://bitwarden.com/

Have I Been Pwned (n.d.). ';--have i been pwned. Have I Been Pwned. Retrieved March 20, 2024, from https://haveibeenpwned.com/API/v3

Microsoft (n.d.). Maximum password age. Microsoft Learn. Retrieved March 20, 2024, from https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/security-policy-settings/maximum-password-age

Microsoft (n.d.). Minimum Password Age. Microsoft Learn. Retrieved March 20, 2024, from https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/security-policy-settings/minimum-password-age

Cisco (n.d.). Duo: Cisco's Secure Access. Cisco Duo. Retrieved March 20, 2024, from https://www.cisco.com/c/en_ca/products/security/duo/index.html#~software-benefits

Proton (n.d.). How Safe is Proton Mail? Proton: Privacy by Default. Retrieved March 20, 2024, from https://proton.me/mail/security

Cisco (n.d.). Cisco AnyConnect Secure Mobility Client v4.X. Cisco AnyConnect. Retrieved March 20, 2024, from https://www.cisco.com/c/en/us/support/security/anyconnect-secure-mobility-client-v4-x/model.html

VeraCrypt (n.d.). Vera Crypt. Retrieved March 20, 2024, from https://www.veracrypt.fr/en/Home.html
