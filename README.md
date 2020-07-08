# Enable EPEL Repository for CentOS 7 installed on Raspberry Pi 4
This will enable the EPEL repository on your Raspberry Pi 4

```shell
nano /etc/yum.repos.d/epel.repo
```

##### Copy/paste this:

```shell
[epel]
name=Epel rebuild for armhfp
baseurl=https://armv7.dev.centos.org/repodir/epel-pass-1/
enabled=1
gpgcheck=0
```

##### Save the above and run:
```shell
yum install epel-release -y
```
