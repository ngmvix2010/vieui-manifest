# VieUI Manifest
...

## How to build
### Create work dir
```
mkdir vieui && cd vieui
```

### Repo init
```
repo init -u https://github.com/ngmvix2010/vieui-manifest.git -b main
```

### Repo sync
```
repo sync -c -j$(nproc) --force-sync --no-clone-bundle --no-tags
```
