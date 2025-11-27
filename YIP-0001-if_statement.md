# YIP-0001 — `if` Statement for Yr

**Author:** Yr Core Team
**Status:** Draft
**Type:** language
**Created:** 2025-01-02

---

## 1. Summary

This proposal adds a minimal `if` conditional expression to Yr, enabling basic
branching inside `nosection`.

---

## 2. Motivation

Yr currently offers no conditional logic.
Introducing `if` enables:

- simple dynamic behavior
- conditional wrappers
- programmatic generation of markup
- future foundations for loops and functions

This is the first step toward Yr becoming a full programming language.

---

## 3. Specification

Conditional logic based on environment (options.env).

### Tokens

* `??` is if and if else, followed by the name of variable

* `?_` is else

* `//` closes the conditional

* `::` for ternary, will be then

## 4. Examples

### Inline:

```yr
?? allow :: !! Ui/Password ?_ !! Ui/Login
```

### Multiline:

```yr
++

?? allow
  _ .green
?? warn
  _ .yellow
?_
  _ .red
//
```