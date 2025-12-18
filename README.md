# Linux Support Lab – GCP

## 📌 Project Overview
This project demonstrates hands-on Linux system administration and troubleshooting skills by simulating real-world IT support scenarios on a cloud-based Ubuntu server hosted on Google Cloud Platform (GCP).

## 🛠️ Environment
- Cloud Provider: Google Cloud Platform (GCP)
- OS: Ubuntu 24.04 LTS
- Access: SSH (Browser-based)
- Role Simulated: Linux L1/L2 Support Engineer

---

## 🔹 Scenario 1: User Management
**Problem:** New employee requires Linux access.

**Actions:**
- Created user using `useradd`
- Assigned password using `passwd`
- Verified user and groups using `id`

**Outcome:** User account successfully created.

---

## 🔹 Scenario 2: Sudo Permission Issue
**Problem:** User unable to run administrative commands.

**Investigation:**
- Switched user using `su`
- Identified sudo access error

**Fix:**
- Added user to sudo group using `usermod -aG sudo`

**Outcome:** User granted admin privileges.

---

## 🔹 Scenario 3: File Permission Issue
**Problem:** Application unable to write to log file.

**Actions:**
- Created application directory under `/opt`
- Simulated permission error using `chmod`
- Fixed ownership using `chown`

**Outcome:** Permission issue resolved.

---

## 🔹 Scenario 4: Log Analysis
**Problem:** System showing unexpected behavior.

**Actions:**
- Investigated logs under `/var/log`
- Analyzed recent entries using `tail`
- Reviewed detailed system logs using `journalctl`

**Outcome:** Identified system and service-related errors.

---

## 📸 Screenshots
Screenshots for each scenario are available in the `screenshots/` directory.

---

## 🎯 Skills Demonstrated
- Linux User & Group Management
- File Permissions & Ownership
- Log Analysis (`/var/log`, `journalctl`)
- Cloud-based Linux Administration (GCP)
- Real-world IT Support Troubleshooting

