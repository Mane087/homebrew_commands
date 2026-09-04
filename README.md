<img src="https://brew.sh/assets/img/homebrew-social-card.png" alt="homebrew-logo"/>

---

🇲🇽 [ES](https://github.com/Mane087/homebrew_commands) | 🇺🇸 [US](https://github.com/Mane087/homebrew_commands/blob/main/README_US.md)

| **Descripción**                                                             | **Comando**                                               | **Ejemplo**                                                     |
| ----------------------------------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------------------- |
| Buscar un paquete                                                       | <samp>brew search <paquete></samp>                    | <samp>brew search postgresql</samp>                         |
| Ver información de un paquete                                           | <samp>brew info <paquete></samp>                      | <samp>brew info node</samp>                                 |
| Instalar una fórmula                                                    | <samp>brew install <paquete></samp>                   | <samp>brew install git</samp>                               |
| Instalar una aplicación gráfica                                         | <samp>brew install --cask <aplicacion></samp>         | <samp>brew install --cask visual-studio-code</samp>         |
| Actualizar Homebrew                                                     | <samp>brew update</samp>                              | <samp>brew update</samp>                                    |
| Actualizar los paquetes instalados                                      | <samp>brew upgrade</samp>                             | <samp>brew upgrade</samp>                                   |
| Actualizar un paquete específico                                        | <samp>brew upgrade <paquete></samp>                   | <samp>brew upgrade node</samp>                              |
| Listar paquetes con actualizaciones disponibles                         | <samp>brew outdated</samp>                            | <samp>brew outdated</samp>                                  |
| Listar aplicaciones gráficas con actualizaciones disponibles            | <samp>brew outdated --cask</samp>                     | <samp>brew outdated --cask</samp>                           |
| Evitar que un paquete se actualice                                      | <samp>brew pin <paquete></samp>                       | <samp>brew pin node</samp>                                  |
| Permitir nuevamente la actualización de un paquete                      | <samp>brew unpin <paquete></samp>                     | <samp>brew unpin node</samp>                                |
| Desinstalar un paquete                                                  | <samp>brew uninstall <paquete></samp>                 | <samp>brew uninstall git</samp>                             |
| Desinstalar un paquete usando el alias `remove`                         | <samp>brew remove <paquete></samp>                    | <samp>brew remove git</samp>                                |
| Desinstalar una aplicación gráfica                                      | <samp>brew uninstall --cask <aplicacion></samp>       | <samp>brew uninstall --cask visual-studio-code</samp>       |
| Desinstalar una aplicación gráfica y eliminar configuraciones asociadas | <samp>brew uninstall --cask --zap <aplicacion></samp> | <samp>brew uninstall --cask --zap visual-studio-code</samp> |
| Listar todos los paquetes instalados                                    | <samp>brew list</samp>                                | <samp>brew list</samp>                                      |
| Listar fórmulas instaladas                                              | <samp>brew list --formula</samp>                      | <samp>brew list --formula</samp>                            |
| Listar aplicaciones gráficas instaladas                                 | <samp>brew list --cask</samp>                         | <samp>brew list --cask</samp>                               |
| Listar paquetes instalados con sus versiones                            | <samp>brew list --versions</samp>                     | <samp>brew list --versions</samp>                           |
| Mostrar la versión instalada de un paquete                              | <samp>brew list --versions <paquete></samp>           | <samp>brew list --versions node</samp>                      |
| Mostrar la versión de Homebrew                                          | <samp>brew --version</samp>                           | <samp>brew --version</samp>                                 |
| Listar paquetes principales instalados explícitamente                   | <samp>brew leaves</samp>                              | <samp>brew leaves</samp>                                    |
| Mostrar la ruta de instalación de un paquete                            | <samp>brew --prefix <paquete></samp>                  | <samp>brew --prefix node</samp>                             |
| Listar paquetes fijados                                                 | <samp>brew list --pinned</samp>                       | <samp>brew list --pinned</samp>                             |
| Limpiar versiones antiguas y caché                                      | <samp>brew cleanup</samp>                             | <samp>brew cleanup</samp>                                   |
| Simular la limpieza sin eliminar archivos                               | <samp>brew cleanup -n</samp>                          | <samp>brew cleanup -n</samp>                                |
| Eliminar todas las descargas almacenadas en caché                       | <samp>brew cleanup --prune=all</samp>                 | <samp>brew cleanup --prune=all</samp>                       |
| Eliminar dependencias que ya no son necesarias                          | <samp>brew autoremove</samp>                          | <samp>brew autoremove</samp>                                |
| Mostrar las dependencias de un paquete                                  | <samp>brew deps <paquete></samp>                      | <samp>brew deps node</samp>                                 |
| Mostrar las dependencias de un paquete en forma de árbol                | <samp>brew deps --tree <paquete></samp>               | <samp>brew deps --tree node</samp>                          |
| Mostrar qué paquetes dependen de otro paquete                           | <samp>brew uses <paquete></samp>                      | <samp>brew uses openssl</samp>                              |
| Mostrar qué paquetes instalados dependen de otro paquete                | <samp>brew uses --installed <paquete></samp>          | <samp>brew uses --installed openssl</samp>                  |
| Revisar el estado de Homebrew y detectar problemas                      | <samp>brew doctor</samp>                              | <samp>brew doctor</samp>                                    |
| Mostrar la configuración actual de Homebrew                             | <samp>brew config</samp>                              | <samp>brew config</samp>                                    |

> <samp>--zap</samp> realiza una desinstalación más agresiva y puede eliminar configuraciones asociadas.
>
> <samp>-n</samp> funciona como `dry-run`: muestra qué elementos se eliminarían sin realizar la limpieza.


