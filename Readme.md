# About

This fork of the corporate design beamer template is intended to be XeLaTex (and possibly LuaLaTex) compatible.
The packages `inputenc` and `fontenc` are not required anymore.

Further this fork does not require the `cabin` package to be available but ships a folder containing the opentype font files.
These are defined as the standard sans font using `fontspec`.

## But why?
I have to use XeLaTex in order to make use of `unicode-math`. 
This way, unicode glyphs such as α,β,γ,… can be used in math environments.

