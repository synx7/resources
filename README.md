# resources

Standalone binaries and installers pulled in by the [synxOS](https://github.com/synx7/synxOS) playbook during install. Not meant to be browsed or installed manually — grab what you need from [Releases](https://github.com/synx7/resources/releases/latest) if you're looking for a specific tool.

## Contents (latest release)

| Asset | What it is |
|---|---|
| `synxAFF.exe` | Standalone tool |
| `synxUEFI.exe` | Standalone tool |
| `synxshot-installer.zip` | Installer bundle for synxshot (the Lightshot replacement used by [synxOS](https://github.com/synx7/synxOS)) — contains `install-synxshot.ps1`/`.cmd`, `synxshot.exe`, and `uninstall-synxshot.ps1` |

## synxshot install

1. Download and extract `synxshot-installer.zip`.
2. Run `install-synxshot.cmd` (or `install-synxshot.ps1` directly).
3. It copies `synxshot.exe` to `%LOCALAPPDATA%\Programs\synxshot`, adds a Start Menu shortcut, registers an uninstall entry, and launches it.
4. To remove it, run `uninstall-synxshot.ps1` from the install folder (or use "Add or Remove Programs").
