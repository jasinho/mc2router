# Meshcentral 2 router

A node webkit-based application to ease certain application tunneling via [Meshcentral 2](https://github.com/Ylianst/MeshCentral). 
## Dependencies
```
npm install ws request socksv5 https-proxy-agent
```

## Configuration

```javascript
{
    "mesh_url": "https://alt.meshcentral.com/",    
	"mesh_username": "usename",
	"mesh_password": "password",
	"ssh": "C:\\Program Files (x86)\\PuTTY\\putty.exe",
	"sftp": "C:\\Program Files\\FileZilla FTP Client\\filezilla.exe",
	"rdp": "C:\\Windows\\System32\\mstsc.exe",
	"use_proxy": false,
	"proxy_type": "socks",
	"proxy_host": "proxy.company.com",
	"proxy_port": "1080"

}

```
## How to run
```
> nw
```