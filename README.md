# Lab 1 — Your first virtual machine

Pair: Dinmukhamed / Amira
Machine: OMEN by HP Laptop Arch Linux, guest Ubuntu Server 26.04.1
Date: <17.10.2026>

## What I did
1. Installed VirtualBox 7.2.20. Licence: https://www.virtualbox.org/wiki/GPLv3
2. Created VM lab01-ubuntu: 4 vCPU, 2 GB RAM, 25 GB dynamic disk, NAT.
3. Installed Ubuntu Server, took snapshot clean-install.
4. Broke it: sudo rm -rf /usr/bin
5. Rolled back to clean-install

## Resource justification
2GB and 4CPU it is comfortable for my pc (16CPU 16GB RAM)

## Result
The VM boots; the break-and-rollback cycle is shown in the evidence below.

## What did not work the first time
Nothing

## Evidence
- [evidence/vm-settings.png](evidence/vm-settings.png) — CPU, memory and disk as configured
- [evidence/guest-release.txt](evidence/guest-release.txt) — Ubuntu Server is running in the guest
- [evidence/broken.png](evidence/broken.png) — the guest in its broken state
- [evidence/snapshot-list.png](evidence/snapshot-list.png) — the snapshot, after the rollback
