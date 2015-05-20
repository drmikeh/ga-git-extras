## Mac

```bash
$ brew tap drmikeh/homebrew-ga-extras
$ brew install ga-git-extras
```

## Debian

```bash
$ sudo $apt_pref update
$ sudo $apt_pref install ga-git-extras
```

## Clone / Tarball:

```bash
$ git clone https://github.com/drmikeh/ga-git-extras.git
$ cd ga-git-extras
# checkout the latest tag
$ git checkout $(git describe --tags $(git rev-list --tags --max-count=1))
$ [sudo] make install
```

One-liner:

```bash
$ (cd /tmp && git clone https://github.com/drmikeh/ga-git-extras.git && cd ga-git-extras && git checkout $(git describe --tags $(git rev-list --tags --max-count=1)) && sudo make install)
```
