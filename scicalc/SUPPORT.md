# Support — Sci Calc (Scientific Calculator)

## What it does

Sci Calc is a scientific calculator for iPhone with all the functions you'd
expect from a Casio fx-991 or TI-84 — wrapped in a fast, clean dark
interface. No subscriptions, no ads, no data collection.

## Quick Start

1. **Type a number**, tap operators (`+`, `−`, `×`, `÷`, `^`), tap `=`.
   Sci Calc shows a **live preview** of the result as you type.
2. **Scientific functions**: tap `sin`, `cos`, `tan`, `log`, `ln`, `√`, etc.
   Each function automatically opens a `(` — close with `)` then `=`.
3. **DEG / RAD**: tap the `DEG` chip at the top to toggle.
4. **INV** (inverse): tap the `INV` chip to flip `sin → sin⁻¹`, `log → 10^x`,
   `ln → e^x`. Tap again to flip back.
5. **History**: tap the clock icon at the top right. Tap any past result to
   re-load it.

## Function Reference

| Key | Meaning |
|---|---|
| `sin` `cos` `tan` | Trigonometric — degrees or radians per the DEG/RAD toggle |
| `sin⁻¹` `cos⁻¹` `tan⁻¹` | Inverse trig (visible when INV is on) |
| `log` | Base-10 logarithm |
| `ln` | Natural logarithm (base *e*) |
| `10^x` `e^x` | Exponentials (visible when INV is on) |
| `√` | Square root |
| `x²` | Square |
| `x^y` | General power |
| `1/x` | Reciprocal |
| `n!` | Factorial (integers 0 – 170) |
| `π` `e` | Mathematical constants |
| `(` `)` | Standard precedence with parentheses |
| `⌫` | Delete the last character (smart — removes full function names like `sin` as one unit) |
| `AC` | Clear everything |

## Frequently Asked Questions

**Why does the result update as I type?**
Sci Calc evaluates the expression in real time. If the expression is
incomplete, you'll see `…` or the last typed number. Once it's valid, the
live result appears.

**Why is `tan(90°)` not infinity?**
It's actually a very large number (≈1.6 × 10¹⁶) because of floating-point
limits, not true infinity. Mathematically the function is undefined there.

**Where's GRAD (gradians)?**
Not in v1. We chose DEG + RAD because GRAD has very low usage. Tell us if
you need it.

**Does it sync between devices?**
Not currently. History is stored locally per device. We're considering
iCloud sync for v1.1.

**Can it solve equations or do calculus?**
Not yet. Sci Calc focuses on direct expression evaluation. If you'd like
solving / numerical integration, let us know.

**Does it use my data?**
No. Sci Calc never makes a network request and never collects any data.
See [PRIVACY.md](./PRIVACY.md).

**Which devices does it work on?**
iOS 17 or later. iPhone only (iPad version coming).

## Contact

- **Bug reports / feature requests**: [open an issue](https://github.com/fengyiqicoder/appmatemax/issues)
- **Email**: fengyiqicoder@gmail.com
