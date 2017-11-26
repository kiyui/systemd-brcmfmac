# systemd-brcmfmac
Disable the `brcmfmac` module on shutdown to avoid SystemD timeout on stopping the `firewalld` service.
- [Associated bug report](https://bugzilla.redhat.com/show_bug.cgi?id=1397274)

# installation
- Copy `remove-brcmfmac.service` to `/etc/systemd/system/`
- Run `systemctl enable remove-brcmfmac.service`

## arch-linux
- Available as [AUR Package](https://aur.archlinux.org/packages/systemd-brcmfmac-git/)
