Kalolo is a dark 256-colors scheme for the [kakoune](https://kakoune.org/) editor.

Features
========

- Selections are in shades of yellows in normal mode and blues in insert mode.
- Selections let the syntax coloring appear ("alpha blending").
- Primary selection, secondary selection, primary cursor, secondary cursor and
  end-of-line cursors all have different colors.
- It tries to stay semantically consistent:

    - Green is only used for comments (because comments are important),
    - with documentation in bold (because documentation is very important),
    - and strings (because messages are often close to comments).
    - Variable-related objects are in blues.
    - Operator and delimiters are (lightly) highlighted, to ease the visual parsing.
    - Attributes are in yellow.
    - Builtins keyword are slightly more highlighted than normal text, to allow
      for an immediate visual typo checking.
    - Keywords are in red, with flow-related ones (if, for, etc.) in bold.

"kalolo" (New-Caledonia familiar adj.) means "beautiful, cute".


Dependencies
============

Some faces depends on additional highlight keywords: `flow` and `state`.

Screeshots
==========

![Screeshot in insert mode](https://raw.githubusercontent.com/nojhan/kalolo/main/screen_insert.png)
![Screenshot in normal mode](https://raw.githubusercontent.com/nojhan/kalolo/main/screen_normal.png)
