![Icon](https://github.com/netevert/dnsmorph/blob/master/docs/icon.png)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fintrigueio%2Fdnsmorph.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fintrigueio%2Fdnsmorph?ref=badge_shield)
==================================================================

This version of DNSMORPH is a fork of the original, available at https://github.com/netevert/dnsmorph

DNSMORPH includes the following domain permutation attack types:
- Homograph attack (both on single and duplicate characters)
- Bitsquat attack
- Hyphenation attack
- Omission attack
- Repetition attack
- Replacement attack
- Subdomain attack
- Transposition attack
- Vowel swap attack
- Addition attack
- Tld Brute attack

Installation
============
There are two ways to install dnsmorph on your system:

1. Downloading the pre-compiled binaries for your platform from the [latest release page](https://github.com/netevert/dnsmorph/releases) and extracting in a directory of your choosing.

2. Downloading and compiling the source code yourself by running the following commands:

    - ```go get -v github.com/intrigueio/dnsmorph```
    - `cd /$GOPATH/src/github.com/intrigueio/dnsmorph`
    - `go get -v ./...`
    - `go build`


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fintrigueio%2Fdnsmorph.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fintrigueio%2Fdnsmorph?ref=badge_large)