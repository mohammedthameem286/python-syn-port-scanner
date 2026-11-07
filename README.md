# Python TCP SYN Port Scanner

A beginner-level network port scanner developed using
Python 3 and Scapy in Kali Linux.

## Project Overview

This project demonstrates TCP SYN scanning techniques
to examine selected TCP ports on a target host.

It was developed as a hands-on cybersecurity learning
project to understand network scanning and TCP/IP
communication.

## Technologies Used

- Python 3
- Scapy
- Kali Linux
- TCP/IP Networking

## Features

- Accepts a target IP address.
- Scans multiple user-specified TCP ports.
- Sends TCP SYN packets.
- Displays responses received from the target.

## Installation

Update Kali Linux:

    sudo apt update

Install Scapy:

    sudo apt install python3-scapy -y

## How to Run

Navigate to the project directory:

    cd ~/projects/python-syn-port-scanner

Run the scanner:

    sudo python3 portscanner.py

Enter the target IP and ports when prompted.

## Example

Target IP: 127.0.0.1

Ports: 8080,80,443,22

## Local Testing

Start a local HTTP server:

    python3 -m http.server 8080

Run the scanner in another terminal and test
against 127.0.0.1 on port 8080.

## Purpose

This project was created for educational purposes
to develop practical knowledge of Python programming,
Scapy, TCP SYN scanning and network security.

## Disclaimer

Use this tool only on systems you own or have
explicit permission to test.
