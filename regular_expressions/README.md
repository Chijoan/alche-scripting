````markdown
# Regex Basics

**Regex** (regular expressions) lets you **search and match patterns** in text.

---

## Symbols
- `.` → any character  
- `*` → 0 or more  
- `+` → 1 or more  
- `?` → 0 or 1  
- `[]` → any character inside  

---

## Example

```python
import re
text = "The fox runs fast"
match = re.search(r"fox", text)
print(match.group())  # Output: fox
````

You can match multiple words too:

```python
text = "A cat and a dog"
match = re.search(r"cat|dog", text)
print(match.group())  # Output: cat
```
