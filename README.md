This repository contains 90 regex tasks divided into three parts: Beginner, Intermediate, and Advanced.  
Each task is implemented as a separate Python code cell and can be run in Jupyter Notebook.

 Parts Overview

Part 1 – Beginner (Basic Matching & Searching, 30 Tasks)
 Focuses on simple pattern matching, searching, and extraction.
 Covers letters, digits, uppercase/lowercase, vowels/consonants, and basic validations.
 Introduces core regex concepts like character classes `[a-zA-Z]`, digits `\d`, whitespace `\s`, anchors `^ $`, and basic quantifiers.

Part 2 – Intermediate (Groups, Quantifiers, Special Sequences, 30 Tasks)
Uses grouping, capturing, replacements, and validations.
 Practical tasks include **email parsing, password validation, currency extraction, HTML tag handling, date/time matching.
 Teaches quantifiers `{n}`, `+`, `*`, word boundaries `\b`, and special sequences.

Part 3 – Advanced (Lookarounds, Backreferences, Performance, 30 Tasks)
 Uses lookaheads `(?=...)`, lookbehinds `(?<=...)`, negative lookarounds `(?!...)`, and backreferences `\1`.
 Tasks include **overlapping matches, repeated sequences, palindromes, IP/MAC/URL validation, HTML comment extraction, and advanced pattern parsing**.
 Focused on precise extraction and real-world data validation.



 How to Use
1. Open this repository in Jupyter Notebook.
2. Each task is in a separate code cell with example input and output.
3. Run the cells one by one to see the results.
4. Modify the sample text to practice with your own data.



Key Regex Concepts Covered
Character Classes: `[a-z]`, `[A-Z]`, `[0-9]`
Anchors:`^` (start), `$` (end)
Quantifiers: `+`, `*`, `{n}`, `{n,}`, `{n,m}`
Groups & Backreferences: `()`, `\1`
Lookarounds: `(?=...)`, `(?!...)`, `(?<=...)`, `(?<!...)`
Special Sequences: `\d`, `\w`, `\s`, `\b`
Substitution & Replacement: `re.sub()`
Validation Patterns:Emails, URLs, passwords, phone numbers, IPs, MAC addresses, credit cards.
