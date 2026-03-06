# Flux CD Commands Cheatsheet

> Flux CD is a GitOps operator for Kubernetes.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `flux check` | Check prerequisites and cluster compatibility |
| `flux install` | Install Flux components on a cluster |
| `flux bootstrap github` | Bootstrap Flux with a GitHub repository |
| `flux bootstrap gitlab` | Bootstrap Flux with a GitLab repository |
| `flux uninstall` | Uninstall Flux components from a cluster |
| `flux create source git` | Create a Git source repository |
| `flux create source helm` | Create a Helm chart repository source |
| `flux get sources git` | List Git source repositories |
| `flux get sources helm` | List Helm source repositories |
| `flux get sources all` | List all source repositories |
| `flux create kustomization` | Create a Kustomization resource |
| `flux get kustomizations` | List Kustomization resources |
| `flux create helmrelease` | Create a Helm release |
| `flux get helmreleases` | List Helm releases |
| `flux reconcile` | Trigger reconciliation of a resource |
| `flux get all` | List all Flux resources |
| `flux logs` | Display Flux controller logs |
| `flux suspend` | Suspend reconciliation of a resource |
| `flux resume` | Resume reconciliation of a resource |
| `flux create image repository` | Create an image repository scan |
| `flux create image policy` | Create an image update policy |
| `flux create image update` | Create an image update automation |
| `flux get images all` | List all image automation resources |
| `flux create secret git` | Create a Git authentication secret |
| `flux create secret helm` | Create a Helm authentication secret |
| `flux trace` | Trace a Kubernetes object through Flux |
| `flux export` | Export Flux resources as YAML |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Flux CD interactively** | [Open Terminal](https://technoscripts.com/cli/flux-cd/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/flux-cd-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Flux CD Commands](https://technoscripts.com/command-playground/typing-practice/flux-cd/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
