# GitHub-Markdown.tmbundle
Provides some [GitHub Flavoured Markdown](https://help.github.com/articles/github-flavored-markdown/) extensions for TextMate to make working with GitHub Flavoured Markdown nicer.

## Features
- Add a new "Preview" command (overriding the existing Markdown preview) using [Redcarpet](https://github.com/vmg/redcarpet) to render GitHub Flavoured Markdown
- Support triple-backtick raw blocks and support syntax highlighting for various languages (others can be added trivially). There’s also a tab trigger for inserting raw blocks: Just type a single backtick (<kbd>`</kbd>) and then hit the tab key.
- Support and highlight GitHub Flavoured Markdown strikethroughs, tables, references, checkboxes and italics

You can also use nicer fonts by installing the [GitHub Flavoured Markdown Font Settings bundle](https://github.com/mikemcquaid/GitHub-Markdown-Font-Settings.tmbundle).

## Installation
### TextMate 2

Check "Markdown (GitHub)" in TextMate 2's Preferences' Bundles.

Alternatively:
```bash
mkdir -p ~/Library/Application\ Support/Avian/Bundles
cd ~/Library/Application\ Support/Avian/Bundles
git clone https://github.com/mikemcquaid/GitHub-Markdown.tmbundle
```

### TextMate 1
```bash
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone https://github.com/mikemcquaid/GitHub-Markdown.tmbundle
osascript -e 'tell app "TextMate" to reload bundles'
```

## Status
The above features are tested and working for my day-to-day.

Tested using TextMate 2. May work in TextMate 1 or Sublime Text; I've no idea.

[Patches welcome](https://github.com/mikemcquaid/GitHub-Markdown.tmbundle/pulls).

## Contact
[Mike McQuaid](mailto:mike@mikemcquaid.com)

## License
GitHub-Markdown.tmbundle is licensed under the [MIT License](http://en.wikipedia.org/wiki/MIT_License). The full license text is
available in
[LICENSE.txt](https://github.com/mikemcquaid/GitHub-Markdown.tmbundle/blob/master/LICENSE.txt).
