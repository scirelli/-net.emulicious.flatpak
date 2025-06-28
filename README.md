# Flatpak wrapper for Emulicious
Threw together a quick flatpak for Emulicious

Build
```
flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install builddir net.emulicious.java.emulicious.yml
```

Run
```
flatpak run  net.emulicious.java.emulicious
```
