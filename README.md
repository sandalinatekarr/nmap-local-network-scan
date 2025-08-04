# nmap-local-network-scan

This project performs a local network scan using Nmap on the subnet `192.168.1.0/24`.

## Command Used

```bash
sudo nmap -sT -Pn 192.168.1.0/24 > scan_results.txt
