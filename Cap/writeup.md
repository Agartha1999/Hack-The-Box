# Cap - HTB

## Target
10.129.54.196

## Open Ports
21 FTP
22 SSH
80 HTTP

## Vulnerability
IDOR en /data/[id]

## Exploitation
Se accedió a múltiples scans y se descargó un PCAP con credenciales FTP.

## Lateral Movement
Credenciales reutilizadas en SSH.

## Privilege Escalation
/usr/bin/python3.8 con capabilities → root

## Flags
User y Root obtenidas
