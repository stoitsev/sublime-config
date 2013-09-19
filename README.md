# Sublime Text 3 Config and Plugins

I am using Sublime Text as my primary editor for couple of months. This is my config and plugins for it.

## Package Control

This is the Sublime Text package manager that makes it exceedingly simple to find, install and keep packages up-to-date.

[Documentation](https://sublime.wbond.net/docs/usage)

## Zen Tabs

Zen Tabs is a Sublime Text 2/3 plugin that helps you to keep you tab bar in Zen.

[Website](https://github.com/travmik/ZenTabs)

`
shift + tab - opens Tab Browser
`

## Bracket​Highlighter

Bracket Highlighter matches a variety of brackets such as: [], (), {}, "", '', <tag></tag>, and even custom brackets.

[Website](https://github.com/facelessuser/BracketHighlighter/tree/BH2ST3)

## Git

Plugin for some git integration.

[Website](https://github.com/kemayo/sublime-git)

## SublimeCodeIntel

A full-featured code intelligence and smart autocomplete engine for Sublime Text.

Provides the following features:

* Jump to Symbol Definition - Jump to the file and line of the definition of a symbol.
* Imports autocomplete - Shows autocomplete with the available modules/symbols in real time.
* Function Call tooltips - Displays information in the status bar about the working function.

[Website](http://sublimecodeintel.github.io/SublimeCodeIntel/)

## SideBarEnhancements

Provides enhancements to the operations on Sidebar of Files and Folders for Sublime Text.

[Website](https://github.com/titoBouzout/SideBarEnhancements/tree/st3)

## Markdown Preview

Preview your markdown files quickly in you web browser from sublime text 2/3.

`
alt + m - preview markdown in the browser
`

[Website](https://github.com/revolunet/sublimetext-markdown-preview)

### To preivew :
  
   - optionnaly select some of your markdown for conversion
   - use `cmd+shift+P` then `Markdown Preview` to show the follow commands:
    - Markdown Preview: Python Markdown: Preview in Browser
    - Markdown Preview: Python Markdown: Export HTML in Sublime Text
    - Markdown Preview: Python Markdown: Copy to Clipboard
    - Markdown Preview: Github Flavored Markdown: Preview in Browser
    - Markdown Preview: Github Flavored Markdown: Export HTML in Sublime Text
    - Markdown Preview: Github Flavored Markdown: Copy to Clipboard
    - Markdown Preview: Open Markdown Cheat sheet
   - or bind some key in your user key binding, using a line like this one:
     `{ "keys": ["alt+m"], "command": "markdown_preview", "args": {"target": "browser", "parser":"markdown"} },`
   - once converted a first time, the output HTML will be updated on each file save (with LiveReload plugin)


## SublimeREPL

SublimeREPL - run an interpreter inside ST2 (Clojure, CoffeeScript, F#, Groovy, Haskell, Lua, MozRepl, NodeJS, Python, R, Ruby, Scala, shell or configure one yourself).

[Website](https://github.com/wuub/SublimeREPL)

### Keybindings

   - Evaluate in REPL:
    - ctrl+,, s Selection
    - ctrl+,, f File
    - ctrl+,, l Lines
    - ctrl+,, b Block
   - Transfer in REPL (just copy, without evaluating it):
    - ctrl+shift+,, s Selection
    - ctrl+shift+,, f File
    - ctrl+shift+,, l Lines
    - ctrl+shift+,, b Block

Note: ctrl+,, f means: press Ctrl and Comma, release all, press F.
