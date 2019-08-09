# Markdown

Markdown can be used for writing readmes, doc, code examples. It's less verbose than HTML.

Markdown files extension: `.md`

```
# <h1> header
## <h2>
###### <h6> (smallest)

_italic text_

**bold text**

_**bold and italic**_

use tildes for `monospace text`

you can make lists:
* item 1
* item 2
  * item 2a
  * item 2b

this is an ordered list:
1. item 1
1. item 2
  1. item 2a
  1. item 2b

link:
[GitHub](http://github.com)

link with title:
[GitHub](http://github.com "Github Homepage")

link to a local file:
[click me](./path/to/file)

insert an image:
![GitHub Logo](/images/logo.png)

you can make task lists:
- [x] this is done
- [ ] this is not done

you can make tables:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

you can use html:

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

add a youtube video:

<a
  href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE"
  target="_blank">
  <img
    src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg"
    alt="IMAGE ALT TEXT HERE"
    width="240"
    height="180"
    border="10" />
</a>

~~crossed out text~~

> blockquote

horizontal rule:
---
```

Src:
* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
* https://guides.github.com/features/mastering-markdown/
