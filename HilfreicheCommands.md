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