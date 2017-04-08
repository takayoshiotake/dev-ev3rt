# dev-ev3rt

This is an ansible-playbook for setup *ev3rt* development environment. The development environment is installed in the directory of this file.

## References

- TOPPERS/EV3RT,  http://dev.toppers.jp/trac_user/ev3pf/wiki/WhatsEV3RT

## Dependencies

- http://www.toppers.jp/download.cgi/ev3rt-beta6-3-release.zip
- http://toppers.jp/download.cgi/cfg-osx-static-1_9_5.tar.gz
- http://dev.toppers.jp/trac_user/ev3pf/attachment/wiki/DevEnvMac/mkimage
- https://launchpad.net/gcc-arm-embedded/5.0/5-2016-q3-update/+download/gcc-arm-none-eabi-5_4-2016q3-20160926-mac.tar.bz2

## Requirement

- ansible: 2.2.1.0


## Setup: *ev3rt* development environment

```
$ pwd
dev-ev3rt
$ source install_devenv.sh
[...]
```

## Demo: make a sample app

```
$ pwd
dev-ev3rt
$ source ./export_path.sh
$ cd devenv/ev3rt-beta6-3-release/hrp2/sdk/workspace
$ make app=helloe
[...]
  LD      app
```
