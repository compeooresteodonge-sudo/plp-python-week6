# Week 6 Assignment - Safe Functions

## Files

- `safe_tools.py` - Contains three safe functions using try and except.
- `README.md` - Describes the assignment and explains why an if check cannot catch invalid number conversion.

## Why can the if check not catch "abc" on its own?

An if check can test conditions, but converting "abc" with int() causes a ValueError. The try and except block is needed to catch this error and keep the program from crashing.