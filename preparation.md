---
layout: page
title: Preparation
---   
## Preparations before GAP Days

In preparation for these GAP Days please get your resources up to date.
Please note that this list will be updated on the go, as we find more things that need to be prepared.

- install [Jekyll](https://jekyllrb.com) (may require you to install ruby first)
    - `gem install jekyll` if `gem` (the ruby package manager) is there
- clone relevant repositories (please put all into the same parent directory):
    - https://github.com/gap-system/Mixer
    - https://github.com/gap-system/gap-distribution
    - https://github.com/gap-system/GapWWW 
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
    - [README.jekyll.md](https://github.com/fingolfin/GapWWW/blob/mh/gh-pages/README.jekyll.md)