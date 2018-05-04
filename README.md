# Choose your mozconfig interactively

Interactively choose on of your mozconfig files and copy it into your Firefox source tree.

## Prerequisites

* [fzf](https://github.com/junegunn/fzf) - Fuzzy file finding
* [fd](https://github.com/sharkdp/fd) - Fast file finder


_Note: alternative tools (selecta, find) would work as well, the script is currently hard-coded for the above._

## Install

1. `git clone https://github.com/badboy/mozconfigs`
2. `ln -s /path/to/mozconfigs/mozcfg ~/bin/mozcfg`
3. Done!

## Usage

```
mozcfg
```


## References

* [Configuring Build Options](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/Configuring_Build_Options)
