# qmk_keymap

My keeb.io iris rev7 keymap

## Install

Clone this repo into your `qmk_firmware` folder:

```bash
cd ~/qmk_firmware/keyboards/keebio/iris/keymaps/
git clone https://github.com/ubermanu/qmk_keymap ubermanu
```

## Build

```bash
qmk compile -kb keebio/iris/rev7 -km ubermanu
```

## Flash

```bash
qmk flash -kb keebio/iris/rev7 -km ubermanu
```
