# Week 7 Assignment: Hands-On Lab - Shopping List Manager

## Files
- `list_warmup.py` - practises index access, `.append()`, `.remove()` and `len()` on a fruits list.
- `shopping_list.py` - an interactive menu (add / remove / show / done) that manages a shopping list.
- `list_report.py` - loops through a list to print it numbered, count long names and find the longest.
- `screenshots/` - screenshots of each program running.

## Why check `in` before calling `.remove()`?
If you call `.remove()` on an item that is not in the list, Python raises a `ValueError` and the program crashes. Checking with `in` first lets the program print a friendly message instead and keep running. It makes the program safer and easier for users to trust.
