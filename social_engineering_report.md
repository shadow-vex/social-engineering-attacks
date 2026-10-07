# Social Engineering Attacks

## Research Report

**Prepared By:** Sathya V  
**Domain:** Cybersecurity  
**Report Type:** Research Report  
**Platform:** GitHub  
**Date:** October 2026

---

## 1. Introduction

Social engineering is a cybersecurity attack technique that manipulates people into revealing sensitive information, performing unauthorized actions, or providing access to systems and resources.

Unlike attacks that primarily exploit software vulnerabilities, social engineering focuses on exploiting human trust, emotions, habits, and decision-making.

The National Institute of Standards and Technology (NIST) describes social engineering as an attempt to deceive an individual into revealing information or taking an action that can be used to compromise or adversely affect a system. Social engineering includes techniques such as phishing, pretexting, baiting, and quid pro quo.

Social engineering is effective because attackers can exploit normal human behaviors such as trust, curiosity, urgency, fear, authority, and the desire to help others.

### 1.1 Why Social Engineering Is Effective

Attackers commonly use psychological techniques such as:

- **Trust:** Pretending to be a trusted person or organization.
- **Urgency:** Creating pressure to make the victim act quickly.
- **Authority:** Impersonating managers, IT staff, banks, or government officials.
- **Fear:** Threatening account suspension, financial loss, or disciplinary action.
- **Curiosity:** Using interesting information, files, or links to attract attention.
- **Reward:** Offering free software, money, gifts, or other benefits.
- **Reciprocity:** Offering assistance or a service in exchange for information.

NIST research on phishing awareness also highlights the importance of the human element in understanding why users may fall for phishing attempts and why security-awareness programs need to account for user context.

### 1.2 Scope of the Research

This report focuses on four important social engineering techniques:

1. Phishing
2. Pretexting
3. Baiting
4. Quid Pro Quo

The report also examines documented real-world incidents and provides practical prevention recommendations for individuals and organizations.

---

# 2. Phishing

## 2.1 Definition

Phishing is a form of social engineering in which attackers use fraudulent emails, messages, websites, phone calls, or other communication methods to impersonate trusted entities and manipulate victims.

The primary objectives may include:

- Stealing usernames and passwords
- Capturing authentication information
- Delivering malware
- Obtaining financial information
- Redirecting users to malicious websites
- Gaining access to organizational systems

CISA identifies phishing as a form of social engineering and describes several forms including spearphishing, whaling, vishing, and smishing.

---

## 2.2 How Phishing Works

A typical phishing attack can follow these stages:

### Step 1: Target Identification

The attacker identifies a person or organization that may provide valuable access or information.

### Step 2: Information Gathering

The attacker may collect publicly available information about the target, such as:

- Name
- Job position
- Organization
- Email address
- Department
- Public social media information

### Step 3: Message Creation

The attacker creates a convincing message that appears to come from a legitimate organization or individual.

Examples include:

- Banking alerts
- Password reset notifications
- IT support requests
- Delivery notifications
- Account verification messages
- Job-related communications

### Step 4: Psychological Manipulation

The message may create:

- Urgency
- Fear
- Curiosity
- Authority
- Financial pressure

### Step 5: Victim Interaction

The victim may:

- Click a malicious link
- Open an attachment
- Enter credentials
- Download software
- Provide confidential information

### Step 6: Attacker Exploitation

The attacker uses the collected information to access accounts, steal data, deploy malware, or continue the attack.

---

## 2.3 Types of Phishing

### 2.3.1 Spear Phishing

Spear phishing is a targeted form of phishing directed at a specific person or organization.

Instead of sending the same message to thousands of people, attackers customize the communication using information about the target.

For example, an attacker may impersonate an employee's manager and request an urgent document or account action.

---

### 2.3.2 Whaling

Whaling is phishing that specifically targets high-profile or senior individuals.

Common targets include:

- CEOs
- CFOs
- Directors
- Government officials
- Senior administrators

The goal is often to obtain high-value information, financial access, or privileged credentials.

---

### 2.3.3 Vishing

Vishing means voice phishing.

The attacker uses phone calls or voice communication to manipulate the victim.

Examples include pretending to be:

- Bank employees
- IT support personnel
- Government representatives
- Company administrators

Attackers may ask victims to verify account information, passwords, authentication codes, or other sensitive information.

---

### 2.3.4 Smishing

Smishing is phishing performed through SMS or text messaging.

Examples include fake:

- Bank alerts
- Delivery notifications
- Account warnings
- Prize notifications
- Login verification messages

