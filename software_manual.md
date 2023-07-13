# :information_source: Infomation

[![hackmd-github-sync-badge](https://hackmd.io/_zTR-3VFSIiDyhH_MvUlkw/badge)](https://hackmd.io/_zTR-3VFSIiDyhH_MvUlkw)

:::info
This manual will provide guidance for CWB developers on how to effectively utilize the system's pre-built or custom-built packages.
:::

## :hammer: WGRIB2
:::success
* FX1000
```
GRIB_ROOT='/package/fx1000/wgrib2-3.1.0'
export PATH=${GRIB_ROOT}/bin:$PATH
```
* x86_64
```
$ which wgrib2
/usr/bin/wgrib2
```
:::
## :hammer: G2LIB
:::success
* FX1000
```
G2LIB_ROOT='/package/fx1000/g2lib-1.4.0_cwb'
export LD_LIBRARY_PATH=${G2LIB_ROOT}/lib:${LD_LIBRARY_PATH}
```
* x86_64
```
G2LIB_ROOT='/package/x86_64/g2lib-1.4.0'
export LD_LIBRARY_PATH=${G2LIB_ROOT}/lib:${LD_LIBRARY_PATH}
```
:::
## :hammer: G2CLIB
:::success
* FX1000
```
G2CLIB_ROOT='/package/fx1000/g2clib-1.4.0_cwb'
export LD_LIBRARY_PATH=${G2CLIB_ROOT}/lib:${LD_LIBRARY_PATH}
```
* x86_64
```
G2CLIB_ROOT='/package/x86_64/g2clib-1.4.0'
export LD_LIBRARY_PATH=${G2CLIB_ROOT}/lib:${LD_LIBRARY_PATH}
```
:::