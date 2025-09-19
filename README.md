# My Configuration Files

This repository stores my personal configuration files for various tools.

## Oh My Posh

This repository contains themes for [Oh My Posh](https://ohmyposh.dev/), a prompt theme engine for any shell.

### Themes

*   **green**: A green-based theme that displays session, path, and git status information.

### Installation

1.  Install Oh My Posh by following their [installation guide](https://ohmyposh.dev/docs/installation).
2.  Copy the theme file(s) from the `oh-my-posh/themes` directory to your Oh My Posh themes directory.
3.  Configure your shell's profile to use the theme. For example, in PowerShell:
    ```powershell
    oh-my-posh init pwsh --config "$HOME/.poshthemes/green.omp.json" | Invoke-Expression
    ```
    *(Replace `$HOME/.poshthemes/` with your actual theme directory if different.)*
