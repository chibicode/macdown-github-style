# macdown-github-style

Markdown preview style based on GitHub's CSS for [MacDown.app](https://macdown.uranusjr.com/). More up-to-date than the built-in version. Based on [sindresorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css).

<img width="1680" alt="screenshot 2017-05-03 at 12 09 12 pm" src="https://cloud.githubusercontent.com/assets/992008/25647971/820b8a4e-2ff9-11e7-9aba-dacb931cf807.png">

Note that this doesn't update syntax highlighting.

## Usage

1. Add `github-markdown.css` to `~/Library/Application\ Support/MacDown/Styles`
2. On MacDown, go to `Preferences` > `Rendering` and click `Reload`. Then select `github-markdown` from `CSS`.

## How it's generated

1. Download `github-markdown.css` from [sindresorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)
2. Replace `.markdown-body` with `body`
3. Add `padding: 30px;` to `body`
