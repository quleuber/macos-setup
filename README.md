# macos-setup

## Tiling Windows Manager

An i3-like tiling WM: [Yabai](https://github.com/koekeishiya/yabai/)

References:

- [So you want i3wm on MacOS?](https://cbrgm.net/post/2021-05-5-setup-macos/)
- [Gist by @Krever: Yabai setup for i3wm users](https://gist.github.com/Krever/74d43fa38c57c42c355df55faa0a00ee)
- [FAQ: System Integrity Protection #13](https://github.com/koekeishiya/yabai/issues/13)
- For M1/Monterey (as of 2020-03-01, Monterey 12.2.1):
  - https://github.com/koekeishiya/yabai/issues/1054#issuecomment-974818851
  - https://github.com/koekeishiya/yabai/wiki/Installing-yabai-(from-HEAD)

My config:

- https://github.com/quleuber/dotfiles/blob/master/home/.config/yabai/yabairc
- https://github.com/quleuber/dotfiles/blob/master/home/.config/skhd/skhdrc

Extra software:

- [kitty](https://sw.kovidgoyal.net/kitty/)
  - `brew install --cask kitty`
  - bound to `$mod + return`
  - command: `kitty -1 --instance-group yabai -d ~`
