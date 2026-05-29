# Linux Basic Navigation Commands

## Goal

This note documents basic Linux navigation commands used in the terminal. These commands are essential for Cloud, DevOps, and AI studies.

---

## 1. `pwd`

Shows the current directory.

```bash
pwd
```

Example:

```bash
/home/marceloadvincula/projects/cloud-foundations-labs
```

Meaning:

The terminal is currently inside the `cloud-foundations-labs` project folder.

---

## 2. `ls`

Lists files and folders in the current directory.

```bash
ls
```

Example:

```bash
README.md  01-linux-basics  02-git-github
```

Useful options:

```bash
ls -l
```

Shows details such as permissions, owner, size, and date.

```bash
ls -a
```

Shows hidden files.

```bash
ls -la
```

Shows detailed information, including hidden files.

---

## 3. `cd`

Changes directory.

Enter a folder:

```bash
cd 01-linux-basics
```

Go back one level:

```bash
cd ..
```

Go to the home directory:

```bash
cd ~
```

or:

```bash
cd
```

Go directly to the project folder:

```bash
cd ~/projects/cloud-foundations-labs
```

---

## 4. `mkdir`

Creates a new directory.

```bash
mkdir new-folder
```

Create nested folders:

```bash
mkdir -p folder1/folder2/folder3
```

The `-p` option prevents errors if some folders already exist.

---

## 5. `touch`

Creates an empty file.

```bash
touch notes.md
```

Example:

```bash
touch 01-linux-basics/commands/basic-navigation.md
```

---

## 6. `cat`

Displays the content of a file.

```bash
cat README.md
```

Useful for quickly checking small files.

---

## 7. `nano`

Opens a text editor in the terminal.

```bash
nano README.md
```

Useful shortcuts:

```text
Ctrl + O  Save
Enter     Confirm
Ctrl + X  Exit
Ctrl + K  Cut line
Ctrl + W  Search
```

---

## 8. `cp`

Copies files or folders.

Copy a file:

```bash
cp file1.txt file2.txt
```

Copy a folder:

```bash
cp -r folder1 folder2
```

The `-r` option means recursive, used for folders.

---

## 9. `mv`

Moves or renames files and folders.

Rename a file:

```bash
mv old-name.txt new-name.txt
```

Move a file to another folder:

```bash
mv file.txt folder/
```

---

## 10. `rm`

Removes files or folders.

Remove a file:

```bash
rm file.txt
```

Remove a folder and its contents:

```bash
rm -r folder/
```

Warning:

Use `rm` carefully because deleted files are not moved to the Windows recycle bin.

---

## 11. `tree`

Shows folders and files as a tree.

```bash
tree
```

Limit depth:

```bash
tree -L 2
```

Show hidden files:

```bash
tree -a
```

---

## 12. `clear`

Clears the terminal screen.

```bash
clear
```

Shortcut:

```text
Ctrl + L
```

---

## Practice

Run these commands inside the project folder:

```bash
pwd
ls
ls -la
tree -L 2
cd 01-linux-basics
pwd
cd ..
pwd
```

---

## Notes

These commands are the foundation for working with Linux servers, cloud labs, Docker, Terraform, Kubernetes, and automation scripts.
