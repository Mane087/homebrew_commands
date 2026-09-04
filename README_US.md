<img src="https://brew.sh/assets/img/homebrew-social-card.png" alt="homebrew-logo"/>

---


| **Description**                                                             | **Command**                                            | **Example**                                                 |
| --------------------------------------------------------------------------- | ------------------------------------------------------ | ----------------------------------------------------------- |
| Search for a package                                                        | <samp>brew search <package></samp>                     | <samp>brew search postgresql</samp>                         |
| View package information                                                    | <samp>brew info <package></samp>                       | <samp>brew info node</samp>                                 |
| Install a formula                                                           | <samp>brew install <package></samp>                    | <samp>brew install git</samp>                               |
| Install a graphical application                                             | <samp>brew install --cask <application></samp>         | <samp>brew install --cask visual-studio-code</samp>         |
| Update Homebrew                                                             | <samp>brew update</samp>                               | <samp>brew update</samp>                                    |
| Upgrade installed packages                                                  | <samp>brew upgrade</samp>                              | <samp>brew upgrade</samp>                                   |
| Upgrade a specific package                                                  | <samp>brew upgrade <package></samp>                    | <samp>brew upgrade node</samp>                              |
| List packages with available updates                                        | <samp>brew outdated</samp>                             | <samp>brew outdated</samp>                                  |
| List graphical applications with available updates                          | <samp>brew outdated --cask</samp>                      | <samp>brew outdated --cask</samp>                           |
| Prevent a package from being upgraded                                       | <samp>brew pin <package></samp>                        | <samp>brew pin node</samp>                                  |
| Allow a package to be upgraded again                                        | <samp>brew unpin <package></samp>                      | <samp>brew unpin node</samp>                                |
| Uninstall a package                                                         | <samp>brew uninstall <package></samp>                  | <samp>brew uninstall git</samp>                             |
| Uninstall a package using the `remove` alias                                | <samp>brew remove <package></samp>                     | <samp>brew remove git</samp>                                |
| Uninstall a graphical application                                           | <samp>brew uninstall --cask <application></samp>       | <samp>brew uninstall --cask visual-studio-code</samp>       |
| Uninstall a graphical application and remove associated configuration files | <samp>brew uninstall --cask --zap <application></samp> | <samp>brew uninstall --cask --zap visual-studio-code</samp> |
| List all installed packages                                                 | <samp>brew list</samp>                                 | <samp>brew list</samp>                                      |
| List installed formulas                                                     | <samp>brew list --formula</samp>                       | <samp>brew list --formula</samp>                            |
| List installed graphical applications                                       | <samp>brew list --cask</samp>                          | <samp>brew list --cask</samp>                               |
| List installed packages and their versions                                  | <samp>brew list --versions</samp>                      | <samp>brew list --versions</samp>                           |
| Show the installed version of a package                                     | <samp>brew list --versions <package></samp>            | <samp>brew list --versions node</samp>                      |
| Show the Homebrew version                                                   | <samp>brew --version</samp>                            | <samp>brew --version</samp>                                 |
| List top-level packages installed explicitly                                | <samp>brew leaves</samp>                               | <samp>brew leaves</samp>                                    |
| Show the installation path of a package                                     | <samp>brew --prefix <package></samp>                   | <samp>brew --prefix node</samp>                             |
| List pinned packages                                                        | <samp>brew list --pinned</samp>                        | <samp>brew list --pinned</samp>                             |
| Clean up old versions and cache files                                       | <samp>brew cleanup</samp>                              | <samp>brew cleanup</samp>                                   |
| Simulate cleanup without deleting files                                     | <samp>brew cleanup -n</samp>                           | <samp>brew cleanup -n</samp>                                |
| Remove all cached downloads                                                 | <samp>brew cleanup --prune=all</samp>                  | <samp>brew cleanup --prune=all</samp>                       |
| Remove dependencies that are no longer needed                               | <samp>brew autoremove</samp>                           | <samp>brew autoremove</samp>                                |
| Show a package's dependencies                                               | <samp>brew deps <package></samp>                       | <samp>brew deps node</samp>                                 |
| Show a package's dependencies as a tree                                     | <samp>brew deps --tree <package></samp>                | <samp>brew deps --tree node</samp>                          |
| Show which packages depend on another package                               | <samp>brew uses <package></samp>                       | <samp>brew uses openssl</samp>                              |
| Show which installed packages depend on another package                     | <samp>brew uses --installed <package></samp>           | <samp>brew uses --installed openssl</samp>                  |
| Check Homebrew's status and detect problems                                 | <samp>brew doctor</samp>                               | <samp>brew doctor</samp>                                    |
| Show the current Homebrew configuration                                     | <samp>brew config</samp>                               | <samp>brew config</samp>                                    |

> <samp>--zap</samp> performs a more aggressive uninstall and may remove associated configuration files.
>
> <samp>-n</samp> works as a `dry-run`: it shows which items would be removed without actually performing the cleanup.