The message usually contains a malicious link or asks the victim to contact the attacker.

---

## 2.4 Real-World Case Study: Twitter 2020 Attack

One of the most well-known examples of social engineering occurred at Twitter in July 2020.

Attackers targeted Twitter employees using social engineering and phishing techniques. According to WIRED's investigation, attackers contacted employees and attempted to convince them to provide access credentials.

Some employees were directed to a fraudulent website where their usernames, passwords, and multifactor authentication information were captured.

The attackers subsequently gained access to internal administrative tools and compromised high-profile Twitter accounts.

Approximately 130 accounts were targeted, with 45 accounts used to publish unauthorized tweets.

The attackers used several compromised accounts to promote a Bitcoin scam.

### Attack Method

The incident demonstrated a combination of:

- Phone-based social engineering
- Phishing
- Credential theft
- Impersonation
- Abuse of internal administrative privileges

### Impact

The attack demonstrated that compromising a small number of employees can potentially lead to access to highly privileged internal systems.

It also showed the importance of:

- Least privilege
- Strong authentication
- Employee awareness
- Verification procedures
- Administrative access controls

### Lesson Learned

Technical security controls alone are not enough when attackers successfully manipulate authorized users.

Organizations must protect both their systems and the people who operate them.

---

## 2.5 Phishing Prevention Recommendations

### 1. Verify Unexpected Requests

Users should independently verify unusual requests before providing credentials, transferring money, or changing account information.

### 2. Use Multi-Factor Authentication

MFA provides an additional layer of protection if a password is compromised.

Organizations should prefer phishing-resistant authentication methods where possible.

### 3. Inspect Links and Attachments

Users should carefully inspect:

- Sender addresses
- Website domains
- Unexpected attachments
- Suspicious links
- Unusual formatting

### 4. Report Suspicious Messages

Employees should have a simple method to report suspicious emails, messages, and calls.

Early reporting can help security teams identify and contain attacks.

---

# 3. Pretexting

## 3.1 Definition

Pretexting is a social engineering technique in which an attacker creates a false identity, situation, or story to obtain information or convince a victim to perform an action.

The attacker establishes a believable scenario before requesting sensitive information.

Examples include pretending to be:

- IT support
- A manager
- A bank employee
- A customer
- A delivery representative
- A government official

---

## 3.2 How Pretexting Works

A typical pretexting attack can involve:

### Step 1: Selecting a Target

The attacker identifies a person who has access to useful information or systems.

### Step 2: Creating a False Identity

The attacker chooses a believable role.

For example:

> "I am calling from the company's IT support team."

### Step 3: Building the Scenario

The attacker creates a reason for contacting the victim.

Examples:

- Password reset
- Account verification
- Technical problem
- Security investigation
- Urgent management request

### Step 4: Establishing Trust

The attacker may use publicly available information to make the story appear legitimate.

### Step 5: Requesting Information or Action

The attacker asks the victim to:

- Reveal information
- Reset a password
- Approve access
- Open a file
- Provide a verification code

### Step 6: Exploitation

The attacker uses the obtained information or access for further attacks.

---

## 3.3 Real-World Example

Pretexting and impersonation are commonly associated with attacks against help desks and technical-support personnel.

MITRE/OWASP CAPEC documentation describes pretexting through phone calls and technical support scenarios where an attacker assumes a trusted role and attempts to obtain information or manipulate a target into performing an action.

Help-desk staff can be particularly valuable targets because they may have legitimate procedures for password resets and account recovery.

---

## 3.4 Prevention Measures

### 1. Identity Verification

Employees should verify the identity of anyone requesting sensitive information or privileged actions.

Verification should use an independent communication channel when appropriate.

### 2. Follow Formal Procedures

Password resets, account recovery, and privilege changes should follow documented organizational procedures.

Employees should not bypass security processes because someone claims to be a manager or administrator.

### 3. Apply Least Privilege

Employees should only receive the access required for their job responsibilities.

Limiting privileges reduces the potential impact of successful social engineering.

---

# 4. Baiting

## 4.1 Definition

Baiting is a social engineering technique that uses an attractive or tempting item to encourage a victim to perform an unsafe action.

The bait may be:

- A physical USB device
- Free software
- A fake download
- A free document
- A reward
- A tempting online offer

The psychological techniques commonly involved are curiosity and reward.

---

## 4.2 Physical Baiting

Physical baiting uses tangible objects to attract victims.

A common example is an unknown USB drive.

An attacker may leave removable media in a location where employees are likely to find it.

A curious employee may connect the device to a computer, potentially exposing the system to malicious content.

