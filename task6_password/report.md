# Report — Password Strength Results (Task 6)

## Date:
$(date)

## Purpose:
Test multiple passwords for strength and explain why some are stronger than others.

## Passwords tested and results (copy these into an online password strength checker such as passwordmeter.com or similar and record the results):

### 1) password
- Type: single lowercase dictionary word
- Expected result: VERY WEAK
- Reason: common word found in dictionaries; short length.

### 2) Password123
- Type: word + simple digits
- Expected result: WEAK to MODERATE
- Reason: predictable pattern (capital first letter + '123') is common.

### 3) Tr0ub4dor&3
- Type: mixed-case, substitutions and symbol
- Expected result: MODERATE to STRONG (tool-dependent)
- Reason: substitutions help but some leetspeak is common and can be included in attacker rules.

### 4) 7h3-V0y@g3r-Needs-8
- Type: long, mixed characters, separators
- Expected result: STRONG
- Reason: long length + mixed character types increases entropy significantly.

### 5) horse battery staple correct
- Type: passphrase with spaces
- Expected result: STRONG
- Reason: high length and word randomness; very hard for brute force when words are random.

## How to test (manual steps for your browser)
1. Open your web browser (Firefox or Chrome).
2. Visit a free password strength checker such as `passwordmeter.com` (or another you trust).
3. Type/paste each password from above and note the score, suggestions, and any estimated crack time.
4. Copy those results below (or screenshot them and add to this folder).

## Example results (copy/paste your tool output here):
- `password` -> Score: very low; suggestions: increase length, avoid dictionary words.
- `Password123` -> Score: low; suggestions: avoid common patterns.
- `Tr0ub4dor&3` -> Score: medium; suggestions: increase length.
- `7h3-V0y@g3r-Needs-8` -> Score: high; suggestions: good length.
- `horse battery staple correct` -> Score: high; suggestions: consider adding symbol or numbers if required by site.

## Conclusion
Longer passwords and passphrases are the best balance of memorability and security. Combine length with unpredictability and store complex passwords in a password manager.
