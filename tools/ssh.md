# SSH Commands Cheatsheet

> SSH (Secure Shell) is the standard protocol for secure remote access.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `ssh user@host` | Connect to a remote host |
| `ssh -p` | Connect on a specific port |
| `ssh -i` | Use a specific identity (private key) file |
| `ssh -v` | Connect with verbose output |
| `ssh-keygen` | Generate a new SSH key pair |
| `ssh-copy-id` | Copy public key to a remote host |
| `ssh-agent` | Start the SSH authentication agent |
| `ssh-add` | Add a private key to the agent |
| `scp` | Copy files to/from a remote host |
| `scp -r` | Recursively copy directories |
| `sftp` | Start an interactive SFTP session |
| `rsync over ssh` | Synchronize files over SSH |
| `ssh -L (Local Forward)` | Create a local port forward tunnel |
| `ssh -R (Remote Forward)` | Create a remote port forward tunnel |
| `ssh -D (SOCKS Proxy)` | Create a SOCKS proxy tunnel |
| `ssh -N -f (Background Tunnel)` | Run a tunnel in the background |
| `ssh config file` | Configure SSH client settings |
| `ssh known_hosts` | Manage known host keys |
| `ssh authorized_keys` | Configure authorized public keys |
| `ssh-keyscan` | Gather SSH host public keys |
| `ssh -X (X11 Forwarding)` | Enable X11 display forwarding |
| `ssh -J (Jump Host)` | Connect through a jump/bastion host |
| `ssh remote command` | Execute a command on a remote host |
| `ssh -o (Options)` | Pass configuration options inline |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice SSH interactively** | [Open Terminal](https://technoscripts.com/cli/ssh/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/ssh-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type SSH Commands](https://technoscripts.com/command-playground/typing-practice/ssh/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
