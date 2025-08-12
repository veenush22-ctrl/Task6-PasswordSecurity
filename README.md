# Task 6 – Password Security Analysis

## 1. Introduction
Passwords are the primary security barrier protecting our online accounts and sensitive information. A weak password can be easily cracked using automated tools, leaving accounts vulnerable to unauthorized access. This report evaluates multiple passwords of varying complexity using online password strength checkers and provides best practices for creating secure passwords.

---

## 2. Passwords Tested
(*Note: For safety, some characters are replaced with `*`.*)

| Password (Hidden)     | Length | Complexity Level | Purpose |
|-----------------------|--------|------------------|---------|
| pa****123             | 8      | Low              | Weak password test |
| Ve****2024            | 10     | Medium           | Medium password test |
| V3****@2024!          | 12     | High             | Strong password test |
| M*****#pT2@K9&        | 15     | Very High        | Very strong password test |

---

## 3. Results Table

| Password # | Strength Score | Feedback from Tool |
|------------|----------------|--------------------|
| 1          | 43% (Weak)     | Too short, lacks complexity |
| 2          | 78% (Medium)   | Add symbols & increase length |
| 3          | 100% (Strong)   | Good complexity, could be longer |
| 4          | 100% (Very Strong) | Excellent length & complexity |
---

## 4. Best Practices Learned
- Use **at least 12–16 characters** for stronger protection.
- Include **uppercase letters, lowercase letters, numbers, and symbols**.
- Avoid personal information or predictable sequences (e.g., `1234`, `abcd`).
- Use **random passphrases** (e.g., `BlueTiger#RunsFast!2024`).
- Change passwords periodically and never reuse the same password across multiple accounts.
- Enable **Multi-Factor Authentication (MFA)** for added security.

---

## 5. Common Password Attacks

- **Brute Force Attack**  
  An attacker tries all possible combinations until the correct password is found. Longer and more complex passwords make this attack impractical.

- **Dictionary Attack**  
  The attacker uses a list of common words, phrases, or previously leaked passwords to guess the password. Avoid dictionary words or simple combinations.

- **Phishing Attack**  
  Attackers impersonate trusted entities to trick users into revealing their passwords. Always verify links and websites before entering credentials.

---

## 6. Conclusion
Password strength directly impacts account security. Longer passwords with mixed character types significantly reduce the risk of being compromised. Combining a strong password with MFA provides robust protection against common cyber attacks.

---

## 7. Screenshots
Below are the password test results:

### Weak Password Test
![Weak Password Test](screenshots/password1_weak.png)

### Medium Password Test
![Medium Password Test](screenshots/password2_medium.png)

### Strong Password Test
![Strong Password Test](screenshots/password3_strong.png)

### Very Strong Password Test
![Very Strong Password Test](screenshots/password4_verystrong.png)

(Optional) Comparison Table:
![Comparison Table](screenshots/comparison_table.png)
