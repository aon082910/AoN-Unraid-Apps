# AoN-Unraid-Apps

Unraid Community Applications templates for my self-hosted apps. One folder per app.

| App | Template | Source | Image |
|---|---|---|---|
| **Shopping Hub** | [`Shopping-Hub/`](Shopping-Hub/shopping-hub.xml) | [aon082910/shopping-hub](https://github.com/aon082910/shopping-hub) | [`allornothing/shopping-hub`](https://hub.docker.com/r/allornothing/shopping-hub) |
| **AoNarr** | [`AoNarr/`](AoNarr/aonarr.xml) | [aon082910/AoNarr](https://github.com/aon082910/AoNarr) | [`allornothing/aonarr`](https://hub.docker.com/r/allornothing/aonarr) |
| **MC-Mod-Hub** | [`MC-Mod-Hub/`](MC-Mod-Hub/mc-mod-hub.xml) | [aon082910/mc-mod-hub](https://github.com/aon082910/mc-mod-hub) | [`allornothing/mc-mod-hub`](https://hub.docker.com/r/allornothing/mc-mod-hub) |
| **Build-Hub** | [`Build-Hub/`](Build-Hub/build-hub.xml) | [aon082910/build-hub](https://github.com/aon082910/build-hub) | [`allornothing/build-hub`](https://hub.docker.com/r/allornothing/build-hub) |
| **AppForge Hub** | [`AppForge-Hub/`](AppForge-Hub/appforge-hub.xml) | [aon082910/appforge-hub](https://github.com/aon082910/appforge-hub) | [`allornothing/appforge-hub`](https://hub.docker.com/r/allornothing/appforge-hub) |

## Installing

Once this repository is listed in Community Applications, open the **Apps** tab on
your Unraid server and search for the app by name.

To install a template before then, pull it straight onto the server:

```bash
wget -O /boot/config/plugins/dockerMan/templates-user/my-shopping-hub.xml \
  https://raw.githubusercontent.com/aon082910/AoN-Unraid-Apps/main/Shopping-Hub/shopping-hub.xml
```

Then **Docker -> Add Container** and pick it from the template dropdown.

## Repository layout

```
ca_profile.xml          maintainer profile shown in Community Applications
icon.png                repository icon
Shopping-Hub/
  shopping-hub.xml      container template
  icon.png              app icon
  screenshots/          listing screenshots
AoNarr/
  aonarr.xml            container template
  icon.png              app icon
MC-Mod-Hub/
  mc-mod-hub.xml        container template
  icon.png              app icon
Build-Hub/
  build-hub.xml         container template
  icon.png              app icon
AppForge-Hub/
  appforge-hub.xml      container template
  icon.png              app icon
```

`ca_profile.xml` lives at the root and describes the whole repository, not any one
app -- Community Applications expects exactly one per repository.

## License

MIT - see [LICENSE](LICENSE). Each app is licensed separately in its own repository.
