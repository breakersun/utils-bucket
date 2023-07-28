# utils-bucket


## Install
Please install this bucket as this:

```powershell
scoop bucket add breaker-utils https://github.com/breakersun/utils-bucket.git

scoop update
```

## Usage

```powershell
scoop install breaker-utils/bincalc
scoop install breaker-utils/gcc-arm-none-eabi@5.4.1
scoop install breaker-utils/gitversion2c
```

## Switch `arm-gcc` version

You can install 2 version `arm-gcc` at the same time:
```powershell
scoop bucket add extras
scoop install extras/gcc-arm-none-eabi // install the latest arm-gcc
scoop install breaker-utils/gcc-arm-none-eabi@5.4.1 // install my old version of arm-gcc
```

switch between 2 of them:

Reset to latest version
note : please check C:\Users\user\scoop\apps\gcc-arm-none-eabi\ to see which is the latest version number
```powershell
scoop reset gcc-arm-none-eabi@12.2.rel1
```

Reset to old version 5.4.1
```powershell
scoop reset gcc-arm-none-eabi@5.4.1
```
