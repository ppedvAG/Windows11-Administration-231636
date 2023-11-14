# Im Kurs verwendete commands

```cmd
ipconfig
```
```cmd
ipconfig /all
```
```cmd
nslookup
```
```powershell
Add-Computer -DomainName ppedv.test -DomainCredential ppedv\Administrator -NewName Client1
```

```powershell
Rename-Computer -NewName Client1 -DomainCredential ppedv\Administrator
```
```cmd
ipconfig /flushdns
```
```cmd
ipconfig /displaydns
```
```powershell
Resolve-DnsName -Name Server1
```
```powershell
Get-DnsClientCache
```
```powershell
Clear-DnsClientCache
```
---
```cmd
ping 192.168.10.1
```
```powershell
Test-Connection -ComputerName 192.168.10.1
```
```powershell
Test-NetConnection -ComputerName 192.168.10.1 -Port 53
```
|Port | Dienst |
| --- | --- | 
| 21 | FTP |
| 22 | SSH |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |
| 445 | SMB |
| 3389 | RDP |