### The flatpak build repo for Wings3D

See <www.wings3d.com> (and/or <https://github.com/dgud/wings>)

Create releases with:
 `flatpak-builder --force-clean build-dir com.wings3d.WINGS.json`

Test with:
 `flatpak-builder --run build-dir com.wings3d.WINGS.json wings`
