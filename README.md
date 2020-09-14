# my_rvm_installer

Speed up the rvm installation for me.

## Usages

```bash
# install the rvm in my way
gpg2 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
curl -sSL http://qiniu.forqian.cn/blue_dream_tools/my_rvm_installer/rvm-installer.txt | bash -s stable
# backup
curl -sSL https://gitee.com/blue_dream_tools/my_rvm_installer/raw/master/rvm-installer.txt | bash -s stable
```

## Source Bash Scripts

### `qiniu.forqian.cn`

url: http://qiniu.forqian.cn/blue_dream_tools/my_rvm_installer/rvm-installer.txt

backup_url: https://gitee.com/blue_dream_tools/my_rvm_installer/raw/master/rvm-installer.txt

### `github.com`

https://raw.githubusercontent.com/rvm/rvm/master/binscripts/rvm-installer

## Source Tags

### `qiniu.forqian.cn`

http://qiniu.forqian.cn/blue_dream_tools/my_rvm_installer/rvm-tags.txt

### `bitbucket.org`

https://api.bitbucket.org/2.0/repositories/mpapis/rvm/refs/tags?sort=-name&pagelen=20

### `github.com`

https://api.github.com/repos/rvm/rvm/tags

## Source Releases

### `qiniu.forqian.cn`

#### template

package_url: `http://qiniu.forqian.cn/blue_dream_tools/my_rvm_installer/${_version}.tar.gz`

verfiy_pgp_url: `http://qiniu.forqian.cn/blue_dream_tools/my_rvm_installer/${_version}.tar.gz.asc`

#### example

package_url: http://qiniu.forqian.cn/blue_dream_tools/my_rvm_installer/1.29.10.tar.gz

verfiy_pgp_url: http://qiniu.forqian.cn/blue_dream_tools/my_rvm_installer/1.29.10.tar.gz.asc

### `bitbucket.org`

#### list
https://bitbucket.org/mpapis/rvm/downloads/?tab=tags
https://bitbucket.org/mpapis/rvm/downloads/?tab=downloads

#### template

package_url: `https://bitbucket.org/mpapis/rvm/get/${_version}.tar.gz`

verfiy_pgp_url: `https://bitbucket.org/mpapis/rvm/downloads/${_version}.tar.gz.asc`

#### example

package_url: https://bitbucket.org/mpapis/rvm/get/1.29.10.tar.gz

verfiy_pgp_url: https://bitbucket.org/mpapis/rvm/downloads/1.29.10.tar.gz.asc

### `github.com`

#### list
https://github.com/rvm/rvm/tags
https://github.com/rvm/rvm/releases

#### template

package_url: `https://github.com/rvm/rvm/archive/${_version}.tar.gz`

verfiy_pgp_url: `https://github.com/rvm/rvm/releases/download/${_version}/${_version}.tar.gz.asc`

#### example

package_url: https://github.com/rvm/rvm/archive/1.29.10.tar.gz

verfiy_pgp_url: https://github.com/rvm/rvm/releases/download/1.29.10/1.29.10.tar.gz.asc
