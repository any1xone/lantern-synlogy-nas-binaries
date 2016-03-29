# Lantern - Synology NAS DS212j binanries
You can get my building here.

## How to 

## Install
* scp lantern_linux_arm-syno to your NAS, or using File Station to upload it
* make sure it's executable
```sh
chmod a+x lantern_linux_arm-syno
```

### Running it in background
```sh
./lantern_linux_arm-syno -addr 0.0.0.0:8787 >/dev/null 2>&1 &
```

### Using it as your LAN proxy
```sh
export http_proxy=http://<your NAS IP>:8787
export https_proxy=https://<your NAS IP>:8787
```
e.g. : export http_proxy=http://192.168.1.123:8787

## Download list
[2.1.2-20160329]()lantern-synology_nas_ds212j-2.1.2-20160329.tgz
