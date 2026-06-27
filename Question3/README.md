# Question 3 - File System and Link Analysis

## Commands Executed

### Command 1

```bash
mkdir ~/Question3
cd ~/Question3
```

**Explanation:** Created a working directory for the experiment.

---

### Command 2

```bash
echo "Linux File System Experiment" > original.txt
```

**Explanation:** Created the original file.

---

### Command 3

```bash
ln original.txt hardlink.txt
```

**Explanation:** Created a hard link that shares the same inode as the original file.

---

### Command 4

```bash
ln -s original.txt symlink.txt
```

**Explanation:** Created a symbolic link pointing to the original file.

---

### Command 5

```bash
ls -li
```

**Explanation:** Displayed inode numbers and verified the relationship between the files.

---

### Command 6

```bash
stat original.txt hardlink.txt symlink.txt
```

**Explanation:** Displayed detailed metadata for each file.

---

### Command 7

```bash
rm original.txt
ls -li
cat hardlink.txt
cat symlink.txt
```

**Explanation:** Demonstrated that the hard link remained accessible after deleting the original file, while the symbolic link became broken.
