# Password Policy Audit

## 1. Introduction

The purpose of this project is to examine password policies, identify weak rules, and recommend practical improvements based on NIST guidance.

## 2. Comparison with NIST Guidance

NIST stands for the National Institute of Standards and Technology.

According to NIST SP 800-63B-4:

* Passwords used as a single authentication factor should have at least 15 characters.
* Systems should support password managers.
* Common and compromised passwords should be blocked.
* Routine password changes should not be required without a reason.
* Multi-factor authentication helps protect accounts.

Reference: https://pages.nist.gov/800-63-4/sp800-63b.html

## 3. Weak Password Rules

### Rule 1: Changing passwords every 30 days

Reason: Frequent changes can encourage predictable variations of existing passwords.

Improvement: Change passwords when compromise is suspected or confirmed.

### Rule 2: Requiring special characters

Reason: Strict character-composition rules can encourage predictable patterns.

Improvement: Focus on password length and block common passwords.

### Rule 3: Allowing only eight characters

Reason: Eight characters is below the NIST minimum for passwords used as a single authentication factor.

Improvement: Require at least 15 characters for single-factor passwords.

### Rule 4: Prohibiting password managers

Reason: Users may struggle to remember many unique passwords.

Improvement: Allow approved password managers.

### Rule 5: Allowing common passwords

Reason: Common passwords are easier to guess.

Improvement: Block common, expected, and compromised passwords.

## 4. Improved Password Policy

1. Require at least 15 characters for single-factor passwords.
2. Allow long passphrases and spaces.
3. Do not require specific combinations of character types.
4. Block commonly used and compromised passwords.
5. Support password managers.
6. Do not require routine password changes without a reason.
7. Require password changes when compromise is suspected or confirmed.
8. Enable multi-factor authentication where appropriate.
9. Store passwords securely using suitable salted password-hashing methods.
10. Protect login systems against repeated password-guessing attempts.

## 5. One-Page Staff Guide

### How to Protect Your Passwords

* Use long passwords or memorable passphrases.
* Use a unique password for every account.
* Use an approved password manager.
* Never share your password.
* Enable multi-factor authentication.
* Avoid common passwords and personal information.
* Change your password if it is compromised.
* Report suspicious account activity to IT support.

### Remember

Long, unique passwords, password managers, and multi-factor authentication help protect your accounts.

## 6. Conclusion

Effective password policies should improve security without creating unnecessary difficulties for users. Long passwords, password managers, compromised-password screening, and multi-factor authentication provide a practical approach to password security.
# password-policy-audit
A password policy audit comparing sample password rules with NIST guidance, identifying weaknesses, and proposing an improved policy with a staff guide.
