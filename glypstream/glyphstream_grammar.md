# GlyphStream Grammar & Syntax Guide (v1.0)

## Core Structures

### 1. Basic Phrase
- `[L][O][L]=[L]` (Logogram Operator Logogram = Result)
  - Ex: ☀️➕🌙＝✨ (sun+moon=star)

### 2. Variable Assignment
- `X＝[Phrase]`
  - Ex: X＝☀️➕🌙

### 3. Variable Recall/Substitution
- Use assigned variable in new phrase
  - Ex: X➕🖤＝💢

### 4. Conditional & Fallback
- `[X]❓＝A／B`
  - Ex: Y❓＝💢／❔ (Y, if condition, equals anger, else unknown)
- Max fallback chain: 3 slashes, then ⬛ (rest/null)

### 5. Parentheses/Nesting
- `( ... )` to group operations
  - Ex: (☀️➕🌙)❓🖤＝🌀

### 6. Function/Macro
- `F(X)＝[Phrase]` (define function)
- `F(Y)` (invoke function)
  - Ex: F(X)＝X➕✨ ; Z＝F(Y)

### 7. Choice/Arbitration
- `🎲` or `🤔` operator: resolves ambiguity by roll or reader prompt
  - Ex: X🎲＝A／B (roll to pick A or B)

## Operator List
- ➕, ➖, ✖️, ➗, ＝, ❓, ／, 🎲, ⬛, 0️⃣, ⚫, 🌑, ( )

## Null/Zero/Origin Conventions
- ⬛ = null/rest (pause, undefined)
- 0️⃣ = zero/reset (begin/start)
- ⚫/🌑 = origin/potential

## Ambiguity & Rest
- If ambiguity unresolved: use 🎲/🤔 or ⬛ after 3 fallbacks

## Version & Audit
- Version, date, author, and summary logged at top of every file

