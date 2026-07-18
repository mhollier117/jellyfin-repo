# Jellyfin Plugin Repository

Plugin repository for [jellyfin-plugin-jfremote](https://github.com/mhollier117/jellyfin-plugin-jfremote)
and [jellyfin-plugin-fillerskip](https://github.com/mhollier117/jellyfin-plugin-fillerskip).

## Add to Jellyfin

Dashboard → Plugins → Repositories → **+**

```
https://raw.githubusercontent.com/mhollier117/jellyfin-repo/main/manifest.json
```

Builds are provided for Jellyfin 12.0.x and 10.11.x — the catalog picks the right
one for your server automatically.

## Third-party 12.0 builds

This repository also carries unofficial **Jellyfin 12.0** builds of two dependencies
that have no upstream 12.0 releases yet: [JavaScript Injector](https://github.com/n00bcodr/Jellyfin-JavaScript-Injector)
and [File Transformation](https://github.com/IAmParadox27/jellyfin-plugin-file-transformation),
compiled from their upstream sources. They are listed for Jellyfin 12.0 only - on 10.x,
install them from the authors' own repositories.
