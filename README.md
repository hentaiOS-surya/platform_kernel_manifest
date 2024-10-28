## Repo Init ##
```bash
repo init -u https://github.com/hentaiOS-surya/platform_kernel_manifest.git -b master
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
