# Linux Fundamentals

## Commands Learned

### pwd
Print Working Directory.

Example:
```bash
pwd
```

Shows the current location of the user in the Linux file system.

---

### ls
Lists files and directories.

Example:
```bash
ls
```

---

### ls -la
Lists all files including hidden files with detailed information.

Example:
```bash
ls -la
```

---

### cd
Change Directory.

Example:
```bash
cd Downloads
```

Move into the Downloads folder.

```bash
cd ..
```

Move back one directory.

---

### mkdir
Make Directory.

Example:
```bash
mkdir music_project
```

Creates a new folder called music_project.

---

### touch
Creates a new empty file.

Example:
```bash
touch notes.txt
```

Creates an empty file named notes.txt.

---

### cp
Copies files.

Example:
```bash
cp notes.txt backup.txt
```

Creates a copy of notes.txt named backup.txt.

---

### mv
Moves or renames files.

Example:
```bash
mv notes.txt report.txt
```

Renames notes.txt to report.txt.

---

### cat
Displays file contents.

Example:
```bash
cat notes.txt
```

### history
Displays previously executed commands.

Example:

```bash
history
```

Shows a numbered list of commands that have been used in the terminal.

Example Output:

```text
1  pwd
2  ls
3  cd Downloads
4  mkdir music_project
5  touch notes.txt
```

---

### !!
Runs the last command again.

Example:

```bash
!!
```

If your previous command was:

```bash
ls
```
Then:

```bash
!!
```

will run:

```bash
ls
```

again.

---

### !number
Runs a command from the history list using its number.

Example:

```bash
!5
```

Runs command number 5 from the history output.

---

### history -c
Clears the current user's command history.

Example:

```bash
history -c
```

Removes commands from the current shell history.

Note:
In cybersecurity and system administration, command history may be reviewed during investigations to understand what actions were performed on a system.
