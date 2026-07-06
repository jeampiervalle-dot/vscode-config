# VSCode Config

Mi configuración personal de Visual Studio Code.

## Instalación

### 1. Copiar settings.json

```bash
# Linux
cp settings.json ~/.config/Code/User/settings.json

# macOS
# cp settings.json ~/Library/Application\ Support/Code/User/settings.json

# Windows
# copy settings.json %APPDATA%\Code\User\settings.json
```

### 2. Extensiones necesarias

Abre VSCode, ve a la pestaña de Extensiones (`Ctrl+Shift+X`), busca e instala:

| Extensión | ID | Propósito |
|-----------|----|-----------|
| Catppuccin | `Catppuccin.catppuccin-vsc` | Tema de color |
| Catppuccin Icons | `Catppuccin.catppuccin-vsc-icons` | Iconos del tema |
| Prettier | `esbenp.prettier-vscode` | Formateo al guardar |
| Animations | `brandonkirbyson.vscode-animations` | Animaciones suaves |
| Custom UI Style | `custom-ui-style` | Estilos UI personalizados |
| File Peek | `file_peek` | Vista previa de archivos |
| Background | `background` | Fondo personalizado |
| Kilo Code | `kilo-code.new` | Autocompletado con IA |

O instala todo desde la terminal:

```bash
code --install-extension Catppuccin.catppuccin-vsc
code --install-extension Catppuccin.catppuccin-vsc-icons
code --install-extension esbenp.prettier-vscode
code --install-extension brandonkirbyson.vscode-animations
code --install-extension kilo-code.new
code --install-extension file_peek
code --install-extension custom-ui-style
code --install-extension background
```

### 3. Fuente JetBrains Mono (opcional pero recomendada)

```bash
# Linux
sudo apt install fonts-jetbrains-mono

# macOS
# brew install --cask font-jetbrains-mono

# Windows
# Descargar de https://www.jetbrains.com/lp/mono/
```

La terminal usa `JetBrainsMono Nerd Font Mono`. Descargar de [Nerd Fonts](https://www.nerdfonts.com/font-downloads).
