# Iris Rev4 Devo Layout

Forget everything you thought you knew about QMK. I inevitably forget how to
flash this thing or QMK changes. Basically, just clone the QMK firmware, clone
this repository in
`keyboards/keebio/iris/keymaps`
go to the root of the repo and run
```bash
sudo make keebio/iris/rev4:devo:dfu-split-left
sudo make keebio/iris/rev4:devo:dfu-split-right
```
Making sure to plug in the correct half and put it into dfu mode. I think this
layout is pretty sick ngl and it's roughly the same as my crkbd layout as well
so I don't mess up when I switch between them. _profit_

Also if you don't have the enter button on your thumb, you're not even living.
So much power.
