# Fedora

## Summary
- [git](https://github.com/jeanleonino/linux-checklist/blob/master/fedora.md#git)
- [RPM Fusion repositories](https://github.com/jeanleonino/linux-checklist/blob/master/fedora.md#rpm-fusion-repositories)
- [Gnome Tweak Tool](https://github.com/jeanleonino/linux-checklist/blob/master/fedora.md#gnome-tweak-tool)
- [Fedy](https://github.com/jeanleonino/linux-checklist/blob/master/fedora.md#fedy)
- [Gnome Shell Extensions](https://github.com/jeanleonino/linux-checklist/blob/master/fedora.md#gnome-shell-extensions)

### Ensure system is up-to-date
```sudo dnf update```

### git
```zsh
sudo dnf install git
git config --global color.ui true
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR@EMAIL.com"
git config --global push.default simple
git config --global credential.helper 'cache --timeout=3600' # desired cache timeout in seconds
git config --global core.editor vim # pick your favorite editor
```

### RPM Fusion repositories
1. Go to http://rpmfusion.org/Configuration
2. Download free + nonfree repos for matching Fedora version number
3. Click on them, and click install when it opens "Software" application

### Gnome Tweak Tool
```sudo dnf install gnome-tweak-tool```

### Fedy
```bash -c 'su -c "curl http://folkswithhats.org/fedy-installer -o fedy-installer && chmod +x fedy-installer && ./fedy-installer"'```

### Gnome Shell Extensions
1. Go to https://extensions.gnome.org/ (IN FIREFOX!)
2. If the prompt to enable "Gnome Shell Integration" extension shows up, hit "always allow"
3. Install whatever extensions you like

Recommended:
* [Battery Percentage Indicator](https://extensions.gnome.org/extension/23/battery-percentage-indicator/)
* [Hide App Icon](https://extensions.gnome.org/extension/810/hide-app-icon/)
* [Impatience](https://extensions.gnome.org/extension/277/impatience/)
* [Media Player Indicator](https://extensions.gnome.org/extension/55/media-player-indicator/)
* [Panel OSD](https://extensions.gnome.org/extension/708/panel-osd/)

