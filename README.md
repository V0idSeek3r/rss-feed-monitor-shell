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

## Summary
This project is a lightweight yet powerful solution for integrating RSS feed monitoring into daily terminal usage.

![image](https://github.com/user-attachments/assets/a6107bb8-3a67-4f8f-95f6-8ba4dab61c15)
