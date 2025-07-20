---
tags:
  - extendedsdk
  - decorators
  - crate-spawners
---

## Basic Setup

First, add a Crate Spawner of the **Clipboard Lore** crate. Add the **Lore Clipboard Proxy** component, then fill it out!
## Color

When **Use Color** is toggled on, the text on the clipboard will use the **Text Color**. The default color in the script is black and completely transparent, so you *must* increase the alpha value of the color (preferably to the max) to see the text. When **Use Color** is toggled off, it will use solid black text.

You may also use [Unity's Rich Text](https://docs.unity3d.com/Packages/com.unity.ugui@1.0/manual/StyledText.html) to recolor individual strings of text. For example: `<color=blue>Some text here!</color>`.

Here's a basic setup:

![[ClipboardSetup.png]]