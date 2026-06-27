# Question 1 - Linux Environment Verification

## Objective

Verify the Linux environment by checking user information, shell, current directory, workspace contents, and network connectivity.

### Command 1

```bash
id
```

**Explanation:**
The `id` command displays the current user's UID, GID, and group memberships. It confirmed that my user account belongs to groups such as `sudo`, `adm`, and `users`.

---

### Command 2

```bash
echo $SHELL
```

**Explanation:**
This command displays the default shell currently being used. The output showed that the system is using `/bin/bash`.

---

### Command 3

```bash
pwd
```

**Explanation:**
The `pwd` command prints the current working directory. It showed that I was working inside the WSL-mounted Windows directory.

---

### Command 4

```bash
ls -la
```

**Explanation:**
This command lists all files and directories, including hidden files, along with permissions and ownership information. It confirmed the contents of my current workspace.

---

### Command 5

```bash
ping -c 4 google.com
```

**Explanation:**
The `ping` command verifies internet connectivity by sending four packets to Google's server. All packets were received successfully with 0% packet loss, confirming a stable network connection.

## Files Included

* Environment_Report.txt
* Q1.png
