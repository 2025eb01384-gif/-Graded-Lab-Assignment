# Question 4 - File Access and I/O Investigation

## Commands Executed

### Command 1

```bash
mkdir ~/Question4
cd ~/Question4
```

**Explanation:** Created a working directory for the experiment.

---

### Command 2

```bash
echo "Linux I/O Investigation" > log.txt
cat log.txt
```

**Explanation:** Created a sample file and displayed its contents.

---

### Command 3

```bash
lsof | head
```

**Explanation:** Displayed a list of open files currently in use by running processes.

---

### Command 4

```bash
ls -l /proc/self/fd
```

**Explanation:** Displayed the standard file descriptors and their associated devices or files.

---

### Command 5

```bash
echo "This is standard output" > output.txt
```

**Explanation:** Redirected standard output into a file.

---

### Command 6

```bash
ls non_existing_file 2> error.txt
cat error.txt
```

**Explanation:** Redirected standard error into a separate file.

---

### Command 7

```bash
ulimit -a
```

**Explanation:** Displayed the resource limits configured for the current shell.

