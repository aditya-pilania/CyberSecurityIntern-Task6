# 🔐 Task 6 – Password Strength Evaluation

## 📝 Objective
Understand the characteristics of a strong password and test various passwords using free online strength checkers. Learn how password complexity affects overall security and how to defend against common password attacks.

---

## 🔧 Tools Used
- [Kaspersky Password Checker](https://www.passwordmeter.com)
- [LastPass Password Generator](https://www.lastpass.com/features/password-generator)
---

## 🔢 Passwords Tested

| S.No | Password              | Complexity Level | Strength (%) | Feedback |
|------|------------------------|------------------|--------------|----------|
| 1    | `password123`          | Low              | 25%          | Common, easy to guess |
| 2    | `P@ssw0rd2024`         | Medium           | 60%          | Better, but still predictable |
| 3    | `B!gBr@in$#9876`        | Passphrase Style             | 85%          | Strong: symbols, upper, lower, numbers |
| 4    | `A7#pM!c@Lu$T19z&x`     | Very High        | 100%         | Excellent: random, long, very hard to guess |
| 5    | `Tr33$Fly!in2025`       | Passphrase Style | 90%          | Very good: dictionary-resistant, creative |

---

## 📊 Summary of Observations

- **Password Length Matters**: Longer passwords (12+ characters) are significantly stronger.
- **Mix of Characters**: Using uppercase, lowercase, numbers, and symbols increases entropy.
- **Avoid Common Patterns**: Passwords like `password123`, `admin@123`, or keyboard patterns (`qwerty`) are easily cracked.
- **Randomization Wins**: The more random and less meaningful your password is, the harder it is to guess.
- 
---

## 🔒 Best Practices for Creating Strong Passwords

1. Use **at least 12–16 characters**.
2. Mix uppercase (`A–Z`), lowercase (`a–z`), digits (`0–9`), and special characters (`!@#$%`).
3. **Avoid real words, names, dates, or keyboard patterns.**
4. Use **passphrases** (e.g., `B1ueD0g$Jumps^Hi`) for memorability with strength.
5. Consider using a **Password Manager** to store and generate strong passwords.
6. Enable **Multi-Factor Authentication (MFA)** wherever available.

---

## 🛡️ Common Password Attacks Explained

### 1. **Brute Force Attack**
- Tries all possible character combinations until the correct one is found.
- Countermeasure: Use long, complex passwords and MFA.

### 2. **Dictionary Attack**
- Uses a precompiled list of common passwords and word combinations.
- Countermeasure: Avoid using dictionary words or predictable formats.

### 3. **Credential Stuffing**
- Attackers use leaked username-password combinations on multiple sites.
- Countermeasure: Don't reuse passwords and enable MFA.

---

## 🔐 What is Multi-Factor Authentication (MFA)?
MFA adds an extra layer of security by requiring:
1. Something you know (password)
2. Something you have (phone, OTP)
3. Something you are (fingerprint, face)

Even if your password is compromised, MFA helps protect your account.

---

## 🧠 What are Passphrases?
Passphrases are long combinations of unrelated words or phrases. Example:  
`PurpleGiraffe#Skates!Highway22`

- Easier to remember
- Still secure if constructed correctly

---

## ❌ Common Password Mistakes

- Reusing the same password on multiple platforms
- Using personal information like birthdates or names
- Short passwords (<8 characters)
- Simple substitutions like `pa$$word` instead of `password`

---
