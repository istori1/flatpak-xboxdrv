# Flatpak xboxdrv

Shared modules: https://github.com/flathub/shared-modules

Todo: Building

`flatpak install flathub org.flatpak.Builder org.freedesktop.Platform//22.08 org.freedesktop.Sdk//22.08`

`flatpak run org.flatpak.Builder --repo=xboxdrv-repo --force-clean build-dir io.gitlab.xboxdrv.yml`

`flatpak remote-add --system --no-gpg-verify xboxdrv-repo xboxdrv-repo`

`flatpak install io.gitlab.xboxdrv`

Run

`sudo -i flatpak run io.gitlab.xboxdrv`
