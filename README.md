# Arc-for-Vivaldi  
Arc for Vivaldi is a custom css file that integrates Vivaldi's UI with [Arc](https://github.com/NicoHood/arc-theme) (or [Arc Grey](https://github.com/eti0/arc-grey-theme)), a popular GTK theme. Optionally integrate with [Arc Grey](https://github.com/eti0/arc-grey-theme) instead of vanilla Arc.

User [drakkar1969](https://github.com/drakkar1969) forked this skin and almost completely rewrote it. You might like his fork more than mine, find his fork [here](https://github.com/drakkar1969/Arc-for-Vivaldi)

**Note:** drakkar's css is much nicer and more customizable than mine, and he changed way more of the interface than I did. Moreover he's more active in updating his fork than I am in updating this. My time is mostly being focused on other projects nowadays, especially [Isabella.](https://github.com/isabella-theme) I'll still maintain Arc for Vivaldi until drakkar's fork gets enough attention to replace it, and I will help with issues if you find any. However I highly recommend you switch to drakkar's fork because I don't even use Arc or this skin anymore, and [am working on a new one.](https://github.com/isabella-theme/isabella-vivaldi) Sorry for any inconvenience.

## Installation
First, find `style` in your Vivaldi install directory. It should be in the following places depending on your platform:

**Linux:** `/opt/vivaldi/resources/vivaldi/style`  
**Windows:** `%localappdata%\Vivaldi\Application\[version]\resources\vivaldi\style`  
**Mac:** `/Applications/Vivaldi.app/Contents/Versions/[version]/Vivaldi Framework.framework/Resources/vivaldi/style`

Now,

If you just want to **integrate with Arc,** save `arc.css` in the style folder. (You should be left with a folder structure like this: `resources/vivaldi/style/arc.css`)  
Then open `resources/vivaldi/browser.html` in a text and add the following to `<head>`  
`<link rel="stylesheet" href="style/arc.css" />`

If you want to **integrate with arc-grey instead of Arc,** save `arc-grey.css` in the same folder as `arc.css` and then open `browser.html` again and add `<link rel="stylesheet" href="style/arc-grey.css" />` under the code from the last step.

If you want to **use the Arc window buttons** instead of Vivaldi's default window buttons, save the `arc` folder in style as well.

**Note:** *You may like the way this theme generally looks but not want to use Arc's window buttons. If you'd prefer not to use Arc's window buttons, open `arc.css` in a text editor and find line 173 for instructions on how to not use them.*

**Also note:** *Arc's scrollbars only get applied to internal pages and, as far as I know, there's nothing I can do about that from within a custom css file for Vivaldi. But I also wrote a userstyle that you can use to apply the scrollbars on websites. Install it [here.](https://userstyles.org/styles/142645/arc-scrollbars)*

**Note also:** *Because Vivaldi features a built-in theme editor, it is easier to create a custom Arc theme and then to use this CSS on top of that theme. This custom CSS is necessary to integrate with Arc because you cannot currently customize every aspect of Vivaldi from the editor. See below.*

| Arc theme settings:              | Arc Dark theme settings:         | Arc Darker theme settings:       |
| -------------------------------- | -------------------------------- | -------------------------------- |
| Background: #e7e8eb              | Background: #2f343f              | Background: #f5f6f7              |
| Foreground: #303030              | Foreground: #d3dae3              | Foreground: #7a8b94              |
| Highlight: #5294e2               | Highlight: #5294e2               | Highlight: #5294e2               |
| Accent: #f9f9fa                  | Accent: #383c4a                  | Accent: #2f343f                  |
| [ ] Apply Accent Color to Window | [ ] Apply Accent Color to Window | [x] Apply Accent Color to Window |
| [x] Transparent Tabs             | [x] Transparent Tabs             | [x] Transparent Tabs             |
| Corner Rounding: 2px             | Corner Rounding: 2px             | Corner Rounding: 2px             |

| Arc Grey theme settings:         | Arc Grey Dark theme settings:    | Arc Grey Darker theme settings:  |
| -------------------------------- | -------------------------------- | -------------------------------- |
| Background: #e8e8e8              | Background: #383838              | Background: #f5f5f5              |
| Foreground: #757575              | Foreground: #dbdbdb              | Foreground: #6b6b6b              |
| Highlight: #999999               | Highlight: #999999               | Highlight: #999999               |
| Accent: #f5f5f5                  | Accent: #4a4a4a                  | Accent: #4a4a4a                  |
| [ ] Apply Accent Color to Window | [ ] Apply Accent Color to Window | [x] Apply Accent Color to Window |
| [x] Transparent Tabs             | [x] Transparent Tabs             | [x] Transparent Tabs             |
| Corner Rounding: 2px             | Corner Rounding: 2px             | Corner Rounding: 2px             |

## Screenshots:
Imgur Album: https://imgur.com/a/jMSWq

**Need more help?** Get in touch!
- join my [Discord server](https://discord.gg/ZfDP2ZV)
- [Create an issue here on GitHub](https://github.com/Tiamarth/Arc-for-Vivaldi/issues/new)
- [Email me](mailto:jontiamac@gmail.com)

----

[pre-github changelog](https://github.com/Tiamarth/Arc-for-Vivaldi/blob/master/changelog.txt) | [AFV thread on the Vivaldi forums](https://forum.vivaldi.net/post/137297)  
