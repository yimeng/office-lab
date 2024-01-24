# Linux
```
export CF_API_EMAIL=your-cloudflare-email
export CF_API_KEY=xxxxxxxxxxxxxxxx
./traefik --configFile=traefik.yaml
```

# Windows Powershell
```
$Env:CF_API_EMAIL=your-cloudflare-email
$Env:CF_API_KEY=xxxxxxxxxxxxxxxx
./traefik.exe --configFile=traefik.yaml
```

runner register in Windows
```
.\act_runner-0.2.6-windows-amd64.exe register --instance "https://git.office.yimeng.ch" --labels "windows-office:host" --name "windows-office" --no-interactive --token "xxxxxxxxxxxxxx"

.\act_runner-0.2.6-windows-amd64.exe daemon
```

