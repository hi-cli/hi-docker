# hi-docker: docker installation script

## Installation guide

### Install [hi-cli](https://github.com/hi-cli/hi-cli)

### Install hi-docker package

```bash
hi install docker
```

### Install docker

```bash
hi docker install all new storage=/dev/sdb
```

Parameters:

| Parameter | Default | Description |
|:--|:--|:--|
|all||reinstall all|
|new||new installation|
|storage|/dev/sdb|docker storage destination|
|percentage|98|percentage of storage being used, 98 means 98% of storage is used|
|partition|1|disk partition number, e.g. /dev/sdb1|