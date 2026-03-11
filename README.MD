
# VIYARA i.MX6UL manifest

## i.MX6UL XML:
```
viyara-i.mx6ul-5.10.9-1.0.0.xml
```

# i.MX6UL-5.10

## repo init and get viyara-i.mx6ul-5.10.9-1.0.0.xml:
```
$: mkdir ~/bin
$: curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
$: chmod a+x ~/bin/repo
$: PATH=${PATH}:~/bin
$: mkdir yoctotutor
$: cd yoctotutor
$: repo init -u https://github.com/viyaraembedded/viyara-imx-manifest.git -b i.MX6UL-5.10-gatesgarth --no-clone-bundle --depth=1 -m viyara-i.mx6ul-5.10.9-1.0.0.xml
$: repo sync
$: DISTRO=fsl-imx-fb MACHINE=mys-6ull source sources/meta-myir/tools/myir-setup-release.sh -b build
          # ask for license press space and hold for 100% then pres "y"
$: bitbake myir-image-core
```

out put images present in 
```
build\$: ls tmp/deploy/images/mys-6ull
```
