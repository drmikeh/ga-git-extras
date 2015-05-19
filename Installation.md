## Debian

```bash
$ sudo $apt_pref update
$ sudo $apt_pref install git-extras
```

## Mac

```bash
$ brew tap drmikeh/homebrew-ga-extras
$ brew install git-extras
```

## Clone / Tarball:

```bash
$ git clone https://github.com/tj/git-extras.git
$ cd git-extras
# checkout the latest tag
$ git checkout $(git describe --tags $(git rev-list --tags --max-count=1))
$ [sudo] make install
```

One-liner:

```bash
$ (cd /tmp && git clone https://github.com/tj/git-extras.git && cd git-extras && git checkout $(git describe --tags $(git rev-list --tags --max-count=1)) && sudo make install)
```
