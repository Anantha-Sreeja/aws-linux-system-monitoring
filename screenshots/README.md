# Project Screenshots

This folder contains proof screenshots for the **AWS Linux System Monitoring** project.

---

## EC2 Instance Status
- EC2 instance running on AWS (t3.micro)
- Status checks passed
- Ubuntu 22.04 LTS

---

## System Monitoring Proof

### htop
- CPU usage per core
- Memory utilization
- Active processes

### Disk Usage
- `df -h` output showing disk usage under safe limits

### I/O Statistics
- `iostat` output showing low I/O wait

### Load Testing
- CPU stress test executed using:
  ```bash
  stress --cpu 2 --timeout 60
