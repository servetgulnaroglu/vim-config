
# Vim Configuration Guide

This guide will walk you through installing Vim and configuring it with the provided \`.vimrc\` file. Instructions are provided for both macOS and Windows operating systems.

## macOS Installation

### 1. Install Vim
You can install Vim on macOS using Homebrew. Open Terminal and run:
```bash copy
brew install vim
```

### 2. Download the .vimrc file
Clone the repository or download the \`.vimrc\` file from the [GitHub repository](https://github.com/your-username/your-repo).

### 3. Copy the .vimrc file to your home directory
In Terminal, navigate to the directory containing the downloaded \`.vimrc\` file and run:
```bash copy
cp .vimrc ~/
```

## Windows Installation

### 1. Install Vim
You can download the Vim installer for Windows from the [official website](https://www.vim.org/download.php).

### 2. Download the .vimrc file
Clone the repository or download the \`.vimrc\` file from the [GitHub repository](https://github.com/your-username/your-repo).

### 3. Copy the .vimrc file to your home directory
Copy the \`.vimrc\` file to your user home directory, usually located at \`C:\\Users\\YourUsername\`.

## Final Step
After following the above steps, open Vim, and you should see the configurations from the \`.vimrc\` file applied.

If you encounter any issues or have any questions, please refer to the repository or feel free to open an issue.

Happy coding with Vim!




# Vim Cheat Sheet

This document provides an extensive collection of Vim commands that aid in navigation, editing, searching, and more. These commands are primarily used in Normal Mode, so remember to press 'ESC' before utilizing them.

## Basic Movements
- **h:** Move cursor left.
- **j:** Move cursor down.
- **k:** Move cursor up.
- **l:** Move cursor right.

## Modes
- **Esc:** Normal Mode
- **i:** Insert text before the cursor
- **I:** Insert text at the beginning of the line
- **a:** Append text after the cursor
- **A:** Append text at the end of the line
- **v:** Visual Mode (character-wise)
- **V:** Visual Mode (line-wise)
- **Ctrl+v:** Visual Mode (block-wise)
- **::** Command-line Mode
- **r:** Replace a single character
- **R:** Replace mode (continuous replace)

## Word Movements
- **w:** Move to the start of the next word.
- **b:** Move to the start of the current/previous word.

## Line Movements
- **0:** Move to the start of the line.
- **^:** Move to the first non-blank character.
- **$:** Move to the end of the line.
- **%:** Jump to the matching brace or bracket.

## Screen Movements
- **H:** Move to the top of the screen.
- **M:** Move to the middle of the screen.
- **L:** Move to the bottom of the screen.
- **zz:** Center the current line.
- **zt:** Move the current line to the top.

## Paragraph and Block Movements
- **{:** Start of the current paragraph/block.
- **}:** End of the current paragraph/block.

## File Movements
- **gg:** Start of the file.
- **G:** End of the file.
- **:<line_number>:** Go to a specific line.

## Jump Movements
- **gd:** Go to definition.
- **ctrl-o:** Previous location.
- **ctrl-i:** Next location.
- **'m:** Jump to mark 'm'.
- **[g, ]g:** Navigate diagnostics.
- **<F2>:** Rename occurrences.

## Additional
- **Shift 3:** Highlight All Occurrences
- **n:** Navigate highlights.
- **:noh:** Clear highlights.

## Scrolling
- **ctrl-u:** Scroll up (half-screen).
- **ctrl-d:** Scroll down (half-screen).
- **ctrl-b:** Scroll up (full screen).
- **ctrl-f:** Scroll down (full screen).

## Search
- **/<word>:** Search for a word.
- **ge:** Replace word under cursor.

## Editing
- **diw:** Delete current word.
- **yiw:** Copy the current word.
- **u:** Undo.
- **p:** Paste copied by yiw (pastes after the cursor).
- **shift+p:** Paste before the cursor.

## Fold
- **zf:** Fold at current indent level.
- **za:** Toggle current fold.

## NERDTree
- **<leader>n:** Focus NERDTree (C means CTRL).
- **<C-n>:** Toggle NERDTree.
- **<leader>:** A key specified in .vimrc, my leader key is a comma ','.

## Window Resizing
- **++:** Increase window width.
- **--:** Decrease window width.
- **:new:** Create new buffer horizontally.
- **:vnew:** Create new buffer vertically.
- **CTRL+w+ <arrow_key from hjkl>:** Move between windows.

## Buffers
- **gb:** List buffers.
- **bd:** Delete current buffer.
- **bd!:** Delete current buffer without saving changes.
- **b<buffer_number>:** Go to a specific buffer.

## Session
- **mks!:** Create a session.
- **vim -S:** Load a session.

## File Operations
- **:w:** Save file.
- **:q:** Quit without saving.
- **:q!:** Force quit without saving.
- **:wq:** Save and quit.
