# T-labzz

**Terminal Lab Preparation Automation – by Yi-Kyu**

**T-labzz** is a pure Bash automation utility designed to prepare your terminal and folder structure for efficient pentesting workflows.  
Inspired by s4vitar's environment, this tool runs under root and performs a clean, structured setup for your engagements.

Unlike flashy tools, **T-labzz** avoids unnecessary aesthetics to keep things fast, minimal, and functional.

---

## What It Does

T-labzz automates:

- Terminal workspace initialization
- Directory structure creation for new targets
- IPv4 format validation
- Root-level setup commands
- Smart tab labeling using `xdotool`

All of this happens automatically from the moment the script runs.

---

## Important Note

**Once T-labzz starts running, do not close or switch the terminal.**  
Interrupting it mid-process may cause misconfigurations or incomplete setups.

---

## Root Access Required

T-labzz checks your UID and will exit if not run with `sudo` or as `root`.  
This ensures proper creation of directories and execution of terminal commands.

---

## Installation

```bash
git clone https://github.com/Yi-Kyu/T-labzz.git
chmod +x T-labzz
sudo mv T-labzz /usr/local/bin/
```
--- 

## License

MIT License – Use, modify, and distribute freely. Stay ethical.

Special thanks to [s4vitar](https://github.com/s4vitar) for the inspiration and for the `mkt` function used for enumeration setup.

---

## Author
Yi-Kyu

Terminal Automation • Pentesting Workflow 
GitHub: github.com/Yi-Kyu
