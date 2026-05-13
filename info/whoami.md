# 👤 `whoami` – Identify Current User

The `whoami` command is used in Linux to **print the current effective username** of the user executing the command. It's simple, fast, and commonly used in **scripts**, **access checks**, and **debugging** sessions.

---

## 📌 Overview

`whoami` is short for "**Who am I?**" and returns the **username associated with the current user ID**. It is often used in scripts to ensure the correct user is executing the script or to print the user context.

It is functionally equivalent to:

```bash
id -un
