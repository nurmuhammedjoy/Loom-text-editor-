# Loom-text-editor-
Sure! Here's a clean, user-friendly `README.md` you can use for your Git project:

---

# Loom - A Simple CLI Text Editor

**Loom** is a minimal and easy-to-use command-line text editor, heavily inspired by Vim.  
It is written in Python and designed for quick editing with a lightweight feel.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/loom.git
cd loom
```

### 2. Usage

You can start Loom by running:

```bash
python editor.py [yourfile.txt]
```

However, it's easier to **create an alias** so you can simply type:

```bash
loom [yourfile.txt]
```

#### Setting Up Alias (Optional but Recommended)

Add this line to your `.bashrc` or `.zshrc`

```bash
alias loom='python ~/loom/editor.py'
```

*(Replace `~/loom/editor.py` with the actual path.)*

Then reload your shell:

```bash
source ~/.bashrc
```
or

```bash
source ~/.zshrc
```

---

## How to Use Loom

| Action | Key |
| :--- | :--- |
| **Start inserting text** | Press `i` (INSERT mode) |
| **Return to NORMAL mode** | Press `ESC` |
| **Move cursor left** | `h` |
| **Move cursor down** | `j` |
| **Move cursor up** | `k` |
| **Move cursor right** | `l` |
| **Save file** | Press `w` |
| **Quit editor** | Press `q` |

---

## Example 

```bash
loom notes.txt    # Open or create notes.txt

# Press 'i' to enter INSERT mode
# Type your notes
# Press 'ESC' to go back to NORMAL mode
# Press 'w' to save
# Press 'q' to quit
```