Organizations should therefore control the use of unauthorized removable media.

---

## 4.3 Digital Baiting

Digital baiting uses online content to attract victims.

Examples include:

- Fake software
- Cracked applications
- Fake updates
- Free games
- Fake documents
- Pirated content
- Fake rewards

The victim is encouraged to download or open the content.

---

## 4.4 Real-World Case Study: Stuxnet and USB-Based Infection

The 2009 Stuxnet attack against Iran's nuclear infrastructure provides an important example of the security risks associated with removable media.

Research on the incident describes how USB drives were involved in introducing malware into an environment where critical systems were isolated from ordinary network connectivity.

The incident demonstrates an important security principle:

> An isolated network is not automatically safe if untrusted physical media can cross the security boundary.

The case also highlights the importance of controlling removable media and protecting endpoint systems.

---

## 4.5 Baiting Prevention Measures

### 1. Restrict Unauthorized USB Devices

Organizations should establish policies controlling the use of removable storage devices.

Where appropriate, technical controls can restrict unauthorized USB devices.

### 2. Do Not Use Unknown Devices

Employees should never connect an unknown USB drive to organizational computers.

Unknown devices should be submitted to the IT/security team for safe inspection.

### 3. Download Software Only From Trusted Sources

Employees should avoid downloading software from unknown websites or unofficial sources.

Software should be obtained from approved repositories or official vendor websites.

---

# 5. Quid Pro Quo

## 5.1 Definition

Quid pro quo is a social engineering technique in which an attacker offers something in exchange for information, access, or an action.

The phrase means approximately:

> "Something for something."

The attacker creates the expectation that the victim will receive a benefit after cooperating.

---

## 5.2 Examples

Examples include:

- Fake technical support
- Free software installation
- Fake security assistance
- Fake surveys offering rewards
- Fraudulent service offers
- Fake IT troubleshooting

For example, an attacker may contact an employee and claim that they are helping fix a technical problem. The attacker may then request credentials or other sensitive information.

---

## 5.3 Prevention

Organizations can reduce quid pro quo attacks by:

1. Verifying the identity of support personnel.
2. Never sharing passwords or authentication codes.
3. Using official IT support channels.
4. Training employees to recognize suspicious offers.
5. Requiring formal approval for privileged actions.

---

# 6. Comparison of Social Engineering Attacks

| Attack Type | Primary Target | Psychological Lever | Common Attack Method | Best Countermeasure |
|---|---|---|---|---|
| Phishing | Users / Employees | Trust + Urgency | Email / Web / Messages | Awareness + MFA |
| Spear Phishing | Specific Employees | Trust + Personalization | Targeted Email | Verification + MFA |
| Whaling | Executives | Authority + Urgency | Targeted Communication | Strong approval procedures |
| Vishing | Employees / Users | Trust + Authority | Phone Call | Identity Verification |
| Smishing | Mobile Users | Urgency + Fear | SMS | Link Verification |
| Pretexting | Employees / Support Staff | Authority + Trust | Phone / Email / In-person | Identity Verification |
| Baiting | Users | Curiosity + Reward | USB / Downloads | Device Controls |
| Quid Pro Quo | Employees / Users | Reciprocity | Fake Assistance | Verification + Awareness |

---

# 7. Organisational Security Awareness Recommendations

Organizations should develop a continuous security awareness program rather than relying on one-time training.

## 7.1 Employee Security Awareness Checklist

### 1. Recognize Suspicious Messages

Employees should learn to identify:

- Unknown senders
- Suspicious links
- Unexpected attachments
- Urgent requests
- Unusual payment requests
- Requests for credentials

### 2. Verify Unusual Requests

Employees should verify unexpected requests through trusted communication channels.

For example, if an executive requests a financial transfer, the employee should follow the organization's independent verification procedure.

### 3. Protect Credentials

Employees should:

- Never share passwords
- Never share MFA codes
- Use unique passwords
- Use approved password managers
- Enable MFA

### 4. Report Suspicious Activity

Organizations should provide an easy reporting mechanism.

Employees should be encouraged to report mistakes quickly rather than hide them.

Early reporting can reduce the time available to attackers.

### 5. Participate in Security Training

Organizations should conduct regular:

- Security awareness training
- Phishing simulations
- Social engineering exercises
- Incident reporting exercises

NIST recommends using structured approaches to phishing awareness and measuring the human element of phishing detection rather than treating training as a one-time activity.

---

# 8. Overall Prevention Strategy

A strong defense against social engineering should combine people, processes, and technology.

## 8.1 People

