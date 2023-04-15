# nextcloud-smb

quick fix for me needing smbclient for my hosted nextcloud instance, so i can add my NAS shares to it.  
Link to original Repo -> https://github.com/nextcloud/docker

## docker image
```bash
$ docker pull ghcr.io/bym0/nextcloud-smb:latest
```


## packages
following packages are installed onto the nextcloud:latest base image
- procps
- smbclient

## schedule
this image gets automatically updated every night at 0 UTC
