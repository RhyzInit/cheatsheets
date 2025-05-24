# Neovim Beginner Cheat Sheet

## 🚀 Modes n Neovim

| Mode        | How to Enter  | Description                      |
|-------------|---------------|---------------------------------|
| Normal      | `Esc`         | Default mode, for navigation     |
| Insert      | `i`           | Insert text                     |
| Visual      | `v`           | Select text                    |
| Command     | `:`           | Run commands (like `:w`, `:q`) |
| Replace     | `R`           | Replace text as you type       |

---

## ✍️ Basic Insert Mode Commands

| Action                 | Key           |
|------------------------|---------------|
| Insert at cursor       | `i`           |
| Insert at line start   | `I`           |
| Insert below current line | `o`         |
| Insert above current line | `O`         |
| Append after cursor    | `a`           |
| Append at line end     | `A`           |

---

## 📦 Saving & Exiting

| Action                  | Command         |
|-------------------------|-----------------|
| Save                    | `:w`            |
| Quit                    | `:q`            |
| Save & quit             | `:wq` or `ZZ`   |
| Force quit (discard changes) | `:q!`        |

---

## 🧭 Navigation (Normal Mode)

| Move                      | Key               |
|---------------------------|-------------------|
| Left / Down / Up / Right  | `h` `j` `k` `l`   |
| Start / End of line       | `0` / `$`         |
| Next word                 | `w`               |
| Previous word             | `b`               |
| Top / Middle / Bottom of screen | `H` `M` `L`   |
| Go to line number `n`     | `:n`              |
| Go to file start / end    | `gg` / `G`        |

---

## ✂️ Editing

| Action                 | Key               |
|------------------------|-------------------|
| Delete character       | `x`               |
| Delete word            | `dw`              |
| Delete line            | `dd`              |
| Copy line              | `yy`              |
| Paste below cursor     | `p`               |
| Undo                   | `u`               |
| Redo                   | `Ctrl + r`        |

---

## 🔍 Searching

| Action                 | Command           |
|------------------------|-------------------|
| Search forward         | `/text` + Enter   |
| Search backward        | `?text` + Enter   |
| Next match             | `n`               |
| Previous match         | `N`               |

---

## 🧠 Visual Mode

| Action                 | Key               |
|------------------------|-------------------|
| Start visual select    | `v`               |
| Start linewise visual  | `V`               |
| Block select (column)  | `Ctrl + v`        |
| Copy selection         | `y`               |
| Delete selection       | `d`               |

---

## ⚙️ Useful Commands

| Purpose                | Command                 |
|------------------------|-------------------------|
| Open file              | `:e filename`           |
| Split window horizontal| `:sp filename`          |
| Split window vertical  | `:vsp filename`         |
| Move between splits    | `Ctrl + w` then `h/j/k/l` |
| Close current split    | `:q` or `Ctrl + w + c`  |

---

## 🧩 Neovim Plugin Tips (Optional)

| Action                  | Example Keybinding      |
|-------------------------|------------------------|
| File search (Telescope) | `<leader>ff`            |
| Live grep               | `<leader>fg`            |
| File explorer (NERDTree) | `<leader>e` or `<C-n>` |
| Plugin manager (Lazy)   | `:Lazy`                 |

---

## 🧼 Pro Tip

Start by learning the basics:  
`i`, `Esc`, `:wq`, `dd`, `yy`, `p`, and `u`.  
Build up your skills gradually!
