# System Monitor and Application Health Checker

This repository contains Python scripts for:
1. Monitoring the health of a Linux system.
2. Checking the uptime and health of an application using HTTP status codes.

## Scripts

### 1. System Health Monitoring Script
File: `system_health_monitor.py`

#### Description
This script monitors:
- CPU usage
- Memory usage
- Disk space
- Running processes

If any of these metrics exceed predefined thresholds, it logs alerts in `system_health.log`.

#### How to Run
1. Ensure you have Python installed on your system.
2. Install the `psutil` library:
   ```bash
   pip install psutil
