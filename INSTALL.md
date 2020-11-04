# Installation

## Oh My Zsh

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/Masterkraft0r/zsh-find ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-find
    ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

    ```sh
    plugins=(zsh-find)
    ```

3. Start a new terminal session.

## Manual (Git Clone)

1. Clone this repository somewhere on your machine. This guide will assume `~/.zsh/zsh-find`.

    ```sh
    git clone https://github.com/Masterkraft0r/zsh-find ~/.zsh/zsh-find
    ```

2. Add the following to your `.zshrc`:

    ```sh
    source ~/.zsh/zsh-find/zsh-find.zsh
    ```

3. Start a new terminal session.