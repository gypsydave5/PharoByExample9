# Style guide

## Writing

### Spelling

- [**American English**](https://en.wikipedia.org/wiki/American_English) (en_US) throughout.

### Punctuation

Use the [Oxford comma](https://en.wikipedia.org/wiki/Serial_comma):

> Pharoers are friendly, helpful, and kind.

not

> Pharoers are friendly, helpful and kind.

### Markup

Snippets of Pharo (or other) code inline should be marked up as fixed width, `==`:

> create a new instance with ==MyObject new==

References to files should also be marked up as fixed width, `==`:

> simply import your ==.image== and its associated ==.changes== file using the launcher.

References to GUI buttons inline should be marked up in bold, `""`:

> Here we clicked on the top left ""New"" icon to download a new image.

References to menus should be marked up in bold:

> Open the ""System"" menu

Navigation should be indicated with a `>`:

> Open ""System > File Browser""

#### Key strokes (and key combinations)

Keys typed should be capitalized.

> `Shift-D`

not

> `Shift-d`

A single chord should be written with hyphens:

> `Ctrl-Alt-Del`

Sequences should be written with a space between the parts:

> `Cmd-O Cmd-W`

However, some sequences require the modifier key to remain pressed throughout. Write these with a comma:

> `Cmd-O,W`

would open a Playground.

https://en.wikipedia.org/wiki/Modifier_key

##### macOS

The modifier keys should always be written in the order `Control Option Shift Command`

The modifier keys should be written in abbreviated form of `Ctrl Option Shift Cmd`

https://developer.apple.com/design/human-interface-guidelines/macos/user-interaction/keyboard/

##### Windows / Linux

The modifier keys should be written in the order `Control Alternate Meta Shift`

The modifier keys should be written in the abbreviated form of `Ctrl Alt Meta Shift`

### Titles / Subtitles

Titles written in sentence casing, without a terminating period:

> A quick tour of Pharo

not

> A Quick Tour of Pharo.

## Technical Terms

### Pharo Tools

Always capitalize the name of a Pharo tool.

> Edit the method in the Browser

not

> Edit the method in the browser

This is to clarify that it is the _Pharo_ Browser we're talking about, not (for instance) your system web browser.

When introducing a tool, prefer to bold its name (`""Debugger""`): 

> this will open the **Debugger**.

### Getters, Setters and Accessors

The preferred terms for these is "getter method" and "setter method", or "getter" and "setter" for short. Do not use "mutator method" or similar.

"Accessor method" refers to these methods generically, or to a method which can act as both a getter and a setter.

### Test-Driven Development

Always hyphenate the first two words, even when in different tenses:

> We can test-drive this code.

But prefer to use an alternative formulation to avoid any confusion with "test-drive" meaning "try out". Better would be:

> We can drive this code out with tests.

Abbreviate freely to TDD throughout.

### Operating Systems

The Apple operating system for Mac is called **macOS** _not_ **OS X** or **OSX**.
