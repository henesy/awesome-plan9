# Awesome Plan9

A curated list of awesome Plan9 (and sometimes 9p) libraries and software.

> Generally when referring to "Plan9" this document really means 9front.

9p.io links are accessible over 9p as well. On 9front you can run `9fs 9pio` as a shortcut.

Many of the applications listed here are available under the 9front [ports tree](https://code.9front.org/hg/ports).

### Contributing

Please do.

PR's welcome for all edits or new projects.

### Contents

- [Awesome Plan9](#awesome-plan9)
  - [Resources](#resources)
  - [Applications](#applications)
  - [Languages](#languages)
  - [Libraries](#libraries)
  - [Forks](#forks)
  - [Influenced by Plan9](#influenced-by-plan9)

## Resources

* [Modding Rio](https://wiki.xxiivv.com/site/rio.html) - Tutorials on how to add a wallpaper and change colors.
* [Plan 9 GUI Examples](https://wiki.xxiivv.com/site/plan9_c.html) - Tutorials to learn about GUI development on Plan9.

### Blogs

* []() -

### Sites

* [cat-v](http://cat-v.org)
* [9p.mom/f](http://9p.mom/f) - Files for hacking together bootable things without easy access to a 9front system

### Papers

* [Plan 9 From Bell Labs](https://9p.io/sys/doc/9.pdf) - Overview of the Plan9 system itself
* [Security in Plan 9](https://9p.io/sys/doc/auth.pdf) - Overview of the security architecture of Plan9


### Manuals

* [aiju's manuals](http://man.aiju.de/)
* [cat-v's manuals](http://man.cat-v.org/9front/)

### Third Edition

* [Plan9 3e FAQ](http://www.fywss.com/plan9/plan9v3faq.html) - FAQ for 3rd edition release

### Second Edition

* [Plan9 2e FAQ](http://www.fywss.com/plan9/plan9v2faq.html) - FAQ for 2nd edition release
* [Plan9 Tips and Information](http://www.fywss.com/plan9/info/)

### First Edition

* []() -

### Talks

* [The Name Game](https://youtu.be/3d1SHOCCDn0) - Talk on Plan9 and Inferno by Charles Forsyth

## Applications

### Utilities

* [color9](https://wiki.xxiivv.com/site/plan9_color.html) - Color picker
* [disco](https://github.com/henesy/disco) - Discord client
* [fontsel](https://git.sr.ht/~ft/fontsel) - Font selector
* [git9](https://github.com/oridb/git9) - Git implementation
* [unionfs](https://github.com/okvik/unionfs) - Deep union file server
* [xmpp](https://git.sr.ht/~ft/xmpp) - XMPP client

### Editors

* [9vim](https://vmsplice.net/9vim.html) - A port of vim to Plan9

### Graphics

* [Moogle](https://wiki.xxiivv.com/site/moogle.html) - A simple 3D wireframe editor
* [whiteboardfs](https://git.sr.ht/~amavect/whiteboardfs) - A collaborative drawing file system

### Audio/music

* [mpl](https://github.com/majiru/mpl) - Music Player
* [neindaw](https://git.sr.ht/~ft/neindaw) - DAW for Plan 9
* [orca](https://git.sr.ht/~ft/orca) - Live Programming Environment
* [treason](https://git.sr.ht/~ft/treason) - Video player
* [ytfs](https://github.com/majiru/ytfs) - File system for playing youtube audio
* [zuke](https://git.sr.ht/~ft/zuke) - Music player

## Languages

*Languages which are known to be buildable/operational on Plan9.*

* [fe](https://git.sr.ht/~ft/fe) - A tiny, embeddable Lisp-like language
* [Go](https://golang.org/) - The Go programming language
* [Idris 2](https://git.sr.ht/~ft/idris2) - A dependently typed programming language
* [Lua](http://download.redis.io/releases/redis-3.0.1.tar.gz) - Lua from Redis
* [Myrddin](https://bitbucket.org/oridb/mc) - Systems language by Ori Bernstein
* [Ocaml](http://caml.inria.fr/pub/distrib/ocaml-4.07/ocaml-4.07.1.tar.gz) - Ocaml
* [Scheme 9](http://t3x.org/s9fes/s9fes-20180823.tgz) - Scheme 9 from Empty Space
* [Squeak](https://github.com/henesy/squeak) - Squeak/Smalltalk from de0u/squeak
* [Tcl](https://9p.io/sources/contrib/fgb/root/sys/src/cmd/tcl/) - Tcl port by fgb
* [TinyScheme](https://download.sourceforge.net/tinyscheme/tinyscheme-1.41.tar.gz) - TinyScheme

## Libraries

* [libtags](https://git.sr.ht/~ft/libtags) - A cross-platform library for reading tags
* [libtheme](https://github.com/Plan9-Archive/libtheme) - A theming library for the plan 9 graphics system
* [microui](https://git.sr.ht/~ft/microui) - Tiny immediate-mode UI library

## Forks

* [9ants](http://9gridchan.org/) - Mycroftiv's fork (of 9front) featuring a modified kernel and custom namespace control tooling
* [9atom (deprecated?)](http://mirror.postnix.pw/9atom/INSTALLERS/) - Erik Quanstrom's fork (mirror)
* [9front](http://9front.org/) - Fork featuring new protocols, file systems, and greatly expanded hardware support
* [9legacy](http://9legacy.org/) - Fork which continues maintaining a Bell Labs-like source base
  * [9pi](https://9p.io/sources/contrib/miller/) - Port of 9legacy to the Raspberry Pi
* [Jehanne](http://jehanne.io/) - Giacomo Tesio's fork

## Influenced by Plan9

### Editors

* [acme2k](https://github.com/karahobny/acme2k) - An acme-inspired geared towards easy configurability
* [editor](https://github.com/jmigpin/editor) - An acme-inspired, full-featured, editor in Go
* [edwood](https://github.com/rjkroege/edwood) - An acme-inspired editor in Go
* [sam](https://github.com/deadpixi/sam) - A fork of the unix sam(1) and samterm(1) with extensive extensibility

### Utilities

* [mk](https://github.com/dcjones/mk) - A rewrite and partial re-imagining of mk(1) in Go

### Libraries

* [c9](https://git.sr.ht/~ft/c9) - A low-level 9p client and server implementation

### Kernels

* [plan_rust](https://github.com/TheEnbyperor/plan_rust) - Plan9-influenced kernel in Rust

### Operating Systems

* [Akaros](http://www.akaros.org) - Support for parallel and high-performance applications and to scale to a large number of cores
* [Inferno](http://www.vitanuova.com/inferno/) - Register-oriented virtual machine operating system which can run natively and hosted, leverages 9p heavily as "styx"
* [Interim](https://github.com/mntmn/interim) - Minimal operating system featuring a lisp environment (everything is a file is a symbol)
* [Redox](https://www.redox-os.org/) - A Unix-like operating system written in Rust
