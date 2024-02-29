
# MYiR i.MX6UL manifest

## i.MX6UL XML:
```
myir-i.mx6ul-5.10.9-1.0.0.xml
```

# i.MX6UL-5.10

## repo init and get myir-i.mx6ul-5.10.9-1.0.0.xml:
```
export REPO_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/'
repo init -u https://github.com/MYiR-Dev/myir-imx-manifest.git --no-clone-bundle --depth=1 -m myir-i.mx6ul-5.10.9-1.0.0.xml -b i.MX6UL-5.10-gatesgarth 
repo sync
```
