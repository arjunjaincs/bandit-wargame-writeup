# 🧭 Bandit Level 11 → 12

## 🎯 Level Goal
> The password for the next level is stored in the file **data.txt**, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

---
## 📂 Key Commands Used

```
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```

---
## 🧠 Takeaways

- `tr 'A-Za-z' 'N-ZA-Mn-za-m'` correctly maps each letter to its ROT13 equivalent by rotating the alphabet 13 positions.
- `'N-ZA-M'` splits the alphabet into two halves and wraps around (N–Z then A–M), ensuring 1:1 mapping.    
- `tr` replaces characters by position, so the order of characters in both sets must match exactly for correct output.

---
## 🔐 Password for Level 12
``
```
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
```

---