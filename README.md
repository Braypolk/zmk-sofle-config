This repo is for my zmk sofle split keyboard and it also has my goku config for karabiner (mac keyboard mapping)


# Generate Keymap Images

First comment out so that only keymap remains. Then run

```zmk-viewer generate -f config/sofle.keymap sofle_choc --single && zmk-viewer generate -f config/sofle.keymap sofle_choc --unified```