Organizations should:

- Provide regular security awareness training.
- Teach employees how social engineering works.
- Encourage employees to question unusual requests.
- Create a security-conscious culture.

## 8.2 Processes

Organizations should:

- Establish identity verification procedures.
- Define secure password-reset procedures.
- Require approval for sensitive transactions.
- Maintain incident-reporting procedures.
- Apply least privilege.

## 8.3 Technology

Organizations should use appropriate technical controls such as:

- Multi-Factor Authentication
- Phishing-resistant authentication
- Email security
- Endpoint protection
- Web filtering
- Device control
- Access control
- Security monitoring
- Logging and alerting

Technology should support employee awareness rather than replace it.

---

# 9. Key Security Lessons

The research highlights several important lessons.

### Lesson 1: Humans Are Part of the Attack Surface

Security systems can be bypassed when attackers manipulate authorized users.

### Lesson 2: Trust Must Be Verified

A request appearing to come from a trusted person does not automatically make it legitimate.

### Lesson 3: Urgency Should Trigger Verification

Urgent requests involving credentials, money, or privileged access should receive additional verification.

### Lesson 4: Least Privilege Limits Damage

Reducing unnecessary privileges can limit the impact of compromised accounts.

### Lesson 5: Reporting Is Critical

Employees should report suspicious activity immediately, even if they have already interacted with the attacker.

### Lesson 6: Security Awareness Must Be Continuous

Threats and attack techniques change over time. Security awareness should therefore be regularly updated.

---

# 10. Conclusion

Social engineering remains an important cybersecurity threat because it targets human decision-making rather than relying only on technical vulnerabilities.

Phishing, pretexting, baiting, and quid pro quo attacks use different psychological techniques, but their common objective is to manipulate victims into taking actions that benefit the attacker.

The Twitter 2020 incident demonstrates how targeted social engineering can provide attackers with access to highly privileged internal systems. The RSA SecurID incident demonstrates how a carefully crafted spear-phishing email and malicious attachment can be used as an entry point into an organization. The Stuxnet case demonstrates the security risks associated with removable media and isolated environments.

Effective defense requires a layered approach combining:

- Security awareness
- Identity verification
- Strong authentication
- Least privilege
- Technical controls
- Secure organizational procedures
- Rapid incident reporting

Ultimately, cybersecurity is not only a technical problem. People, processes, and technology must work together to reduce the risk of social engineering attacks.

---

# 11. References

1. **Cybersecurity and Infrastructure Security Agency (CISA)**  
   *Phishing – General Security Guidance*  
   https://www.cisa.gov/

2. **National Institute of Standards and Technology (NIST)**  
   *NIST Phish Scale User Guide – NIST Technical Note 2276*  
   https://www.nist.gov/publications/nist-phish-scale-user-guide

3. **NIST**  
   *Phishing With a Net: The NIST Phish Scale and Cybersecurity Awareness*  
   https://www.nist.gov/publications/phishing-net-nist-phish-scale-and-cybersecurity-awareness

4. **NIST / CSRC**  
   *Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations – NIST SP 800-171 Rev. 3*  
   https://csrc.nist.gov/

5. **SANS Institute**  
   *Top Three Ways Cyber Attackers Target You*  
   https://www.sans.org/newsletters/ouch/top-ways-attackers-target-you

6. **WIRED**  
   *Inside the Twitter Hack—and What Happened Next*  
   https://www.wired.com/story/inside-twitter-hack-election-plan/

7. **WIRED**  
   *How the Alleged Twitter Hackers Got Caught*  
   https://www.wired.com/story/how-alleged-twitter-hackers-got-caught-bitcoin/

8. **Dark Reading**  
   *RSA SecurID Attack Began With Excel File Rigged With Flash Zero-Day*  
   https://www.darkreading.com/cyberattacks-data-breaches/rsa-secureid-attack-began-with-excel-file-rigged-with-flash-zero-day

9. **Dark Reading**  
   *RSA Details SecurID Attack Mechanics*  
   https://www.darkreading.com/cyberattacks-data-breaches/rsa-details-securid-attack-mechanics

10. **SAGE Journals**  
    *Did a USB drive disrupt a nuclear program? A Defense in Depth teaching case*  
    https://doi.org/10.1177/20438869231200284

---

# 12. Disclaimer

This research report is intended strictly for educational and cybersecurity awareness purposes.

The report discusses social engineering techniques to improve defensive understanding and security awareness. It does not provide instructions for conducting unauthorized attacks or compromising systems.

All case studies referenced in this report are based on publicly documented security incidents and research.