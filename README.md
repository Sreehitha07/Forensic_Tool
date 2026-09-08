# Endpoint Forensic Tool

A Python-based endpoint forensic analysis tool designed for collecting and analyzing system artifacts from Windows machines.

The tool brings multiple forensic collection capabilities into a single workflow to support endpoint investigation, system auditing, and digital-forensics experimentation.

## Features

- Collects Windows system and device information
- Retrieves connected USB device information
- Examines network and connectivity details
- Analyzes browser-related artifacts and download history
- Performs network-related forensic analysis
- Collects endpoint information using Windows APIs and PowerShell
- Generates structured forensic reports
- Supports PDF report generation
- Provides a graphical interface using Tkinter

## Technologies Used

- Python
- Windows APIs
- PowerShell
- Tkinter
- SQLite
- Pandas
- NumPy
- NetworkX
- Psutil
- Requests
- Ping3
- PyWin32
- ReportLab

## Repository Structure

~~~text
Forensic_Tool/
├── README.md
├── requirements.txt
├── .gitignore
└── src/
    └── forensic_tool.py
~~~

## System Requirements

This project is primarily designed for:

- Windows 10 / Windows 11
- Python 3.x

Some features depend on Windows-specific modules such as `winreg`, `win32com`, and PowerShell and therefore will not function on macOS or Linux.

## Installation

Clone the repository:

~~~bash
git clone https://github.com/Sreehitha07/Forensic_Tool.git
cd Forensic_Tool
~~~

Install the required dependencies:

~~~bash
pip install -r requirements.txt
~~~

## Running the Tool

Run:

~~~bash
python src/forensic_tool.py
~~~

Depending on the forensic operation being performed, administrator privileges may be required to access certain Windows system information.

## Dependencies

The main third-party dependencies include:

- networkx
- numpy
- pandas
- ping3
- psutil
- reportlab
- requests
- pywin32

See `requirements.txt` for installation details.

## Forensic Capabilities

The application combines multiple endpoint investigation techniques, including system-information collection, device inspection, network analysis, browser artifact analysis, and report generation.

The collected information can help investigators understand endpoint activity and review artifacts relevant to digital-forensic analysis.

## Platform Compatibility

The forensic collection functionality is intended primarily for Windows because it uses Windows-specific registry and COM interfaces.

Although some Python components are cross-platform, the complete application should be executed on a Windows environment.

## Future Improvements

Potential improvements include:

- Modularizing individual forensic collectors
- Adding automated test coverage
- Exporting evidence in additional formats
- Adding timeline-based artifact analysis
- Improving report visualization
- Adding configurable collection modules
- Supporting additional browser artifacts
- Adding structured logging and audit trails

## Ethical Use

This tool is intended for educational, research, and authorized forensic-analysis purposes only.

Use it only on systems that you own or have explicit permission to examine.

## Author

**Sreehitha Kosiganti**

GitHub: https://github.com/Sreehitha07
