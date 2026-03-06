# PowerShell Commands Cheatsheet

> PowerShell is a cross-platform shell and scripting language. Automate Windows and cross-platform workflows.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `Get-Help` | Display help for a command |
| `Get-Command` | List all available commands |
| `Get-Member` | Show properties and methods of objects |
| `Get-Alias` | List command aliases |
| `Get-Verb` | List approved PowerShell verbs |
| `Update-Help` | Download and install help files |
| `Show-Command` | Display command in a GUI window |
| `Get-ChildItem` | List files and directories |
| `Set-Location` | Change the current directory |
| `Get-Location` | Get the current directory path |
| `New-Item` | Create a new file or directory |
| `Remove-Item` | Delete files or directories |
| `Copy-Item` | Copy files or directories |
| `Move-Item` | Move files or directories |
| `Rename-Item` | Rename a file or directory |
| `Test-Path` | Check if a path exists |
| `Get-Item` | Get an item at a specified path |
| `Get-ItemProperty` | Get properties of an item |
| `Set-ItemProperty` | Set properties of an item |
| `Clear-Item` | Clear the contents of an item |
| `Resolve-Path` | Resolve wildcard characters in a path |
| `Push-Location` | Push location onto the stack |
| `Pop-Location` | Pop location from the stack |
| `Get-Content` | Read the contents of a file |
| `Set-Content` | Write content to a file |
| `Add-Content` | Append content to a file |
| `Out-File` | Send output to a file |
| `Select-String` | Search for text patterns in strings |
| `Write-Host` | Write output to the console |
| `Write-Output` | Send output to the pipeline |
| `Write-Error` | Write an error message |
| `Write-Warning` | Write a warning message |
| `Write-Verbose` | Write a verbose message |
| `Clear-Content` | Clear the content of a file |
| `Out-String` | Convert objects to strings |
| `Out-GridView` | Display data in a grid view window |
| `Format-Table` | Format output as a table |
| `Format-List` | Format output as a list |
| `ConvertTo-Json` | Convert objects to JSON format |
| `ConvertFrom-Json` | Convert JSON to PowerShell objects |
| `ConvertTo-Csv` | Convert objects to CSV format |
| `ConvertFrom-Csv` | Convert CSV to PowerShell objects |
| `Export-Csv` | Export objects to a CSV file |
| `Import-Csv` | Import data from a CSV file |
| `Get-Process` | List running processes |
| `Stop-Process` | Stop a running process |
| `Start-Process` | Start a new process |
| `Wait-Process` | Wait for a process to stop |
| `Debug-Process` | Debug a running process |
| `Get-Job` | List background jobs |
| `Start-Job` | Start a background job |
| `Stop-Job` | Stop a background job |
| `Receive-Job` | Get background job results |
| `Remove-Job` | Delete a background job |
| `Get-Service` | List Windows services |
| `Start-Service` | Start a Windows service |
| `Stop-Service` | Stop a Windows service |
| `Restart-Service` | Restart a Windows service |
| `Set-Service` | Change service properties |
| `New-Service` | Create a new Windows service |
| `Remove-Service` | Remove a Windows service |
| `Suspend-Service` | Suspend a Windows service |
| `Resume-Service` | Resume a suspended service |
| `Get-ComputerInfo` | Get comprehensive system information |
| `Get-CimInstance` | Query CIM/WMI classes |
| `Get-WmiObject` | Query WMI classes (legacy) |
| `Get-Host` | Get PowerShell host information |
| `Get-Date` | Get the current date and time |
| `Get-TimeZone` | Get the current time zone |
| `Get-Culture` | Get the current culture settings |
| `Get-EventLog` | Get event log entries (legacy) |
| `Get-WinEvent` | Get Windows event log entries |
| `Get-HotFix` | List installed hotfixes |
| `Get-PSDrive` | List PowerShell drives |
| `Get-Volume` | List disk volumes |
| `Get-Disk` | List physical disks |
| `Test-Connection` | Send ICMP echo requests (ping) |
| `Test-NetConnection` | Test network connectivity and ports |
| `Get-NetIPAddress` | Get IP address configuration |
| `Get-NetIPConfiguration` | Get network interface configuration |
| `Get-NetAdapter` | List network adapters |
| `Resolve-DnsName` | Perform DNS name resolution |
| `Get-NetTCPConnection` | List TCP connections |
| `Get-NetRoute` | Get the IP routing table |
| `Invoke-WebRequest` | Send an HTTP/HTTPS request |
| `Invoke-RestMethod` | Send a REST API request |
| `Get-DnsClientCache` | View DNS client cache entries |
| `Clear-DnsClientCache` | Clear the DNS client cache |
| `Get-LocalUser` | List local user accounts |
| `New-LocalUser` | Create a new local user |
| `Remove-LocalUser` | Delete a local user |
| `Set-LocalUser` | Modify a local user account |
| `Get-LocalGroup` | List local groups |
| `Add-LocalGroupMember` | Add a member to a local group |
| `Get-LocalGroupMember` | List members of a local group |
| `Get-Acl` | Get access control list for a resource |
| `Set-Acl` | Set access control list for a resource |
| `Get-Credential` | Prompt for username and password |
| `Get-ExecutionPolicy` | Get the script execution policy |
| `Set-ExecutionPolicy` | Set the script execution policy |
| `ConvertTo-SecureString` | Convert text to a secure string |
| `ConvertFrom-SecureString` | Convert secure string to text |
| `Get-ItemProperty (Registry)` | Read registry values |
| `Set-ItemProperty (Registry)` | Set registry values |
| `New-ItemProperty` | Create a new registry value |
| `Remove-ItemProperty` | Delete a registry value |
| `Get-ChildItem (Registry)` | List registry subkeys |
| `New-Item (Registry)` | Create a new registry key |
| `Remove-Item (Registry)` | Delete a registry key |
| `Enter-PSSession` | Start an interactive remote session |
| `Exit-PSSession` | End an interactive remote session |
| `New-PSSession` | Create a persistent remote session |
| `Remove-PSSession` | Close a remote session |
| `Get-PSSession` | List active remote sessions |
| `Invoke-Command` | Run commands on remote computers |
| `Enable-PSRemoting` | Enable PowerShell remoting |
| `Disable-PSRemoting` | Disable PowerShell remoting |
| `Test-WSMan` | Test WS-Management connectivity |
| `Get-Module` | List imported modules |
| `Import-Module` | Import a PowerShell module |
| `Remove-Module` | Remove a loaded module |
| `Install-Module` | Install a module from a repository |
| `Uninstall-Module` | Uninstall a PowerShell module |
| `Update-Module` | Update an installed module |
| `Find-Module` | Search for modules in a repository |
| `Get-InstalledModule` | List installed modules |
| `Install-Script` | Install a script from a repository |
| `Get-PSRepository` | List registered repositories |
| `Register-PSRepository` | Register a new repository |
| `Get-Variable` | Get PowerShell variable values |
| `Set-Variable` | Set a PowerShell variable |
| `New-Variable` | Create a new variable |
| `Remove-Variable` | Delete a variable |
| `Clear-Variable` | Clear a variable value |
| `$env: Variables` | Access environment variables |
| `$PSVersionTable` | Display PowerShell version info |
| `$null` | Represent a null value |
| `$true / $false` | Boolean true and false values |
| `@() Array` | Create an array |
| `@{} Hashtable` | Create a hashtable |
| `If/Else/ElseIf` | Conditional logic branching |
| `Switch` | Multi-branch conditional statement |
| `ForEach-Object` | Process each item in a pipeline |
| `For Loop` | Execute a block a set number of times |
| `While Loop` | Loop while a condition is true |
| `Do-While / Do-Until` | Loop with post-condition check |
| `Try/Catch/Finally` | Handle errors and exceptions |
| `Break/Continue` | Control loop flow |
| `Return` | Return a value from a function |
| `Function` | Define a reusable function |
| `Param` | Define function parameters |
| `Select-Object` | Select specific object properties |
| `Where-Object` | Filter objects by condition |
| `Sort-Object` | Sort objects by property values |
| `Group-Object` | Group objects by property values |
| `Measure-Object` | Calculate statistics on objects |
| `Compare-Object` | Compare two sets of objects |
| `Tee-Object` | Send output to file and pipeline |
| `New-Object` | Create a new .NET object |
| `Add-Member` | Add properties to an object |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice PowerShell interactively** | [Open Terminal](https://technoscripts.com/cli/powershell/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/powershell-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type PowerShell Commands](https://technoscripts.com/command-playground/typing-practice/powershell/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
