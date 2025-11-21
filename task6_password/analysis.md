# Analysis for Task 6 — Password Strength Investigation

## 1. What I tested
I created multiple passwords with varying complexity and length, including:
- short common word
- longer passphrase
- mixed-case plus numbers and symbols
- obvious patterns (for demonstration why they are weak)

## 2. Passwords generated for testing (examples)
1. `password` — common and weak (lowercase word).
2. `Password123` — adds capitalization and numbers, still weak (predictable).
3. `Tr0ub4dor&3` — mixed character types and leet substitutions.
4. `7h3-V0y@g3r-Needs-8` — longer, mixed types, dash separators.
5. `horse battery staple correct` — passphrase style (spaces make it longer & memorable).

> Tip: Do not reuse these exact passwords for real accounts. They are examples for learning.

## 3. What I looked for in the strength checker
- Password length (longer is better).
- Use of lower/upper-case letters, digits, symbols.
- Unpredictability (not dictionary words or common substitutions).
- Entropy feedback, estimated crack time (if provided).
- Suggestions provided by the tool (e.g., avoid common words, add length).

## 4. Findings (summary)
- `password` -> **Very weak**. Found in dictionaries, trivial for brute force/dictionary.
- `Password123` -> **Weak/Moderate**. Predictable pattern with common digits.
- `Tr0ub4dor&3` -> **Moderate/Strong** depending on tool; substitution helps but common pattern reduces benefit.
- `7h3-V0y@g3r-Needs-8` -> **Strong** due to length and mixed characters.
- `horse battery staple correct` -> **Strong** as a passphrase because of length and randomness of words.

## 5. Best Practices (derived from testing)
- Prefer length (passphrases with 4+ random words).
- Include upper/lowercase, digits, and symbols if possible.
- Avoid dictionary words or famous phrases by themselves.
- Use a password manager to create & store long random passwords.
- Enable multi-factor authentication (MFA) wherever possible.
