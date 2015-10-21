# GitUp

The shell script that makes `git` easier.

## Dependencies

As GitUp is a very simple script, it depends on only two packages:

- A `bash` compatible command-line interpreter (as `zsh`, `dash` or `fish`).
- `git`

## Installation

Run `./INSTALLER` script as root user (or maybe using `sudo`).
You can use `gitup` if is not installed.

## About Debian/Ubuntu compatibility

**Debian** and **Ubuntu** distributions use patched version of `coreutils` packages (which contains all the commands used by the script), that avoids the 'prompt coloration'.
Thus, is a problem with this, 'cause the prompt coloration is used a lot on `gitup`, the command-line will print this:

\e[1mReal Name: [\0m

instead of this:

**Real name:**

So, I'm working on a solution for this problem? Obviously yes! :smile:

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

If you want to use GitUp with another git-based solution than GitHub, just replace the line `GIT_WEB="https://github.com/"` whit the .

## TO-DO

- [x] Make this script available for other `git` solutions (GitLab and such).
- [ ] Add more commands.
- [ ] Make packages for some Linux and BSD distros.

## License

GitUp is distributed under the BSD 3-Clause license, for further information see [LICENSE](https://github.com/feskyde/gitup/blob/master/LICENSE) file.
