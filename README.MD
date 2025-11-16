
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
$: repo init -u https://github.com/viyaraembedded/viyara-imx-manifest.git --no-clone-bundle --depth=1 -m viyara-i.mx6ul.xml 
$: repo sync
```
