# Caps2Esc.spoon

Map your useless <kbd>caps lock</kbd> to _magic_ <kbd>control</kbd>. When you press it with
something else it works like <kbd>control</kbd>. When you press it in isolation it works
as <kbd>escape</kbd>.

## Intallation

You need [Hammerspoon](http://www.hammerspoon.org/) installed.

```bash
brew install hammerspoon
```

Clone spoon

```bash
git clone --depth 1 https://github.com/lazydo9/Caps2Esc.spoon.git ~/.hammerspoon/Spoons/Caps2Esc.spoon
mkdir -p ~/.hammerspoon
echo "hs.loadSpoon('Caps2Esc'):start()" >> ~/.hammerspoon/init.lua
```

Open _System Preferences_, navigate to _Keyboard > Modifier Keys_, set the <kbd>caps lock</kbd> key to <kbd>control</kbd>.

Reload hammerspoon config. That's it.
