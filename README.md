# GitUp

[![Join the chat at https://gitter.im/feskyde/gitup](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/feskyde/gitup?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Join the chat at https://gitter.im/feskyde/gitup](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/feskyde/gitup?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The shell script that makes `git` easier.

## Dependencies

As GitUp is a very simple script, it depends on only two packages:

- A `bash` compatible command-line interpreter (as `zsh`, `dash` or `fish`).
- `git`

## Installation

Run `./INSTALLER` script as root user (or maybe using `sudo`).
You can use `gitup` if is not installed.

## Usage

You can use large-type commands...

```sh
gitup commit
gitup global-config
gitup branch-switch
```

...or abbreviations.

```sh
gitup cm
gitup gc
gitup bs
```

Just type `gitup help` and see the magic...

## GitLab and others

If you want to use GitUp with another git-based solution than GitHub, replace the variable `GIT_WEB`.

## TO-DO

- [x] Make this script available for other `git` solutions (GitLab and such).
- [x] Fix the Debian/Ubuntu coloration problem.
- [ ] Add more commands.
- [ ] Make packages for some Linux and BSD distros.

## License

GitUp is distributed under the BSD 3-Clause license, for further information see [LICENSE](https://github.com/feskyde/gitup/blob/master/LICENSE) file.

