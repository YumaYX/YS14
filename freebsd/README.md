
```sh
vagrant box add generic/freebsd14 --provider libvirt
```

```sh
ifconfig | grep 172

pkg install -y git
sysrc sshd_enable=YES

uname -a
freebsd-version
```

```sh
freebsd-update upgrade -r 14.4-RELEASE
# 設定ファイル変更衝突を直して保存。
freebsd-update install

freebsd-update fetch install
freebsd-update install
```

```sh
pkg update
pkg update -f
pkg upgrade
```

- [FreeBSD - Wikipedia](https://ja.wikipedia.org/wiki/FreeBSD)
- [HashiCorp Cloud Platform](https://portal.cloud.hashicorp.com/vagrant/discover/)

---

```sh
<<<<<<< current version
                                # Working copy (updated weekly) leapfile
ntp_leapfile_sources="https://www.ietf.org/timezones/
data/leap-seconds.list"
=======
                                # Canonical place to get the leap seconds from
ntp_leapfile_sources="https://hpiers.obspm.fr/iers/bu
l/bulc/ntp/leap-seconds.list https://data.iana.org/ti
me-zones/tzdb/leap-seconds.list"
>>>>>>> 14.4-RELEASE
```

```sh
# rbenv
sudo pkg update
sudo pkg install git curl bash gmake autoconf readline libyaml libffi openssl

```

```sh
sudo dnf install ansible-core

ansible-galaxy collection install community.general
```

```sh
sudo pw group add mygroup

pw groupadd -q -n mygroup2 -g 10022

pw useradd -n myuser -u 1234 -s /bin/bash -m -G mygroup2
```

