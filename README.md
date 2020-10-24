# Brew php version switcher for OSX

If you're on OSX with PHP installed via Brew, you may be looking for an easy way to switch between PHP versions.

## Installation:
```
curl https://raw.githubusercontent.com/danielebarbaro/sphp-osx/main/sphp > /usr/local/bin/sphp
chmod +x /usr/local/bin/sphp
```

Add `/usr/local/bin` to your `$PATH`. If you use the Bash shell, you can do this by running this command:
```
echo 'export PATH="/usr/local/bin:$PATH"' >> $HOME/.bashrc
```

## Usage:

```sh
sphp 7.4
```

This version is heavily inspired from [sgotre/sphp-osx](https://github.com/sgotre/sphp-osx)
