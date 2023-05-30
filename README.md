# TESTS
<!-- line tests -->
*** 
---

## Links
This is [an example][id] reference-style link.

[id]: http://example.com/ "Optional Title Here"

**[down](###Footnotes)**


## Styles
- italic: *single asterisks*
- italic: _single underscores_
- <u>underlined</u>
- bold: **double asterisks**
- bold: __double underscores__
- ~~strikedthrough~~
- combined: ***three asterisks***
- <span style="color:red">red text</span>
- <font color="red">This text is red!</font>
- <p style="color:blue">Make this text blue.</p>

### Code
Use the `printf()` function.

``There is a literal backtick (`) here.``

## Images+
![Image](./data/markdown_1.png "logo1")

![Alt text](./data/markdown_2.png "logo2")

<!-- [from](https://app.diagrams.net) -->
![Installation](./doc/test.drawio.svg "diagram test")

### Emojis
:warning: ATTENTION :warning:

### Arrows
- Up arrow (↑): &uarr;
- Down arrow (↓): &darr;
- Left arrow (←): &larr;
- Right arrow (→): &rarr;
- Double headed arrow (↔): &harr;


## Tables
| **left**        | **centre**   | **right** |
| :---------- | :------: | ----: |
| Paragraph   | First paragraph. <br><br> Second paragraph. | test

- `-` means the column is left aligned.
- `--:` means the column is right aligned.
- `:-:` means the column is center aligned.


## Footnotes
here is a note [^1] . look down -.-


## Links 
### internal / local
- [Tables](#tables)
### external
- [Markdown Hacks](https://www.markdownguide.org/hacks/)
- [Arrows](https://www.toptal.com/designers/htmlarrows/arrows/)

---
## Comments

<!-- 
block comment
-->

[This is a comment that will be hidden.]: place_some_single_worded_text_here


<!-- not supported by every interpreter! -->
[^1]: footnote text
