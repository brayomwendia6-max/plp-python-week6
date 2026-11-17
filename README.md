# PLP Python Week 6 - Safe Tools

## Files
- safe_tools.py - Contains safe_divide, safe_number, and get_field functions that use try/except to handle errors without crashing.
- README.md - Explains the project and answers why try/except is needed.

## Why can the if check not catch abc on its own?

An `if` check cannot catch `"abc"` on its own because `int("abc")` crashes with a ValueError *before* the `if` can even run. You need `try/except` to catch the crash when the conversion itself fails.
