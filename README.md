# take-system

A Bash-based assignment submission, testing, and marking system  
developed as part of a COMP1521 project at UNSW.

## 📂 Scripts Included

- `take-add` – Add new students to the system  
- `take-submit` – Accept assignment submissions  
- `take-fetch` – Retrieve submitted files  
- `take-summary` – Show a summary of submissions  
- `take-status` – Check individual submission status  
- `take-test` – Run automated test scripts  
- `take-mark` – Mark submissions using test output  
- `take-rm` – Remove students and clean up their data

## ⚙️ Technologies

- Bash scripting  
- POSIX shell tools  
- File I/O and directory management  
- Modular CLI tool design

## 🚀 How to Use

Each script runs independently from the terminal:

```bash
./take-add -d .take student1 student2
./take-submit -d .take student1 solution.sh
./take-test -d .take -r .reference
