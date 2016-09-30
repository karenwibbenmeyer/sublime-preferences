# Sublime


## Tips
[Tips/Tricks/Shortcuts](https://generalassemb.ly/blog/sublime-text-3-tips-tricks-shortcuts)


## Keyboard Shortcuts
key | action
--- | ---
`⌘-P` | go to anything (file, :line, @definition)
`⌘-Shift-P` | command prompt
`Ctrl-W` | wrap selection in html tag
`Ctrl-Space` | display autocomplete
`⌘-U` | soft undo

## Text Shortcuts
key | action
--- | ---
`⌘-D` | select word
`⌘-L` | select line
`Ctrl-D` | select between container
`Ctrl-Shift-M` | select between brackets
`⌘-Shift-K` | select both surrounding tags
`⌘-Shift-J` | select with similar indentation
`Ctrl-T` | swap 2 (or more) selections (transpose)
`⌘-C` `⌘-X` `⌘-V` | copy/cut/paste current line (if no selection)
`⌘-Shift-V` | paste respecting indentation
`⌘-Shift-D` | duplicate line
`Ctrl-Shift-K` | delete line
`⌘-J` | join line below to end of current line
`⌘-Return` | insert line after
`⌘-Shift-Return` | insert line before
`⌘-[` `⌘-]` | indent line
`⌘-/` | comment
`⌘-Alt-/` | block comment
`⌘-Ctrl-Up` `⌘-Ctrl-Down` | move current line up or down
`Opt-Up` `Opt-Down` | increment up/down by 1
`Shift-Opt-Up` `Shift-Opt-Down` | increment up/down by 10
`⌘-KU` | uppercase
`⌘-KL` | lowercase

## Emmet Shortcuts
key | action
--- | ---
`lorem` + Tab | add lorem ipsum text
`lorem100` + Tab | add 100 words of lorem ipsum text


## Tips
- selecting dashed (-) words:
	- Preference -> Settings - Default
	- remove '-' from: ```“word_separators”: “./\()"’-:,.;<>~!@#$%^&*|+=[]{}`~?”,```


## Packages
- AlignTab
- AutoFileName
- Color Highlighter
	- [__Preferences__ -> __Package Settings__ -> __ColorHighlighter__ -> __Settings - Default__](ColorHighlighter-default.md)
- CSS Comments
- Emmet
- Git
- HTML-CSS-JS Prettify
- HTMLAttributes
- JavaScript Completions
- JavaScript Snippets
- jQuery
- jQuery Snippets pack
- jsFormat
- MarkdownEditing
- SASS
- SASS Snippets
- Sublime Linter
	- [__Preferences__ -> __Package Settings__ -> __SublimeLinter__ -> __Settings - Default__](SublimeLinter-default.md)

**without SASS**
- Autoprefixer
  - In CSS file, open Command Pallete `⌘-Shift-P` and choose `Autoprefix CSS`
- CSS Color Converter
  - Select a color, hit `⌘-Shift-C` to convert to next type (hex -> rgba -> hsla -> hex -> etc)
