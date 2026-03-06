# Checkov Commands Cheatsheet

> Checkov is a static analysis tool for infrastructure-as-code.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `checkov -f` | Scan a single file |
| `checkov -d` | Scan a directory |
| `checkov --list` | List all available checks |
| `checkov --version` | Display the Checkov version |
| `checkov --framework terraform` | Scan Terraform files only |
| `checkov --framework kubernetes` | Scan Kubernetes manifests only |
| `checkov --framework dockerfile` | Scan Dockerfiles only |
| `checkov --framework cloudformation` | Scan CloudFormation templates only |
| `checkov -o json` | Output results in JSON format |
| `checkov -o sarif` | Output results in SARIF format |
| `checkov -o junitxml` | Output results in JUnit XML format |
| `checkov --compact` | Show compact output |
| `checkov --check` | Run specific checks by ID |
| `checkov --skip-check` | Skip specific checks by ID |
| `checkov --config-file` | Use a configuration file |
| `checkov --baseline` | Compare against a baseline file |
| `checkov --soft-fail` | Exit with code 0 even on failures |
| `checkov --quiet` | Suppress passed check output |
| `checkov --external-checks-dir` | Load custom checks from a directory |
| `checkov --download-external-modules` | Download external Terraform modules |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Checkov interactively** | [Open Terminal](https://technoscripts.com/cli/checkov/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/checkov-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Checkov Commands](https://technoscripts.com/command-playground/typing-practice/checkov/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
