---
layout: page
title: Preparation
---   
## Preparations before GAP Days

In preparation for these GAP Days please get your resources up to date.
Please note that this list will be updated on the go, as we find more things that need to be prepared.

### GAP Days Virtual Preparation
- get/check access to gap-system slack, in which there will be a dedicated GAP Days 2020 channel. If you do not have access to this slack please email us and we will invite you.

- (optional) get Chrome or Chromium for the best functionality of jitsi, the video conferencing tool used.

- connect git account/set up new account for [HackMD.io](https://hackmd.io)

### GAP Days Coding Preparation
- install [Jekyll](https://jekyllrb.com) (may require you to install ruby first)
    - `gem install jekyll`. If `gem` (the ruby package manager) is missing, install `ruby`.
- clone relevant repositories (please put all into the same parent directory):
    ```
    git clone https://github.com/gap-system/Mixer
    git clone https://github.com/gap-system/gap-distribution
    git clone https://github.com/gap-system/GapWWW
    ```

- try to compile `Mixer`:
    ```
    cd Mixer
    make
    ```
- try to build the "old" website in GapWWW branch `gh-pages` (see also its README)
    ```
    cd GapWWW
    ../Mixer/mixer.py -f
    # now inspect generated HTML files in browser
    ```
- try to build the "new" website in GapWWW branch `jekyll`
    ```
    cd GapWWW
    git checkout jekyll
    ../Mixer/mixer.py -f  # still needed for now
    jekyll serve   # starts a local webserver
    ```
- consider reading up on some things:
    - [Max' notes on GAP infrastructure](https://hackmd.io/EUtMx_2mRTaIYYlWSaVI6A)
    - [README.jekyll.md](https://github.com/gap-system/GapWWW/blob/jekyll/README.jekyll.md)
