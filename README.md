<h1>i3wm dotfile - BIOS Theme</h1>
<ul>
  <li><strong>i3wm</strong> - Window Manager</li>
  <li><strong>Polybar</strong> - Status bar </li>
  <li><strong>Rofi</strong> - Application launcher and menu</li>
  <li><strong>Alacritty</strong> - Terminal emulator</li>
</ul>

<h2>Installation</h2>

1. **Clone the repository and navigate to the directory :**
   ```bash
   git clone https://github.com/NeAdvokats/legacy-bios-dotfiles && cd legacy-bios-dotfiles
   ```

2. **Enter the following commands into the terminal one by one** to copy the configuration files :
   ```bash
   cp -r rofi ~/.config/
   cp -r i3 ~/.config/
   cp -r polybar ~/.config/
   cp -r alacritty ~/.config/
   ```
   *Note: The `-r` flag copies directories recursively, including all inner files.*

3. **Copy the `Walls` folder to your home directory :**
   ```bash
   cp -r Walls ~/
   ```

<h2>Key Binds</h2>

| Shortcut | Action |
| :--- | :--- |
| `SUPER` + `Enter` | Open terminal |
| `SUPER` + `SPACE` | Open Rofi menu |
| `SUPER` + `Q` | Close window |
| `SUPER` + `F` | Enter fullscreen mode for the focused container |
| `SUPER` + `Z` | Enter floating mode for the focused container |
| `SUPER` + `1-9` | Switch to workspace 1-9 |

<img src="https://raw.githubusercontent.com/NeAdvokats/legacy-bios-dotfiles/refs/heads/main/rice.png" />
