## 1.6.1

> Released Jan 16, 2017

- **FIX**: Don't install tools or tests folder when installing from Pypi.

## 1.6.0

> Released Jan 15, 2017

- **NEW**: EscapeAll has the option to perform more like Pandoc in that you can enable escaped newlines to be `hardbreaks`, and escaped spaces to be `nbsp`.
- **NEW**: Rework poorly thought out snippets format to require quoting file names with single line format.  Add a block format.  Allow commenting out lines temporarily.  And allow a way to escape them by placing a space after them.
- **FIX**: Fix documentation issues.

## 1.5.0

> Released Jan 13, 2017

- **NEW**: New EscapeAll extension.
- **NEW**: New Snippets extension for including external files into a Markdown file.
- **NEW**: Arithmatex now has configurable output wrapper.
- **NEW**: PathConverter no longer verifies existence of path to allow it more flexible usage.
- **NEW**: PathConverter now only converts relative paths when converting to a relative or absolute location.
- **NEW**: Improved support for path path identification for PathConverter and B64.
- **FIX**: Fixed issue where Arithmatex was un-escaping `$` within math region.
- **FIX**: Fixed issue where plugins would append globally changing the escape list opposed to just in the in the Markdown instance.
- **FIX**: Fixed logic issue where the `mark`, `caret`, and `tilde` extension weren't quite modeling `betterem` inline behavior.
- **FIX**: Critics shouldn't allow escaping critic marks as it is not in the spec.

## 1.4.0

> Released Jan 5, 2017

- **NEW**: HeaderAnchor extension is now deprecated.  It will be removed in a future version.
- **NEW**: HeaderAnchor is no longer included in the `pymdownx.github` extension.
- **NEW**: Slugify functions are moved to `pymdownx.slug` in preparation of HeaderAnchor removal.
- **FIX**: GitHubEmoji is not "pending" deprecation, but is actually deprecated.

## 1.3.0

> Released Jan 1, 2017

- **NEW**: New Emoji extension that aims to replace GitHubEmoji.  By default it is configured for EmojiOne and Gemoji (GitHub's emoji).
- **NEW**: GitHubEmoji is deprecated. Please use the Emoji extension instead.
- **NEW**: PyMdown extension is deprecated.  PyMdown extension was just a wrapper, please configure the desired individual extension(s) instead of relying on PyMdown.
- **NEW**: `github` extension now turns off `nl2br` by default in order properly emulate recent changes in GFM.  `no_nl2br` option is deprecated and will be removed in the future as it no longer reflects GFM behavior.

## 1.2.0

> Released Nov 1, 2016

- **NEW**: Add option to output task lists in a more customizable way.

## 1.1.0

> Released Mar 1, 2016

- **NEW**: Add pypi 3.5 info in setup
- **NEW**: Add option to MagicLink extension to allow the stripping of link protocols (`http://` etc.).
- **NEW**: Add option to `github` extension to disable the use of `nl2br` to reflect recent changes to GitHub Flavored Markdown.  Currently the default is the legacy (uses `nl2br`), but a warning will be displayed.  In the future, the option will be defaulted to not use `nl2br`.

## 1.0.1

> Released Dec 10, 2015

- **FIX**: Ordinal number 11th, 12th, and 13th

## 1.0.0

> Released Dec 8, 2015

- **NEW**: Initial release.
