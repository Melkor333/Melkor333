I love to tinker with possible solutions to stupid problems.

# Ugly shell!

Bash stayed in the 90ies. People believe shell has to be like that. It's "only" glue. Noone uses shell. That's stupid!

## Solution: [Oils](https://oilshell.org)

The only bash-compatible shell. Heavy focus on fixing bash problems instead of bringing a new language:
- Posix compliant: Can actually replace your /bin/sh (other than nushell, fish, etc.)
- Native json parser/output
- Partially upgrade your shell script by enabling flags
  - static parsing (as much as possible) to find issues beforehand

## Projects

- [oily-nixpkgs](https://github.com/Melkor333/oily-nixpkgs) - Trying to replace bash with oils in the Nixpkgs stdenv
- [oily-gentoo](https://github.com/Melkor333/oily-gentoo) - Try to replace bash with oils in gentoo
- [a bit of adventOfCode](https://github.com/Melkor333/adventofcode/blob/main/2023/README.md) in YSH
- [web_shell fork](https://github.com/Melkor333/web_shell) - playing around with [headless shell](https://www.oilshell.org/release/0.21.0/doc/headless.html). Try to implement modular plugin features. Because the terminal sucks!
- [minimal geoiplist generator](https://github.com/Melkor333/diy-geoiplist) - written in Ysh
- [timed interface](https://github.com/Melkor333/timed-stuff) - trying to expose my time tracking in ysh
  - Also: oauth in shell

# Repetitive Server Configurations

How often has every sysadmin set up a linux machine with a simple apache/nginx and php-fpm/gunicorn, etc. It's so repetitive. There are "solutions" like Ansible (my dayjob), Puppet or Salt. But they are all an afterthought and therefore come drawbacks like having to keep checking the state. This is stupid!

## Solution

[NixOS](https://nixos.org/) has the configuration definition built right into it's package manager. Nix (the pkg manager/build system) is hyped for it's flexibility, but I wish to see more NixOS for servers.

## Projects

- [oily-nixpkgs](https://github.com/Melkor333/oily-nixpkgs) - Trying to replace bash with oils in the Nixpkgs stdenv
- [nix-meddle](https://github.com/Melkor333/nix-meddle) - Meddle around in `/nix` and test hotfixes like on legacy Distros. But with the safety of bind-mount and unshare.
- [nix-merge](https://github.com/Melkor333/nix-merge) - Move your non-declarative `nix-env` packages to a configuration file.
- [nixos-boot](https://github.com/Melkor333/nixos-boot) - Fancy Plymouth themes
- [nix-shells](https://github.com/Melkor333/nix-shells) I (used to) use

# Other fun stuff

- [chess2brain](https://github.com/Melkor333/chess2brain) - The source for https://chess2brain.com
- Get a part of [mattermost history](https://github.com/Melkor333/mattermost-history) based on a time range. Because Sometimes I want to know what happened in a specific time range.
- Don't tell anyone I've done some [bad things](https://github.com/Melkor333/activedirectory_usercreator) as well.
