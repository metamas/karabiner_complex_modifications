# Karabiner Complex Modifications

This repo is simply documentation and backup of the custom keyboard modifications/bindings I have configured using [Karabiner-Elements](https://karabiner-elements.pqrs.org/), a keyboard customiztion tool for macOS. All key names and directory references used are therefor conventional to macOS.

## How to Use

The simplest way to ue these keybindings is to copy/download any of the `.json` files in this repo to the following directory:

`~/.config/karabiner/assets/complex_modifications`

## Emacs Specific Modifications

I recently began learning the "venerable" [GNU Emacs](https://www.gnu.org/software/emacs/) text editor. Many of its bindings are combinations with the <kbd>control</kbd> key. That can become awkward and frustrating on many modern laptop keyboards that only provide a left-side <kbd>control</kbd> key. I'm currently experimenting with the following two bindings for triggering a `right_control` key signal.

~~This first option is nice because both my hands already have much muscle memory developed for using my pinky and thumb together for bindings that combine <kbd>command</kbd> or <kbd>option</kbd> with <kbd>shift</kbd>~~.

1. ~~`right_option` + `right_shift` = `right_control`~~

This second combination is the closest I can get to mirroring the left-side <kbd>control</kbd> key position onto the right-side without totally replacing the `left_arrow` signal with `right_control` — which I tried and didn't like.

2. `right_option` + `left_arrow` = `right_control`

**I've settled on the second of the two experimental bindings. It only took me a couple days to realize the first obstructed other bindings I use when in [VS Code](https://code.visualstudio.com/). I'm not willing to change those, and I want any system-wide binding I define to play nicely across all the applications I use.**
