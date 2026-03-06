# Maven Commands Cheatsheet

> Maven is a build automation tool for Java. Build, test, and package Java projects with a single command.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `mvn clean` | Remove compiled output and build files |
| `mvn compile` | Compile the project source code |
| `mvn package` | Package compiled code into JAR/WAR |
| `mvn install` | Install package into local repository |
| `mvn deploy` | Deploy package to remote repository |
| `mvn validate` | Validate the project configuration |
| `mvn verify` | Run integration tests and verify |
| `mvn site` | Generate project documentation site |
| `mvn archetype:generate` | Create a project from an archetype |
| `mvn wrapper:wrapper` | Generate Maven wrapper scripts |
| `mvn versions:set` | Set the project version |
| `mvn dependency:tree` | Display the dependency tree |
| `mvn dependency:resolve` | Resolve and download all dependencies |
| `mvn dependency:analyze` | Analyze used and unused dependencies |
| `mvn dependency:copy-dependencies` | Copy dependencies to a directory |
| `mvn dependency:purge-local-repository` | Purge local repo dependencies |
| `mvn versions:display-dependency-updates` | Show available dependency updates |
| `mvn versions:use-latest-versions` | Update to latest dependency versions |
| `mvn test` | Run unit tests |
| `mvn test -Dtest=` | Run a specific test class |
| `mvn surefire:test` | Run tests using Surefire plugin |
| `mvn failsafe:integration-test` | Run integration tests |
| `mvn surefire-report:report` | Generate test report |
| `mvn jar:jar` | Create a JAR file |
| `mvn war:war` | Create a WAR file |
| `mvn source:jar` | Create a JAR of source files |
| `mvn javadoc:jar` | Create a JAR of Javadoc |
| `mvn assembly:single` | Create a single assembly archive |
| `mvn shade:shade` | Create an uber-JAR with dependencies |
| `mvn install:install-file` | Install a JAR to the local repo |
| `mvn deploy:deploy-file` | Deploy a JAR to a remote repo |
| `mvn dependency:get` | Download a specific artifact |
| `mvn help:effective-pom` | Display the effective POM |
| `mvn help:effective-settings` | Display effective settings |
| `mvn help:describe` | Describe a plugin or goal |
| `mvn help:system` | Display system and environment info |
| `mvn -v` | Display Maven version information |
| `mvn versions:display-plugin-updates` | Show available plugin updates |
| `mvn plugin:help` | Show plugin help information |
| `mvn enforcer:enforce` | Enforce project rules |
| `mvn -pl` | Build specific modules only |
| `mvn -am` | Also build required modules |
| `mvn -amd` | Also build dependent modules |
| `mvn -rf` | Resume build from a specific module |
| `mvn release:prepare` | Prepare a release version |
| `mvn release:perform` | Perform the release deployment |
| `mvn -T` | Build with parallel threads |
| `mvn -o` | Work in offline mode |
| `mvn -X` | Enable debug output |
| `mvn -P` | Activate a build profile |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Maven interactively** | [Open Terminal](https://technoscripts.com/cli/maven/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/maven-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Maven Commands](https://technoscripts.com/command-playground/typing-practice/maven/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
