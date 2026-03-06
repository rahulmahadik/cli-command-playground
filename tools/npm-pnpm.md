# npm / pnpm Commands Cheatsheet

> npm is the default package manager for Node.js. Install, update, and manage JavaScript packages.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `npm install` | Install all project dependencies |
| `npm install <package>` | Install a specific package |
| `npm install --save-dev` | Install as a dev dependency |
| `npm install -g` | Install a package globally |
| `npm install <package>@<version>` | Install a specific version |
| `npm ci` | Clean install from lock file |
| `npm link` | Symlink a package for local development |
| `npm install --production` | Install only production dependencies |
| `npm uninstall` | Remove a package |
| `npm uninstall -g` | Remove a globally installed package |
| `npm uninstall --save-dev` | Remove a dev dependency |
| `npm update` | Update all packages |
| `npm update <package>` | Update a specific package |
| `npm update -g` | Update globally installed packages |
| `npm outdated` | Check for outdated packages |
| `npm list` | List installed packages |
| `npm list --depth` | List packages with depth limit |
| `npm list -g` | List globally installed packages |
| `npm explain` | Explain why a package is installed |
| `npm view` | View registry info for a package |
| `npm search` | Search the npm registry |
| `npm fund` | Show funding information for packages |
| `npm run` | Run a script from package.json |
| `npm start` | Run the start script |
| `npm test` | Run the test script |
| `npm run build` | Run the build script |
| `npm exec` | Execute a package binary |
| `npx` | Execute a package binary directly |
| `npm stop` | Run the stop script |
| `npm restart` | Run the restart script |
| `npm version` | Bump the package version |
| `npm version patch` | Bump the patch version number |
| `npm version minor` | Bump the minor version number |
| `npm version major` | Bump the major version number |
| `npm dist-tag` | Manage distribution tags |
| `npm view versions` | View all available versions |
| `npm publish` | Publish a package to the registry |
| `npm pack` | Create a tarball from a package |
| `npm deprecate` | Deprecate a package version |
| `npm unpublish` | Remove a package from the registry |
| `npm publish --access public` | Publish a scoped package publicly |
| `npm init` | Initialize a new package.json file |
| `npm init -y` | Initialize with default values |
| `npm config list` | List all configuration settings |
| `npm config set` | Set a configuration value |
| `npm config get` | Get a configuration value |
| `npm config delete` | Delete a configuration value |
| `npm set` | Set a configuration key-value pair |
| `npm get` | Get a configuration value |
| `npm audit` | Run a security audit |
| `npm audit fix` | Fix known security vulnerabilities |
| `npm audit fix --force` | Force fix breaking vulnerabilities |
| `npm doctor` | Check npm environment health |
| `npm audit --json` | Output audit report as JSON |
| `npm cache clean` | Clear the npm cache |
| `npm cache verify` | Verify cache integrity |
| `npm prune` | Remove extraneous packages |
| `npm dedupe` | Deduplicate package dependencies |
| `npm rebuild` | Rebuild native addon packages |
| `npm workspaces` | Manage monorepo workspaces |
| `npm install -w` | Install in a specific workspace |
| `npm run -w` | Run a script in a workspace |
| `npm run --workspaces` | Run a script in all workspaces |
| `npm init -w` | Initialize a new workspace |
| `npm login` | Log in to the npm registry |
| `npm logout` | Log out of the npm registry |
| `npm whoami` | Show the logged-in npm username |
| `npm token` | Manage authentication tokens |
| `npm access` | Set access level on packages |
| `npm owner` | Manage package ownership |
| `pnpm install` | Install all project dependencies |
| `pnpm add` | Add a package to dependencies |
| `pnpm add -D` | Add as a dev dependency |
| `pnpm add -g` | Install a package globally |
| `pnpm remove` | Remove a package |
| `pnpm update` | Update installed packages |
| `pnpm run` | Run a script from package.json |
| `pnpm exec` | Execute a package binary |
| `pnpm dlx` | Execute a remote package binary |
| `pnpm list` | List installed packages |
| `pnpm why` | Show why a package is installed |
| `pnpm import` | Import a lockfile from another manager |
| `pnpm init` | Initialize a new package.json |
| `pnpm audit` | Run a security audit |
| `pnpm outdated` | Check for outdated packages |
| `pnpm link` | Symlink a package for development |
| `pnpm unlink` | Remove a symlinked package |
| `pnpm rebuild` | Rebuild native addon packages |
| `pnpm prune` | Remove extraneous packages |
| `pnpm publish` | Publish a package to the registry |
| `pnpm pack` | Create a tarball from a package |
| `pnpm patch` | Patch a dependency package |
| `pnpm patch-commit` | Commit a patched package |
| `pnpm env` | Manage Node.js environments |
| `pnpm create` | Scaffold a new project from a template |
| `pnpm store status` | Check store package integrity |
| `pnpm store prune` | Remove unreferenced store packages |
| `pnpm store add` | Add packages directly to the store |
| `pnpm store path` | Show the store directory path |
| `pnpm fetch` | Fetch packages into the store |
| `pnpm dedupe` | Deduplicate package dependencies |
| `pnpm -r` | Run a command recursively in workspaces |
| `pnpm --filter` | Filter packages in a workspace |
| `pnpm -w` | Run a command in the workspace root |
| `pnpm publish -r` | Publish all workspace packages |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice npm / pnpm interactively** | [Open Terminal](https://technoscripts.com/cli/npm-pnpm/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/npm-pnpm-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type npm / pnpm Commands](https://technoscripts.com/command-playground/typing-practice/npm-pnpm/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
