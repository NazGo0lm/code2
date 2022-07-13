git remote add origin https://wiki.termux.com
git branch -M main 
git push -u origin main
Welcome to Termux!

Wiki:            https://wiki.termux.com
Community forum: https://termux.com/community
Gitter chat:     https://gitter.im/termux/termux
IRC channel:     #termux on freenode

Working with packages:

 * Search packages:   pkg search <query>
 * Install a package: pkg install <package>
 * Upgrade packages:  pkg upgrade

Subscribing to additional repositories:

 * Root:     pkg install root-repo
 * Unstable: pkg install unstable-repo
 * X11:      pkg install x11-repo

Report issues at https://termux.com/issues

$ minux-setup-storage
minux-setup-storage: command not found
$ apt update $$ apt update -y-
E: Command line option '-' [from -y-] is not understood in combination with the other options.
$ apt update $$ apt upgrade -y
E: The update command takes no arguments
$ apt update $$ apt upgrade
E: The update command takes no arguments
$ apt undate && apt upgrade
E: Invalid operation undate
$ apt update && apt upgrare
Ign:1 https://dl.bintray.com/grimler/game-packages-24 games InRelease
Ign:2 https://dl.bintray.com/grimler/science-packages-24 science InRelease
Err:3 https://dl.bintray.com/grimler/game-packages-24 games Release
  OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to dl.bintray.com:443
Err:4 https://dl.bintray.com/grimler/science-packages-24 science Release
  OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to dl.bintray.com:443
Get:5 https://packages.termux.dev/apt/termux-main stable InRelease [14.0 kB]
Get:6 https://packages.termux.dev/apt/termux-main stable/main aarch64 Packages [429 kB]
Reading package lists... Done
E: The repository 'https://dl.bintray.com/grimler/game-packages-24 games Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
E: The repository 'https://dl.bintray.com/grimler/science-packages-24 science Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
$ apt install git
Reading package lists... Done
Building dependency tree... Done
The following additional packages will be installed:
  pcre2
The following NEW packages will be installed:
  git pcre2
0 upgraded, 2 newly installed, 0 to remove and 50 not upgraded.
Need to get 4036 kB of archives.
After this operation, 19.9 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 https://packages.termux.dev/apt/termux-main stable/main aarch64 pcre2 aarch64 10.40 [840 kB]
Get:2 https://packages.termux.dev/apt/termux-main stable/main aarch64 git aarch64 2.37.0 [3196 kB]
Fetched 4036 kB in 5s (676 kB/s)
Selecting previously unselected package pcre2.
(Reading database ... 3457 files and directories currently installed.)
Preparing to unpack .../pcre2_10.40_aarch64.deb ...
Unpacking pcre2 (10.40) ...
Selecting previously unselected package git.
Preparing to unpack .../git_2.37.0_aarch64.deb ...
Unpacking git (2.37.0) ...
Setting up pcre2 (10.40) ...
Setting up git (2.37.0) ...
$
$
!
./
:
[
[[
]]
addpart
alias
am
apt
apt-cache
apt-config
apt-get
apt-key
apt-mark
arp
awk
b2sum
base32
base64
basename
basenc
bash
bg
bind
blkdiscard
blkid
blkzone
blockdev
break
builtin
bunzip2
bzcat
bzcmp
$
$
$ mkdir intro-to-github
$
$ mkdir intro-to-github
mkdir: cannot create directory ‘intro-to-github’: File exists
$ cd intro-to-github
$ cd intro-to-github
bash: cd: intro-to-github: No such file or directory
$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /data/data/com.termux/files/home/intro-to-github/.git/
$ $ touch README.md
No command $ found, did you mean:
 Command [ in package coreutils
 Command k in package kona
 Command o in package o
 Command o in package o-editor
 Command v in package vlang from the unstable-repo repository
$
$ starting with
No command starting found, did you mean:
 Command strings in package binutils
$
$ $ git status
No command $ found, did you mean:
 Command [ in package coreutils
 Command k in package kona
 Command o in package o
 Command o in package o-editor
 Command v in package vlang from the unstable-repo repository
$ touch README.md
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
$ intro-to-github
intro-to-github: command not found
$ ~/Documents/intro-to-github *main>
bash: syntax error near unexpected token `newline'
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
$ ~/Documents/intro-to-github *main >
bash: syntax error near unexpected token `newline'
$ git config advice.addEmptyPathspec false
$ ~/Documents/intro-to-github main* >
bash: syntax error near unexpected token `newline'
$ intro-to-github
intro-to-github: command not found
$ git add
Nothing specified, nothing added.
$ git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'u0_a318@localhost.(none)')
$ git add README.md
$ git add README.md
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

$ git commit -m "Added a readme file"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'u0_a318@localhost.(none)')
$ connect the project
No command connect found, did you mean:
 Command cronnext in package cronie
 Command convert in package imagemagick
 Command context in package texlive-bin
$ remote github repo
No command remote found, did you mean:
 Command bmore in package bvi
 Command bzmore in package bzip2
 Command lpmove in package cups from the unstable-repo repository
 Command zmore in package gzip
 Command rjoe in package joe
 Command rjoe in package jupp
 Command mmove in package mtools
 Command reset in package ncurses
 Command route in package net-tools
 Command refile in package nmh from the unstable-repo repository
 Command rclone in package rclone
 Command rem in package remind
 Command tmate in package tmate
 Command more in package util-linux
 Command lzmore in package xz-utils
$ remote github repo
No command remote found, did you mean:
 Command bmore in package bvi
 Command bzmore in package bzip2
 Command lpmove in package cups from the unstable-repo repository
 Command zmore in package gzip
 Command rjoe in package joe
 Command rjoe in package jupp
 Command mmove in package mtools
 Command reset in package ncurses
 Command route in package net-tools
 Command refile in package nmh from the unstable-repo repository
 Command rclone in package rclone
 Command rem in package remind
 Command tmate in package tmate
 Command more in package util-linux
 Command lzmore in package xz-utils
$ get remote and origin
No command get found, did you mean:
 Command gbt in package gbt
 Command geth in package geth
 Command git in package git
 Command gem in package ruby
 Command net in package samba from the unstable-repo repository
 Command gst in package smalltalk from the unstable-repo repository
 Command uget in package uget from the x11-repo repository
 Command wget in package wget
$ git remote and origin
error: Unknown subcommand: and
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

$
