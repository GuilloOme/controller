Keyboard Compiler Scripts
=========================

Scripts for major keyboards designed using the Kiibohd firmware.
Please refer to `<script> --help` for specific details.

Refer to the [wiki](https://github.com/kiibohd/controller/wiki) on setting up your system for compiling.


Build Steps
-----------

* edit `Bepo-*.kll`
* run `./bepo-ergodox.bash`
* you'll find the `.bin` in the current folder

Example
-------

```bash
./infinity.bash
```


Projects
--------

* infinity.bash     (Infinity Keyboard 2014/10/15 (MD1))
* infinity_led.bash (Infinity Keyboard with LED backlight support (MD1.1))
* ergodox.bash      (Infinity Ergodox 2015/08/15)
* template.bash     (Example template for new keyboards)
* whitefox.bash     (WhiteFox Keyboard)


**Extra files**

* cmake.bash (Used by the compilation script, does nothing on it's own)

