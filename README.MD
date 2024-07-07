# Private HomeServer setup

This PHS setup is based on the podman quadlet feature. It includes the followiing service:
* traefik
* tgtg-bot
* ipknower
* bitwarden

For the general setup please execute the following commands
```bash
git clone git@github.com:HannesHil/homeserver.git
cd homeserver
ln -s $PWD/quadlet/ $HOME/.config/containers/systemd
ln -s $PWD/systemd/podman-custom.service $HOME/.config/systemd/user/podman-custom.s
ervice
ln -s $PWD/systemd/podman-custom.socket $HOME/.config/systemd/user/podman-custom.so
cket
```

