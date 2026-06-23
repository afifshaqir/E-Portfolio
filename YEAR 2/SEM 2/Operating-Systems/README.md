# 🖥️ Operating Systems

**SECR2043 — Operating Systems | Semester II 2024/2025**  
Faculty of Computing, Universiti Teknologi Malaysia

---

## 👤 Student

| | |
|---|---|
| **Name** | Afif Shaqir Irfan bin Arqam |
| **Matric No.** | A23CS0204 |
| **Section** | 03 |
| **Year / Semester** | Year 2 · Semester 2 |

---

## 📌 Lab Assessments

### ✅ Lab Assessment 1 — Basic Linux Commands & Text File Manipulation

**Activity 1: Basic Linux Commands**

| Command | Purpose |
|---------|---------|
| `pwd` | Display current working directory |
| `ls -a /` | List all files including hidden ones |
| `mkdir os_lab` | Create a new directory |
| `cd os_lab` | Change working directory |
| `touch hello.txt` | Create a new file |
| `echo "Hello, world!" > hello.txt` | Write text to a file |
| `cat hello.txt` | Display file contents |
| `cp hello.txt hello_copy.txt` | Copy a file |
| `mv hello_copy.txt hello_bak.txt` | Rename a file |
| `rm hello.txt` | Delete a file |
| `ls -R ~` | List home directory recursively |

**Activity 2: Text File Manipulation**

Practised creating, writing, appending, and concatenating text files using `echo`, `cat`, and `touch`:
- Writing and appending content with `echo` redirection (`>` and `>>`)
- Concatenating multiple files into a single output using `cat`
- Redirecting concatenated output to a new file (`greeting.txt`)

---

### ✅ Lab Assessment 3 — File Management & Bash Scripting

**Question 1a — Shell Script & Directory Tree**

Wrote a bash script (`afifshaqir.sh`) that created a directory and file structure from scratch using Linux commands:

```bash
echo "Hello world" > helloworld.jar
mkdir cars; mkdir dates; mkdir fruits drinks
cd cars; echo "Honda Accord" > accord.c
cp accord.c civic.c; echo proton > proton.c
cd ../dates; date > dateoftheday; cat dateoftheday > appointment
cd ../fruits; echo apple > apple.txt; cat apple.txt > orange.txt
cd drinks; cp ../cars/*.* .; cp ../fruits/*.* .; cp ../*.jar .
```

Drew the resulting directory tree rooted at `$HOME`.

**Question 1b — Interactive Bash Script**

Wrote an interactive script that:
- Prompts the user to enter a file extension
- Displays all files matching that extension
- Counts and prints the total number of matching files

**Question 2a — Reproducing a Directory Tree**

Written a bash script (`myname2a.sh`) to reproduce a given directory/file structure:

```
$HOME/
└── subject/
│   ├── FCS/
│   │   └── books/
│   │       ├── operating_systems
│   │       ├── software_engineering
│   │       └── data_communication
│   └── FBE/
│       ├── Linux_operating_systems
│       └── Best_of_software_engineering
└── faculti/
    ├── dean
    ├── deputy_dean
    └── Project_Manager
```

**Question 2b — File Access Control**

Identified and recorded Linux permission strings (`drwxrwxr-x`, `drwxr-xr-x`) for each directory and file produced by the script.

---

## 🛠️ Skills Covered

`Linux CLI` · `Bash Scripting` · `File & Directory Management` · `File Permissions` · `Text Manipulation` · `Shell Redirection` · `Process & File I/O`

---

## 💭 Reflection

Operating Systems was the course that made me comfortable in the Linux terminal. Before this, I had only used command-line tools occasionally and mostly followed instructions without fully understanding what was happening. Working through Lab 1 — creating files, writing content, copying, renaming, and deleting — gave me a solid foundation in how a Unix filesystem actually works at the command level.

Lab 3 pushed that further into scripting. Writing bash scripts to build directory trees from scratch was more challenging than it looked: the order of commands matters, paths need to be correct, and a single typo breaks everything. Getting the interactive extension-filter script working was satisfying — it felt like building a real mini-tool rather than just completing an exercise.

Understanding file permissions (`drwxrwxr-x`) also changed how I think about security at the OS level. These concepts — filesystem structure, permissions, scripting — quietly underpin everything else in data engineering: servers, pipelines, cloud VMs, and containers all run on Linux. This course built the foundation I use every time I work in a terminal.

---

## 📂 Folder Contents

```
📁 Operating-Systems/
├── 📄 README.md
├── 📄 Lab_Assessment_1_AfifShaqir.pdf
├── 📄 Lab_Assessment_3_AfifShaqir.pdf
└── 📁 scripts/
    ├── afifshaqir.sh
    └── myname2a.sh
```

---

<div align="center">

**Afif Shaqir Irfan bin Arqam** · A23CS0204  
[🌐 E-Portfolio](https://afifshaqir.github.io/afifshaqir.github.ios/) · [🐙 GitHub](https://github.com/afifshaqir)

</div>

