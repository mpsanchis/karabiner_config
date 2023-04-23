# karabiner_config
Configuration for Karabiner-Elements app

# Complex modifications
The remapping was done to avoid the problem in the MacOS terminal which, when selecting "Option as Meta Key", it prevents using
the option key for anything else other than meta (e.g. option can be used to jump from word to word, but it can't be used in 
combination with other keys to generate special characters).
This led me to choose between these two alternatives:
  1. Not being able to jump between words (opt + arrows) or deleting whole words (opt + delete/back)
  2. Not being able to create the special characters that are generated in a swiss-german keyboard with option (e.g: ~@[]|{}#)

The complex modifications I added allow to generate these symbols using the Shift key plus others, as can be seen in `complex-modif-remapping.png`.

# Using accents
In my day-to-day, I might still need to use accents, and I removed three keys that contain them. However they can still be generated:
  - Acute accent ``(´)`` with option+`<last-key-in-number-row>`, where `<last-key-in-number-row>` has the symbols ``(`)`` and `(^)` printed.
    - Note that this requires the option key, but I do not expect to ever need acute accents when typing in the terminal.
  - Grave accent ``(`)`` with shift + `<last-key-in-number-row>`
  - Umlaut ``(¨)`` with `<last-key-in-qwertz-row>`, where `<last-key-in-qwertz-row>` has the symbols `(!)` and `(¨)`printed.