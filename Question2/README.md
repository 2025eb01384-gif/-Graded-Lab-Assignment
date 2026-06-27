# Question 2 - Secure Project Workspace Setup

## Commands Executed

### Command 1

```bash
mkdir -p ~/ProjectWorkspace/{Documents,SourceCode,Reports}
```

**Explanation:** Created a project workspace with three subdirectories in a single command.

---

### Command 2

```bash
tree ~/ProjectWorkspace
```

**Explanation:** Displayed the complete directory hierarchy for verification.

---

### Command 3

```bash
ls -ld ~/ProjectWorkspace
```

**Explanation:** Displayed the directory permissions before and after modification.

---

### Command 4

```bash
chmod 700 ~/ProjectWorkspace
```

**Explanation:** Restricted directory access to the owner only, improving security.

---

### Command 5

```bash
stat ~/ProjectWorkspace
```

**Explanation:** Displayed ownership information and detailed metadata for the workspace.

---

### Command 6

```bash
umask
```
**Explanation:** Displayed the system's default permission mask used when creating new files and directories.

