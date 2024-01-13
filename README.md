# System Information Retrieval Script

## Introduction

This Python script retrieves various system-related information such as installed software, internet speed, and system specifications. It utilizes several Python modules to gather data on the operating system, hardware components, and network connectivity.

## Dependencies

The script requires the following Python modules. Install them using the following commands:

```bash
pip install uuid
pip install psutil
pip install speedtest-cli
pip install platform
pip install os
pip install GPUtil
pip install pyobjc  # Note: pyobjc is required for macOS specific features (commented out in the code).

