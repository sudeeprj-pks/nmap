# Scanning and Enumerating a Local Network with Nmap (Project 1)

## Overview
This project demonstrates basic Nmap usage on Kali Linux for discovering hosts and services on a local network. All scans were performed in a controlled lab environment with permission.

## Structure
- `scans/` — nmap outputs (task1..task5)
- `run_scans.sh` — script to run all scans
- `notes/` — analysis & observations

## How to reproduce
1. Clone repo: `git clone https://github.com/USERNAME/nmap-project-1.git`
2. Inspect scan scripts and run them in a network you are permitted to test.

## Key commands used
- `nmap 10.0.2.15/24 -oN task1_basic_scan.txt`
- `nmap -p 80 10.0.2.15/24 -oN task2_port80.txt`
- `sudo nmap -O 10.0.2.15/24 -oN task4_os_detection.txt`
- `sudo nmap -A 10.0.2.15/24 -oA task5_aggressive_scan`

## Findings
