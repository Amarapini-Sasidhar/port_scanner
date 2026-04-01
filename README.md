# Amarapini Sasidhar Port Scanner

Amarapini Sasidhar Port Scanner is a desktop-based network scanning utility built with Python and Tkinter. It provides a simple graphical interface for launching common Nmap scans and viewing the output inside the application window.

This README has been fully rewritten with original wording and updated author details.

## What This Project Does

The application helps users:

- enter a target host or IP address
- define a port range for basic scans
- run several popular Nmap scan modes
- review live scan output in a scrollable text area
- stop a running scan from the interface
- clear previous output
- save results to a text file
- switch between dark and light display modes

## Included Scan Modes

- Basic port scan
- SYN scan
- Service version detection
- Operating system detection
- Aggressive scan

## Tech Stack

- Python 3
- Tkinter
- Nmap
- Python threading

## Project Files

- `amarapini_sasidhar_port_scanner.py` - main GUI application
- `README.md` - project documentation

## Requirements

Make sure the following are installed before running the program:

- Python 3
- Nmap
- Tkinter support for Python

## Installation

### Linux

```bash
sudo apt update
sudo apt install python3 python3-tk nmap -y
```

### Windows

1. Install Python 3 from the official Python website.
2. Install Nmap from the official Nmap website.
3. Ensure Python is added to your system PATH.

## How To Run

From the project folder, launch:

```bash
python amarapini_sasidhar_port_scanner.py
```

On Linux systems where `python` maps differently, use:

```bash
python3 amarapini_sasidhar_port_scanner.py
```

## How To Use

1. Open the application.
2. Enter the target hostname or IP address.
3. For a basic scan, provide start and end ports.
4. Choose a scan type using the buttons.
5. Watch the results appear in the output panel.
6. Save the output if needed.

## Results

### Sample Result 1

Basic scan output for `scanme.nmap.org` displayed in the GUI:

![Scan result for scanme.nmap.org](result_scan_scanme.png)

### Sample Result 2

Basic scan output for `google.com` displayed in the GUI:

![Scan result for google.com](result_scan_google.png)

## Notes

- OS detection and aggressive scans may require elevated privileges depending on the operating system.
- Results depend on the target host, firewall rules, and network accessibility.
- The stop option halts UI output for the running scan, but underlying process behavior may depend on the platform.

## Intended Use

This project is suitable for:

- cybersecurity practice labs
- local network inspection
- learning how GUI wrappers can interact with command-line tools
- basic demonstrations of Nmap scan types

Use this tool only on systems and networks you are authorized to test.

## Author

Amarapini Sasidhar
