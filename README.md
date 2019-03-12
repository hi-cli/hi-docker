# hi-docker: docker installation script

## Installation guide

### Install [hi-cli](https://github.com/hi-cli/hi-cli)

### Install hi-docker package

```bash
hi install docker
```

### Install docker

```bash
hi docker install ce all new storage=/dev/sdb registry=[registry.com]
```

Parameters:

| Parameter  | Default  | Description                                                       |
|:-----------|:---------|:------------------------------------------------------------------|
| ce         | default  | ce engine default                                                 |
| all        |          | reinstall all                                                     |
| new        |          | new installation                                                  |
| storage    | /dev/sdb | docker storage destination                                        |
| percentage | 98       | percentage of storage being used, 98 means 98% of storage is used |
| partition  | 1        | disk partition number, e.g. /dev/sdb1                             |
| registry   |          | local insecure registry, e.g. harbor.company.com                  |