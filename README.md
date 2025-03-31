# dmenu - A dynamic menu for X

My personal dmenu configuration.

## Wow, did I write all that myself?

Of course not! This project is based on scripts and patches from the suckless
community and can be found at
[suckless.org](https://tools.suckless.org/dmenu/patches/).

### Patches

| url | description |
| --- | --- |

### Scripts

| url | description |
| --- | --- |
| [dmenu_run_history](https://tools.suckless.org/dmenu/scripts/dmenu_run_with_command_history/dmenu_run_history) | Sort run history based on usage frequency |

## Installation

```sh
git clone git@github.com:reyniersbram/dmenu.git
cd dmenu
sudo make install
```

## Updating to the latest version of dmenu

Set up the local git configuration to have the official dmenu repository as 
a remote called upstream.

```sh
patch -p0 < gitconfig.diff
```

Then just run `git pull` to get the latest changes.

> [!NOTE]
> There is absolutely no guarantee no conflicts will come up.
