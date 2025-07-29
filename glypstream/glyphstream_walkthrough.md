# GlyphStream Walkthrough (v1.0)

## Example 1: Simple Addition
- **Input:** ☀️➕🌙＝✨
- **Decoded:** Sun + Moon = Star (synthesis, creation)

## Example 2: Variable Assignment/Recall
- **Input:**
  - X＝☀️➕🌙
  - X➕🖤＝💢
- **Decoded:**
  - X = sun+moon
  - X + shadow = anger/disruption

## Example 3: Conditional with Fallback
- **Input:**
  - Y＝X➕🖤
  - Y❓＝💢／❔
- **Decoded:**
  - Y = X + shadow
  - If Y matches anger, output 💢; else, ❔ (unknown)

## Example 4: Nested Parentheses
- **Input:** (☀️➕🌙)❓🖤＝🌀
- **Decoded:** Sun+moon grouped, in shadow/question context, yields spiral/recursion

## Example 5: Macro/Function Use
- **Input:**
  - F(X)＝X➕✨
  - Z＝F(Y)
  - Y＝X➕🖤
  - X＝☀️➕🌙
  - Z❓＝🌀／❔
- **Decoded:**
  - Define F(X) as X+star
  - Z = F(Y) = (sun+moon+shadow)+star
  - Query: Is Z a spiral? If not, unknown

## Error Handling/Rest Example
- If outcome is ambiguous or not mapped, output ⬛ (rest) after 3 fallback attempts.

---
*Use these as a quick reference or for translator training.*
