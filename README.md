# AoN-Unraid-Apps

Unraid Community Applications templates for my self-hosted apps, one folder per app.

| App | Source | Image |
|---|---|---|
| **Shopping Hub** | [shopping-hub](https://github.com/aon082910/shopping-hub) | [`allornothing/shopping-hub`](https://hub.docker.com/r/allornothing/shopping-hub) |
| **AoNarr** | [AoNarr](https://github.com/aon082910/AoNarr) | [`allornothing/aonarr`](https://hub.docker.com/r/allornothing/aonarr) |
| **MC-Mod-Hub** | [mc-mod-hub](https://github.com/aon082910/mc-mod-hub) | [`allornothing/mc-mod-hub`](https://hub.docker.com/r/allornothing/mc-mod-hub) |
| **Build-Hub** | [build-hub](https://github.com/aon082910/build-hub) | [`allornothing/build-hub`](https://hub.docker.com/r/allornothing/build-hub) |
| **AppForge Hub** | [appforge-hub](https://github.com/aon082910/appforge-hub) | [`allornothing/appforge-hub`](https://hub.docker.com/r/allornothing/appforge-hub) |
| **Model Hub** | [model-hub](https://github.com/aon082910/model-hub) | [`allornothing/model-hub`](https://hub.docker.com/r/allornothing/model-hub) |
| **Repair-Hub** | [repair-hub](https://github.com/aon082910/repair-hub) | [`allornothing/repair-hub`](https://hub.docker.com/r/allornothing/repair-hub) |
| **SOP-Hub** | [sop-hub](https://github.com/aon082910/sop-hub) | [`allornothing/sop-hub`](https://hub.docker.com/r/allornothing/sop-hub) |
| **Channel Hub** | [channel-hub](https://github.com/aon082910/channel-hub) | [`allornothing/channel-hub`](https://hub.docker.com/r/allornothing/channel-hub) |
| **Card-Hub** | [card-hub](https://github.com/aon082910/card-hub) | [`allornothing/card-hub`](https://hub.docker.com/r/allornothing/card-hub) |
| **Ghost-Hub** | [ghost-hub](https://github.com/aon082910/ghost-hub) | [`allornothing/ghost-hub`](https://hub.docker.com/r/allornothing/ghost-hub) |
| **Throttlearr** | [throttlearr](https://github.com/aon082910/throttlearr) | [`allornothing/throttlearr`](https://hub.docker.com/r/allornothing/throttlearr) |
| **Household-Hub** | [household-hub](https://github.com/aon082910/household-hub) | [`allornothing/household-hub`](https://hub.docker.com/r/allornothing/household-hub) |
| **Skill-Harvester** | (private source, template only) | [`allornothing/skill-harvester`](https://hub.docker.com/r/allornothing/skill-harvester) |
| **Unraid File Manager** | (private source, template only) | [`allornothing/unraid-file-manager`](https://hub.docker.com/r/allornothing/unraid-file-manager) |
| **Backblaze-Personal** | [backblaze-personal](https://github.com/aon082910/backblaze-personal) (fork of iamfoz's) | [`allornothing/backblaze-personal`](https://hub.docker.com/r/allornothing/backblaze-personal) |
| **OmniRoute** | [OmniRoute](https://github.com/diegosouzapw/OmniRoute) (third-party) | [`diegosouzapw/omniroute`](https://hub.docker.com/r/diegosouzapw/omniroute) |

## Installing

Once this repository is listed in Community Applications, search for the app by name in the Apps tab.

Until then, add `https://github.com/aon082910/AoN-Unraid-Apps` under Apps → Settings → Template Repositories, or pull a single template onto your server:

```bash
wget -O /boot/config/plugins/dockerMan/templates-user/my-shopping-hub.xml \
  https://raw.githubusercontent.com/aon082910/AoN-Unraid-Apps/main/Shopping-Hub/shopping-hub.xml
```

Then Docker → Add Container and pick it from the template dropdown.

## License

MIT, see [LICENSE](LICENSE). Each app is licensed in its own repository.
