# 02 — Course Overview & The Shell 🎓💻

## 1. Why this course matters ⭐
Most CS programs teach algorithms, OS, ML, etc.  
But they rarely teach how to actually use your tools efficiently.

This leads to:
- 🔁 repetitive manual work  
- ❓ guesswork & blind copy-paste  
- 🧊 using only a tiny fraction of system capabilities  

This course fills that gap by teaching:
- ⚡ automation  
- 🚀 navigation  
- 🐞 debugging  
- 🛠️ tool mastery  

---

## 2. How the course is structured 📘
- 🕒 11 short, dense lectures  
- 🎯 Each topic covers one essential tool  
- 📝 Lecture notes + live demos  
- 🧩 Exercises after every lecture  
- 💬 Office hours + email help  
- 📚 Additional resources for deeper study  

---

# Topic 1 — The Shell 🐚

## What the shell is 🔍
A text interface that lets you:
- ▶️ run programs  
- 📥 pass input & output  
- 🔗 chain tools together  
- 🤖 automate tasks more powerfully than GUIs  

We use **bash**, one of the most common shells.

---

## Opening the shell 🚀
A typical prompt:
```
missing:~$ 
```

Meaning:
- 💻 `missing` → machine name  
- 🏠 `~` → home directory  
- 💲 `$` → normal user (not root)  

Example:
```
missing:~$ date
Fri 10 Jan 2020 11:49:31 AM EST
missing:~$ 
```

---

# Core Shell Commands 🧰  
Usage + output + explanation.

---

## 1. `date` 🕒
**Usage**
```
missing:~$ date
```
**Output**
```
Fri 10 Jan 2020 11:49:31 AM EST
```
**Explanation**  
Shows current date & time.

---

## 2. `echo` 🗣️
**Usage**
```
missing:~$ echo hello
```
**Output**
```
hello
```
**Explanation**  
Prints text or variables.

---

## 3. Quoting & Escaping 📝
**Usage**
```
missing:~$ echo "My Photos"
missing:~$ echo My\ Photos
```
**Output**
```
My Photos
My Photos
```

---

## 4. `$PATH` 🛣️
**Usage**
```
missing:~$ echo $PATH
```
**Explanation**  
Directories the shell searches for commands.

---

## 5. `which` 🔎
**Usage**
```
missing:~$ which echo
```

---

## 6. `pwd` 📍
Shows your current directory.

---

## 7. `cd` 🚶
Navigate between directories.

---

## 8. `ls` 📂
List files in a directory.

---

## 9. `mv` ↔️
Move or rename files.

---

## 10. `cp` 📄➡️📄
Copy files.

---

## 11. `mkdir` 📁
Create a new folder.

---

## 12. `man` 📘
Show manual pages.

---

## 13. Redirection (`>`, `<`, `>>`) 🔀
Redirect input/output.

---

## 14. Pipes (`|`) 🔗
Connect the output of one command to another.

---

## 15. `curl` 🌐
Fetch data from URLs.

---

## 16. `grep` 🔍
Search text patterns.

---

## 17. `cut` ✂️
Extract specific text fields.

---

## 18. `sudo` 🛡️
Run commands as root.

---

## 19. `tee` 📤📄
Write to files using elevated permissions.

---

## 20. `/sys` controls ⚙️
Modify kernel-exposed settings like brightness or LEDs.

---

# End of File 🎯
