# GitUp

The shell script that makes `git` easier.

## Dependencies:

As GitUp is a very simple script, it depends on only two packages:

- A `bash` compatible command-line interpreter (as `zsh`, `dash` or `fish`).
- `git`

## Installation:

Run `./INSTALLER` script as root user (or maybe using `sudo`).
You can use `gitup` if is not installed.

## Commands included:

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

## TO-DO:

- [x] Add more commands.
- [x] Some "eyecandy".
- [ ] CLI (`gitup-cli`).
- [ ] Fixes on Debian.
- [ ] Make this script available for other `git` solutions (GitLab and such).
- [ ] Make packages for other distros.

## Releases:

### Upcoming:

- [0.4-1 "Flute"](www.youtube.com/watch?v=oHg5SJYRHA0 "Soon, my dear son, soon...")

### Lastest:

- [0.3-1 "Euphonium"](https://github.com/feskyde/gitup/releases/tag/v0.3-1 "Big changes are here!")
  - Changes:
    - Rewrite.
    - Added a lot of new options.
    - Added a brand new installer.
    - Change of license.
  - [Cleanups](https://github.com/feskyde/gitup/releases/tag/v0.3-2)

### Old:

- [0.2 "Drums"](https://github.com/feskyde/gitup/releases/tag/v0.2 "Sorry for this")
  - Changes:
    - Added option for fetching pull requests.
    - Change the usage of functions to simple parenthesis.
    - Moved `about` and `help` to functions file.

- [0.1 "Castanets"](https://github.com/feskyde/gitup/releases/tag/v0.1 "First release!")
  - Changes:
    - **Bolded** input messages and script output.
    - Usage of functions.
    - Rewrite the original GitUp commands.
  - And a [bugfix](https://github.com/feskyde/gitup/releases/tag/v0.1.1).

## Collaborations:

- @drpkg (use of `case`)

## License:

GitUp is distributed under the BSD 3-Clause license, for further information see [LICENSE](https://github.com/feskyde/gitup/blob/master/LICENSE) file.