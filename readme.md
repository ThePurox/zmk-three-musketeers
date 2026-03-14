This is a zmk module for [the three musketeers keyboard](https://github.com/1000eyed/the-three-musketeers) by [1000eyed](https://github.com/1000eyed)

It works with local zmk build with the command `west build -p -s zmk/app -b seeeduino_xiao_rp2040 -- -DZMK_EXTRA_MODULES="$PATH_TO_THIS_REPO" -DSHIELD=musketeers` executed from your local zmk-toolchain. I've not tested it with gh-actions.
