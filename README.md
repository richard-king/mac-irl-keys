# mac-irl-keys 1.0

This is the **XML** code (and a little bit more) to correct the key mapping on an *Apple Macintosh* computer when using an external keyboard (or the inbuilt one on a laptop if you wish), from the standard Apple input to the input expected when using a standard Irish `QWERTY` keyboard (**e.g.**: the locations of the keys **"**, **#**, and **|**, etc.).

* Tested: `OSX 10.8.1 (Mountain Lion)` (64-bit) -- 18 September 2012

## About
This is one of the most frustrating aspects of switching to a *Macintosh* for non Apple users as even the default Apple has set for Ireland fails to locate the *double-inverted-comma* correctly, particularly in the case where you have a normally layed out keyboard and are so unable to reference the, no doubt *'elegant'* and *'innovative'*, character placement. :P

### Features
* Full standard keyboard, lowwer and upper case.
* Accented (fadas) vowels (Alt-a for á, Alt-Shift-a for Á).
* Euro sign (€): Alt-4
* Broken bar (¦): Alt-`
* Dead keys for diacritics found in major European languages:
	* ***\`***: **\`** - Grave accent
	* ***Alt-6***: **ˆ** - Circumflex
	* ***Alt-8***: **¨** - Diareses
	* ***Alt-w***: **˙** - Overdot
	* ***Alt-k***: **˚** - Ring
	* ***Alt-c***: **¸** - Cedilla
	* ***Alt-n***: **˜** - Tilde


## How to install

1. System Preferences *>* Language & Text *>* Input Sources
2. Select `Irish` from the list (*for reference later on*).
3. Clone or download the **repo** and place the `Irish.keylayout` and `Irish.icns` files in the `/System/Library/Keyboard Layouts` directory.
4. System Preferences *>* Language & Text *>* Input Sources
5. Select the unselected `Irish` from the list.
6. Deselect the old `Irish` on the list.

## Issues

* The flag icon (`Irish.icns`) appearing is kind of hit and miss.
* It may be necessary to logout and log back in in order for the new key layout to be detected for display in the list of possibles by `OS X`.
* It may also be necessary to logout and log back in for the newly selected key layout.