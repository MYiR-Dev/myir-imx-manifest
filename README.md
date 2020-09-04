# MYiR i.MX8M manifest

## i.MX8M XML:
```
myir-i.mx8m-5.4.3-2.0.0.xml
```

# i.MX8M-5.4

## repo init and get myir-i.mx8m-5.4.3-2.0.0.xml:
```
export REPO_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/'
repo init -u https://github.com/MYiR-Dev/myir-imx-manifest.git --no-clone-bundle --depth=1 -m myir-i.mx8m-5.4.3-2.0.0.xml -b i.MX8M-5.4-zeus 
repo sync
```
