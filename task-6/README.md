# Task 6: Create a Strong Password and Evaluate Its Strength

This task involved creating passwords of varying complexity levels and testing them with online password strength checkers to understand what makes a password truly secure. I learned how different password characteristics affect security and how dramatically password strength impacts crack resistance.

---

## Key Concepts I Explored

- **Password Composition:**  
  Tested how length, character variety, and randomness affect password strength across different complexity levels.

- **Password Testing Tools:**  
  Used passwordmeter.com and security.org to evaluate passwords from multiple perspectives - composition scoring vs. real-world crack time estimation.

- **Dictionary vs. Random Passwords:**  
  Compared passwords containing common words against completely random character combinations to understand vulnerability patterns.

- **Exponential Security Scaling:**  
  Discovered how adding just a few characters can transform crack time from months to quintillions of years.

- **Attack Method Awareness:**  
  Learned how different attack types (brute force, dictionary attacks, social engineering) target different password weaknesses.

---

## My Key Findings

- **Dramatic Security Differences:** A weak password "password123" (43% strength) takes only 1 month to crack, while a strong random password takes 42 quintillion years
- **Length is Exponential:** Adding 9 characters transformed security from 1 month to quintillions of years - length matters more than complexity alone
- **Dictionary Words are Fatal:** Even with numbers added, using "password" as a base made the password vulnerable to dictionary attacks
- **Tool Perspectives Vary:** PasswordMeter focuses on meeting complexity rules, while Security.org estimates actual crack resistance
- **Perfect Scores ≠ Equal Security:** Three passwords all scored 100% on PasswordMeter but had vastly different crack times (15 billion to 42 quintillion years)

---

## My Takeaways

- Password strength isn't just about meeting minimum requirements - it's about creating truly unpredictable combinations that resist real-world attacks.
- Dictionary words, even with modifications, create significant vulnerabilities that attackers can exploit.
- Length combined with randomness provides the best security - a lesson that reinforces the value of password managers.
- Understanding both the technical scoring and practical crack time helps make better security decisions.
- The exponential nature of password security means every additional character and complexity element dramatically improves protection.

---

For detailed testing process, screenshots, and complete analysis with actual crack time comparisons, see:

- [workflow.md](workflow.md) : step-by-step password testing with real results from both tools
