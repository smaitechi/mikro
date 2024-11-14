# Install-MikroTik
Easy way for install Mikrotik’s Cloud Hosted Router on any Cloud VM

## Prerequisites

```bash
  1:
  VPS with VNC access (Preferably Ubuntu > 20.04)
  2:
  This network information is required:
  IP Address - Net Mask - IP Gateway
  3:
  In some cases you need to disable the Virtio driver!
```

For MikroTik 7.16.1

```bash
  bash -c "$(curl -L https://raw.githubusercontent.com/ipcloudflaretamiz/mikro/main/mik78.sh)"
```
