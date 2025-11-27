# Note
THIS IS VERY EXPERIMENTAL 


# LXin

LXin is an experimental programming language designed to let you run and combine multiple programming languages inside a single `.lx` file. Its purpose is to simplify multi-language development by allowing you to write Python, C#, JavaScript, shell scripts, and more all in one place without switching tools or juggling multiple files.

LXin works using simple English-style commands. The main command is:

```
Luse "<language>" : "<code>"
```

LXin reads the language name, captures the quoted code block, and routes the code to the correct interpreter or compiler. This lets you blend languages together inside a single workflow. Supported languages vary based on installed modules, but commonly include Python, JavaScript, C#, C/C++, and shell/bash.

---

## Platform-Aware Logic

LXin supports operating-system-specific conditions:

```
Lwhen Windows : "echo Windows-only code"
Lwhen Linux   : "echo Linux-only code"
Lwhen macOS   : "echo macOS-only code"
```

This allows scripts to run the correct code depending on the user's system, which makes cross-platform tools and automation far easier.

---

## Extensions With `lpipinstall`

LXin expands using:

```
lpipinstall "<module>"
```

This command lets LXin download and install:

- additional language support  
- interpreters or compilers  
- helper modules  
- GitHub-hosted tools  
- custom extensions  

It works similarly to Python’s `pip`, but tailored for LXin’s modular multi-language runtime.

---

## System Commands Installed

When LXin is installed, it adds the following commands:

| Command | Description |
|--------|-------------|
| `lxin` | Runs `.lx` scripts |
| `lxhelp` | Displays LXin documentation |
| `lpipinstall` | Installs or updates LXin extensions |

This makes LXin feel like a natural part of your command-line environment.

---

## Purpose of LXin

LXin is intended to be:

- **Simple** — beginners can learn multiple languages in one place  
- **Powerful** — advanced users can combine languages effortlessly  
- **Flexible** — ideal for tools, automation, scripts, games, prototypes, and experiments  

Rather than being just another language, LXin acts as a **bridge** connecting many languages, enabling more open, creative, and efficient coding.

---

# Help / Notes

**Important:**  
You must edit `fix pathfile` so it uses **your own system path**, not the placeholder path included in the experimental build.

There are **placeholder sections** inside the experimental LXin code.  
You should edit only those placeholders unless you are intentionally contributing to or modifying core systems.

---
