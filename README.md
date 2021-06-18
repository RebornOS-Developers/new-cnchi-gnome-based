# new-cnchi-gnome-based
new cnchi gnome based (ISO creation)

<p align="center">
<img src="https://raw.githubusercontent.com/RebornOS-Developers/new-cnchi-gnome-based/main/Screenshot-20210618-1.png">
</p>

Process to build the ISO:

**1.** Clone this repo:
```
git clone https://github.com/RebornOS-Developers/new-cnchi-gnome-based.git && cd new-cnchi-gnome-based
```

**2.** From terminal, run:
```
sudo ./fix_permissions.sh
sudo ./build.sh -v
```

The installer ISO will be in the **out** folder (folder that will be created automatically).

This installer downloads the cnchi code from the RebornOS repository.
