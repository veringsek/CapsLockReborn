# CapsLockReborn

CapsLock needs an overhaul.

## Philosiphy

<kbd>CapsLock</kbd> to switch between uppercase and lowercase is no longer useful.

In areas with non-phonetic writing systems, uppercase or lowercase makes no sense and no use.

In areas with phonetic writing systems, however, people still don't like <kbd>CapsLock</kbd>. They don't even often use uppercase properly. Even when they do, they can easily type uppercase letters by holding <kbd>Shift</kbd>.

Yet, <kbd>CapsLock</kbd> sits at a very convenient place, with very low use rate.

<kbd>CapsLock</kbd> needs an overhaul.

Apple did a good try by letting <kbd>CapsLock</kbd> to switch input method, but it could be more than just that.

<kbd>CapsLock</kbd> should become a key for input method. A decoration key.

When typing in english-like writing systems, switching input method seems much less useful to people than it actually is. In other writing systems, however, switching input method is necessary. In Japanese, people need to switch between hiragana, katakana and English; in Russian, people need to switch between Cyrillic and English.

Other than switching input method, there are more input method functions that need to be accessed, like half- or full-width space, Traditional or Simplified Chinese, punctuations, user dictionary operation, special characters and so on.

Special characters, including some Unicode characters that can't be input through normal input methods, especially those refuse to implement input method functions, for example, English. These characters can be easily input if an input method funciton is implemented, and <kbd>CapsLock</kbd> can provide a shortcut to access the input method function. It could be like, <kbd>CapsLock</kbd> + <kbd>M</kbd> to show a special characters searching window, and type `integral` to get `∫` .

As you can see, to let one key access those many functions, it's necessary to make `CapsLock` a decoration key, which can be used like `Shift` , `Ctrl` and `Alt` . Once it becomes a new decoration key, it opens up a new possibility for many potential application, like those mentioned above, GIFs insert, contacts, encryption and decryption.

The combination is up to input method, but because `CapsLock` is specific to input method funciton, these combination won't conflict with applications' hotkeys. For example, people who use Microsoft New Zhuyin as the input method now faces a problem that the common used punctuation `，` must be input with <kbd>Ctrl</kbd> + <kbd>, </kbd> , and that conflicts with many applications as they use <kbd>Ctrl</kbd> + <kbd>, </kbd> to access setting pages.

<kbd>CapsLock</kbd> can also provide some left hand side shortcuts for some keys sitting at right hand side, like <kbd>CapsLock</kbd> + <kbd>W</kbd> for <kbd>↑</kbd>, <kbd>CapsLock</kbd> + <kbd>S</kbd> for <kbd>↓</kbd>, <kbd>CapsLock</kbd> + <kbd>A</kbd> for <kbd>←</kbd>, <kbd>CapsLock</kbd> + <kbd>D</kbd> for <kbd>→</kbd>, <kbd>CapsLock</kbd> + <kbd>Q</kbd> for <kbd>Home</kbd>, <kbd>CapsLock</kbd> + <kbd>E</kbd> for <kbd>End</kbd>, <kbd>CapsLock</kbd> + <kbd>F</kbd> for <kbd>Enter</kbd>, <kbd>CapsLock</kbd> + <kbd>G</kbd> for <kbd>Delete</kbd>. 

With the AutoHotkey script [ `CapsLockReborn.ahk` ](CapsLockReborn.ahk) some functions are implemented. Unfortunately, those about input methods are not implemented because every input method relies on different hotkeys.

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright © 2022, veringsek
