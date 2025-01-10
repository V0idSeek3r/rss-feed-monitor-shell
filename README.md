# RSS Feed Monitor for Shell Environments

## Overview
This project addresses the need for an automated program that runs every time a shell session is opened. Its primary function is to fetch and parse RSS feeds, actively monitoring for the presence of specific terms defined by the user.

## Key Features
- **Automated Execution**: The program is designed to execute automatically when a shell session starts, ensuring seamless integration with the user's workflow.
- **RSS Feed Parsing**: It retrieves and parses RSS feeds from configurable URLs to gather the latest entries.
- **Keyword Monitoring**: The program scans each feed entry for user-defined terms, highlighting matches for easy identification.
- **Real-Time Feedback**: Outputs are displayed directly in the shell, providing immediate insights into relevant feed updates.

## Use Case
This tool is ideal for users who need to stay informed about specific topics or updates (e.g., security vulnerabilities, software releases, etc.) by monitoring RSS feeds during their shell sessions. It enhances productivity by combining routine shell usage with real-time information monitoring.

## Technology Stack
- **Python**: Used for the core implementation, including RSS parsing and keyword matching.
- **Libraries**:
  - `requests` for HTTP requests.
  - `xml.etree.ElementTree` for XML parsing.
  - `re` for regular expression-based keyword searching.
  - `colorama` for terminal output styling.

## Installation Guide

### Prerequisites
1. **Python 3.x**: Ensure Python is installed on your system. You can verify this by running:
   ```python3 --version```
   If Python is not installed, follow the instructions for your operating system to install it.

2. **Required Python Libraries**: Install the necessary dependencies using `pip`:
   ```pip install requests colorama```

3. **Download the Script**: Save the Python script (e.g., `rss_monitor.py`) in a directory of your choice. For example:
   ```mkdir -p ~/scripts```
   ```mv rss_monitor.py ~/scripts/```

### Integrate with `.bashrc`
1. Open your `.bashrc` file for editing:
   ```nano ~/.bashrc```

2. Add the following line to automatically execute the script when a new shell session starts:
   ```python3 ~/scripts/rss_monitor.py```

3. Save and close the file (`Ctrl + O`, then `Ctrl + X`).

4. Reload your `.bashrc` to apply the changes immediately:
   ```source ~/.bashrc```

### Testing
Open a new terminal session to verify that the script runs automatically. If there are any issues, double-check the `.bashrc` configuration and ensure the script path is correct.

---

## Summary
This project is a lightweight yet powerful solution for integrating RSS feed monitoring into daily terminal usage.


![image](https://github.com/user-attachments/assets/a6107bb8-3a67-4f8f-95f6-8ba4dab61c15)
