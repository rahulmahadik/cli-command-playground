# Ansible Commands Cheatsheet

> Ansible is an open-source IT automation platform. Automate server configuration and app deployment.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `ansible` | Run ad-hoc commands on hosts |
| `ansible all -m ping` | Ping all hosts to check connectivity |
| `ansible -m shell` | Run shell commands on remote hosts |
| `ansible -m command` | Run commands on remote hosts |
| `ansible -m copy` | Copy files to remote hosts |
| `ansible -m file` | Manage files and directories on hosts |
| `ansible -m apt` | Manage APT packages on Debian hosts |
| `ansible-playbook` | Run an Ansible playbook |
| `ansible-playbook --check` | Dry run a playbook without changes |
| `ansible-playbook --diff` | Show file changes during playbook run |
| `ansible-playbook --limit` | Limit playbook to specific hosts |
| `ansible-playbook --tags` | Run only tasks with specific tags |
| `ansible-playbook --skip-tags` | Skip tasks with specific tags |
| `ansible-playbook -e` | Pass extra variables to a playbook |
| `ansible-inventory` | Show inventory information |
| `ansible-inventory --list` | List all hosts in JSON format |
| `ansible-inventory --graph` | Display inventory as a tree graph |
| `ansible-inventory --host` | Show variables for a specific host |
| `ansible-vault create` | Create a new encrypted file |
| `ansible-vault encrypt` | Encrypt an existing file |
| `ansible-vault decrypt` | Decrypt an encrypted file |
| `ansible-vault view` | View an encrypted file without editing |
| `ansible-vault edit` | Edit an encrypted file in place |
| `ansible-vault rekey` | Change the encryption password |
| `ansible-vault encrypt_string` | Encrypt a string value |
| `ansible-galaxy install` | Install a role from Galaxy |
| `ansible-galaxy init` | Initialize a new role directory structure |
| `ansible-galaxy collection install` | Install an Ansible collection |
| `ansible-galaxy list` | List installed roles |
| `ansible-galaxy remove` | Remove an installed role |
| `ansible-doc` | Show documentation for a module |
| `ansible-doc -l` | List all available modules |
| `ansible --version` | Display the Ansible version |
| `ansible-config` | View or dump Ansible configuration |
| `ansible-lint` | Lint playbooks for best practices |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Ansible interactively** | [Open Terminal](https://technoscripts.com/cli/ansible/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/ansible-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Ansible Commands](https://technoscripts.com/command-playground/typing-practice/ansible/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
