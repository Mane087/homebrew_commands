<img src="https://brew.sh/assets/img/homebrew-social-card.png" alt="homebrew-logo"/>

---

### Buscar un paquete
`brew search <paquete>`

### Ver información del paquete
`brew info <paquete>`

### Instalar una fórmula
`brew install <paquete>`

### Instalar una aplicación gráfica
`brew install --cask <aplicacion>`

### Ejemplos

```zsh
brew search postgresql
brew info node
brew install git
brew install --cask visual-studio-code
```

---

### Actualizar todos los paquetes o un paquete
`brew update | <paquete>`

### Actualizar paquetes internos de Homebrew
`brew upgrade`

### Listar paquetes con actualizaciones
`brew outdated | brew outdated --cask`

### Evitar que un paquete se actualice
`brew pin <paquete>`

### Permitir actualizar un paquete
`brew unpin <paquete>`

---

### Desinstalar un paquete
`brew uninstall <paquete> | brew remove <paquete> | brew uninstall --cask <aplicacion> | brew uninstall --cask --zap <aplicacion>`

> --zap es más agresivo porque puede eliminar configuraciones asociadas.

---

### Listar paquetes instalados
`brew list | brew list --formula | brew list --cask | brew list --versions | brew list --versions <paquete>`

### Version de Homebrew
`brew --version`

### Información de un paquete 
`brew info <paquete>`

### Listar paquetes principales
`brew leaves`

### Ruta de instalación de un paquete
`brew --prefix <paquete>`

### Listar paquetes fijados
`brew list --pinned`

---

### Limpiar versiones antiguas y caché
`brew cleanup | brew cleanup -n`
> `-n` es un flag `dry-run` para saber qué va a borrar sin que lo haga 

### Eliminar descargas almacenadas
`brew cleanup --prune=all`

### Eliminar dependencias no utilizadas 
`brew autoremove`

---

### Dependencias de un paquete
`brew deps <paquete> | brew deps --tree <paquete>`

### Dependencias de un paquete sobre otro
`brew uses <paquete> | brew uses --installed <paquete>`

---

### Estado de Homebrew
`brew doctor`

### Configuración de Homebrew
`brew config`



