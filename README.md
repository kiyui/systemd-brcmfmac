# systemd-brcmfmac
Disable the `brcmfmac` on shutdown to avoid SystemD timeout on stopping the `firewalld` service.

# installation
- Copy `remove-brcmfmac.service` to `/etc/systemd/system/`
- Run `systemctl enable remove-brcmfmac.service`
