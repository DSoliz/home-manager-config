# home-manager-config


multi-user installation

```bash
sh <(curl -L https://nixos.org/nix/install) --daemon
```

start a shell with home-manager and git

```bash
nix-shell -p home-manager git
```

clone the repo and install packages

```bash
git clone https://github.com/DSoliz/home-manager-config.git ~/.config/home-manager

home-manager switch -b backup
```

