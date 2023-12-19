# Local Manifests #
Just grab the manifest and sync to get device sources
### Twelve-Prebuilt ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/yogurt-devs/local_manifests/main/twelve-prebuilt.xml --create-dirs

```
### Thirteen-Prebuilt ###

Required patches for IMS: https://gerrit.pixelexperience.org/q/topic:%22mediatek-ims%22+(status:open%20OR%20status:merged)

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/yogurt-devs/local_manifests/main/thirteen-prebuilt.xml --create-dirs

```
### Thirteen ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/yogurt-devs/local_manifests/main/thirteen.xml --create-dirs

```

### Fourteen ###
```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/yogurt-devs/local_manifests/main/fourteen.xml --create-dirs

``` 

```bash
# Sync
repo sync -j$(nproc --all) --force-sync
```
