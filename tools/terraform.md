# Terraform Commands Cheatsheet

> Terraform is an infrastructure-as-code tool by HashiCorp. Provision and manage cloud resources safely.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `terraform init` | Initialize a Terraform working directory |
| `terraform init -upgrade` | Upgrade providers to latest versions |
| `terraform init -reconfigure` | Reconfigure backend without migration |
| `terraform get` | Download and install modules |
| `terraform providers` | Show required provider plugins |
| `terraform plan` | Preview infrastructure changes |
| `terraform plan -out` | Save a plan to a file |
| `terraform plan -target` | Plan changes for a specific resource |
| `terraform plan -var` | Pass a variable value to the plan |
| `terraform show` | Display the current state or plan |
| `terraform apply` | Apply planned infrastructure changes |
| `terraform apply -auto-approve` | Apply changes without confirmation |
| `terraform destroy` | Destroy all managed infrastructure |
| `terraform destroy -target` | Destroy a specific resource |
| `terraform refresh` | Update state to match real resources |
| `terraform state list` | List all resources in the state |
| `terraform state show` | Show details of a state resource |
| `terraform state mv` | Move a resource in the state |
| `terraform state rm` | Remove a resource from the state |
| `terraform state pull` | Pull remote state to stdout |
| `terraform state push` | Push local state to remote backend |
| `terraform workspace list` | List all workspaces |
| `terraform workspace new` | Create a new workspace |
| `terraform workspace select` | Switch to a different workspace |
| `terraform workspace show` | Show the current workspace name |
| `terraform workspace delete` | Delete a workspace |
| `terraform validate` | Validate configuration syntax |
| `terraform fmt` | Format configuration files |
| `terraform fmt -check` | Check if files are formatted |
| `terraform fmt -recursive` | Format files recursively |
| `terraform output` | Show output values from the state |
| `terraform output -json` | Show output values as JSON |
| `terraform import` | Import existing infrastructure into state |
| `terraform graph` | Generate a visual dependency graph |
| `terraform taint` | Mark a resource for recreation |
| `terraform console` | Open an interactive expression console |
| `terraform force-unlock` | Manually unlock the state |
| `terraform version` | Display the Terraform version |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Terraform interactively** | [Open Terminal](https://technoscripts.com/cli/terraform/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/terraform-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Terraform Commands](https://technoscripts.com/command-playground/typing-practice/terraform/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
