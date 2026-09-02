# System Baseline — Pre-Hardening

## Environment

- OS: Ubuntu 26.04.1 LTS
- Architecture: x86-64
- Virtualisation: Oracle VirtualBox
- Hostname: ubuntu-target
- Network mode: VirtualBox NAT

## Initial Security State

### SSH

OpenSSH was installed during the Ubuntu installation and was
actively listening on TCP port 22.

### Firewall

UFW was installed but inactive at the beginning of the lab.

## Purpose

This baseline records the initial security state of the Ubuntu
target before applying hardening measures.

The baseline will be compared against the system after hardening
to demonstrate the effect of the security controls implemented
during the project.

### Screenshot not shown for security reasons.
