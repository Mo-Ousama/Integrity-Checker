# Integrity-Checker
The Integrity Checker aims to provide security for operating systems. The tool will ensure the integrity and security of system files by verifying their integrity against known hashes or checksums. It will regularly scan the operating system files and compare them with a trusted database to detect any unauthorized modifications or tampering.
📝 Overview

This project is a File Integrity Monitoring (FIM) system designed to detect unauthorized modifications, deletions, or additions to files by comparing their SHA-256 hashes against a trusted baseline. It is ideal for security auditing, compliance checks, and intrusion detection.

Demo Python License
🔑 Key Features

    SHA-256 Hash Calculation: Generate unique file fingerprints.

    Trusted Database: Store baseline hashes in a JSON file.

    Email Alerts: Receive notifications via Gmail SMTP when changes are detected.

    Periodic Scans: Schedule scans at customizable intervals (e.g., every 5 minutes).

    CLI Support: Easy-to-use command-line interface for generating baselines and running scans.

    New File Detection: Identify files added after the baseline was created.

