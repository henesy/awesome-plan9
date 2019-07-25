# Awesome Plan9

A curated list of awesome Plan9 (and sometimes 9p) libraries and software.

_Note_: Generally when referring to "Plan9" this document really means 9front.

9p.io links are accessible over 9p as well. On 9front you can run `9fs 9pio` as a shortcut. 

Many of the applications listed here are available under the 9front [ports tree](https://code.9front.org/hg/ports). 

### Contributing

Please do.

PR's welcome for all edits or new projects. 

### Contents

- [Awesome Plan9](#awesome-plan9)
  - [Resources](#resources)
  - [Applications](#applications)
  - [Libraries](#libraries)
  - [Forks](#forks)
  - [Influenced by Plan9](#influenced-by-plan9)

## Resources

* []() -

### Blogs

* []() -

### Sites

* [cat-v](http://cat-v.org)

### Papers

* []() -

### Manuals

* [cat-v's manuals](http://man.cat-v.org/9front/)
* [aiju's manuals](http://man.aiju.de/)

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

* [disco](https://bitbucket.org/henesy/disco) - Discord client

### Editors

* [9vim](https://vmsplice.net/9vim.html) - A port of vim to Plan9

### Languages

*Languages which are known to be buildable/operational on Plan9.*

* [Go](https://golang.org/) - The Go programming language
* [Lua](http://download.redis.io/releases/redis-3.0.1.tar.gz) - Lua from Redis
* [Ocaml](http://caml.inria.fr/pub/distrib/ocaml-4.07/ocaml-4.07.1.tar.gz) - Ocaml
* [Scheme 9](http://t3x.org/s9fes/s9fes-20180823.tgz) - Scheme 9 from Empty Space
* [Squeak](https://bitbucket.org/henesy/squeak) - Squeak/Smalltalk from de0u/squeak
* [Tcl](https://9p.io/sources/contrib/fgb/root/sys/src/cmd/tcl/) - Tcl port by fgb
* [TinyScheme](https://download.sourceforge.net/tinyscheme/tinyscheme-1.41.tar.gz) - TinyScheme
* [Myrddin](https://bitbucket.org/oridb/mc) - Systems language by Ori Bernstein

## Libraries

* [libtheme](https://bitbucket.org/mischief/libtheme) - A theming library for the plan 9 graphics system

## Forks

* [9front](http://9front.org/) - Fork featuring new protocols, file systems, and greatly expanded hardware support
* [9legacy](http://9legacy.org/) - Fork which continues maintaining a Bell Labs-like source base
  * [9pi](https://9p.io/sources/contrib/miller/) - Port of 9legacy to the Raspberry Pi
* [9ants](http://9gridchan.org/) - Mycroftiv's fork (of 9front) featuring a modified kernel and custom namespace control tooling
* [Jehanne](http://jehanne.io/) - Giacomo Tesio's fork
* [9atom (deprecated?)](http://www.9atom.org/) - Erik Quanstrom's fork
  * [Mirrored 9atom installers](http://mirror.postnix.pw/9atom/INSTALLERS/)

## Influenced by Plan9

### Kernels

* [plan_rust](https://github.com/TheEnbyperor/plan_rust) - Plan9-influenced kernel in Rust

### Operating Systems

* [Inferno](http://www.vitanuova.com/inferno/) - Register-oriented virtual machine operating system which can run natively and hosted, leverages 9p heavily as "styx"
* [Akaros](http://www.akaros.org/akaros-web/news.php) - Support for parallel and high-performance applications and to scale to a large number of cores
* [Interim](http://interim.mntmn.com/) - Minimal operating system featuring a lisp environment (everything is a file is a symbol)
* [Redox](https://www.redox-os.org/) - A Unix-like operating system written in Rust
