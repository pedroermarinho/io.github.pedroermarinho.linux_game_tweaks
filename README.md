# io.github.pedroermarinho.linux_game_tweaks

## [Build Project](https://github.com/pedroermarinho/linux_game_tweaks?tab=readme-ov-file#distribui%C3%A7%C3%A3o-do-aplicativo)

```bash
cd linux_game_tweaks
flutter_distributor release --name build
```

## Build flap

```bash
flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install builddir io.github.pedroermarinho.linux_game_tweaks.yml
```
