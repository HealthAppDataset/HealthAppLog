# HealthLogLeak

HealthLogLeak is a dataset for studying privacy leakage in Android health application logs. It contains real-world log data collected from 25 health-related applications, along with manually validated annotations of privacy leakage instances.

## 📌 Overview

Mobile health applications generate large volumes of runtime logs during daily use, many of which may contain sensitive information. HealthLogLeak provides a curated dataset to facilitate research on privacy leakage detection and privacy-aware logging.

- 📱 25 real-world Android health applications  
- 📄 7.8 million+ log entries  
- 🔍 3,016 manually validated privacy leakage instances  
- 👥 Dual-annotator validation with high agreement  

---

## 📂 Dataset Structure

The dataset is organized as follows:

### 1. Log File Part 1/ Log File Part 2
Contains raw log files collected from each application.

### 2. Files with Privacy Leakage Information
Includes the number of log files that contain identified privacy leakage lines.

### 3. Sensitive_info
Provides annotations of sensitive information detected in logs, including different types of privacy leakage (e.g., device information, identifiers).

### 4. File Summary
This summarizes statistics for each application, such as the total number of lines and level distribution.

### 5. Apk Information
Contains metadata of analyzed applications, including package names and basic app information.

