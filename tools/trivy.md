# Trivy Commands Cheatsheet

> Trivy is an all-in-one security scanner by Aqua Security.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `trivy image` | Scan a container image for vulnerabilities |
| `trivy image --format` | Scan image with custom output format |
| `trivy image --scanners` | Scan image with specific scanner types |
| `trivy fs` | Scan a filesystem for vulnerabilities |
| `trivy rootfs` | Scan a root filesystem directory |
| `trivy config` | Scan IaC files for misconfigurations |
| `trivy config --tf-vars` | Scan Terraform with variable file |
| `trivy k8s` | Scan Kubernetes cluster resources |
| `trivy k8s --compliance` | Scan cluster for compliance violations |
| `trivy k8s --all-namespaces` | Scan all Kubernetes namespaces |
| `trivy repo` | Scan a remote Git repository |
| `trivy sbom` | Generate software bill of materials |
| `trivy image --format cyclonedx` | Generate SBOM in CycloneDX format |
| `trivy server` | Run Trivy in server mode |
| `trivy image --server` | Scan using remote Trivy server |
| `trivy --cache-dir` | Set custom cache directory path |
| `trivy --download-db-only` | Download vulnerability database only |
| `trivy --skip-db-update` | Skip vulnerability database update |
| `trivy clean` | Clean cached data and databases |
| `trivy version` | Display installed Trivy version |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Trivy interactively** | [Open Terminal](https://technoscripts.com/cli/trivy/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/trivy-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Trivy Commands](https://technoscripts.com/command-playground/typing-practice/trivy/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
