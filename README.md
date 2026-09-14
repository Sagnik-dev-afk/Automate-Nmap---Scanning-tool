# Network Scanner / Nmap Automation Project

This Python project runs a network scan using the `python-nmap` wrapper. To prevent dependency conflicts with system packages, all execution and package management should be done inside a Python virtual environment (`venv`).

---

## Prerequisites

- **Python 3.8+**
- **Nmap binary**: `python-nmap` is only a Python wrapper around the system's Nmap executable.
  - **Linux (Debian/Ubuntu):** `sudo apt update && sudo apt install -y nmap`
  - **macOS:** `brew install nmap`
  - **Windows:** Download and install from [nmap.org](https://nmap.org/download.html), and ensure `nmap.exe` is added to your system `PATH`.

---

## Setup & Installation

### 1. Create a Virtual Environment
Run the following command in the project root directory:

```bash
# Linux/macOS
python3 -m venv venv

# Windows
python -m venv venv
