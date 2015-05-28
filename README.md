# Headers
# h1
## h2
### h3
#### h4
##### h5
##### h6
###### h7
####### h8

underline with '='s
====== 

underline with '-'s
------

# Emphasis
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **double asterisks** or __ double underscores __.

Combined emphasis with with **asterisks and _underscores_**

Strikethrough uses two tildes, ~~ Scratch that. ~~

# Lists
1. First ordered list item
2. Another item
  * unordered sub-list
1. Actual numbers don't matter, just that it's a number
  1. ordered sub-list
4. and another item 

   you can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

   To have a line break without a paragraph, you will need to use two trailing spaces.  
   Note that this line is separate, but within the same paragraph.  
   (this is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* unordered list can use asterisks
- Or minuses
+ OR pluses

# Links

There are two ways to create links.

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com


# Images
Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

REference-style:
![alt text][logo]

[logo]:https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

# Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn't. 
However, many renderers -- like Github's and Markdown Here -- support 
syntax highlighting. Which languages are supported and how those 
language names should be written will vary from renderer to renderer.
Markdown Here supports highlighting for dozens of languges (and 
not-really-languages, like diffs and HTTP headers); to see the complete 
list, and how to write the langauge names, see the
[highlightjs demo page](https://highlightjs.org/static/demo/ "demo page")

Inline `code` has `back-ticks around` it.

Blocks of code are either fenced by lines with three back-ticks ```, or are indented with four spaces. 
I recommend only using the fenced code blocks -- they're easier and only they support syntax highlight.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

# Tables

Tables aren't part of the core Markdown spec, but they are part of GFM and Markdown Here supports them.
They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting 
from another application. 

```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      | $1    |

The outer pipes (|) are optional, and you don't need to make the raw Markdown lineup prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      | $1    |

The outer pipes (|) are optional, and you don't need to make the raw Markdown lineup prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


# Writing on Github
## Task Lists

- [ ] a bigger project
 - [x] first butask #1234
 - [x] follow up subtask #4321
 - [x] final subtask cc @mention
- [ ] a separate task

## References

Certain references are auto-linked:

* SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User@SHA: jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* #Num: #26
* GH-Num: GH-26
* User#Num: jlord#26
* User/Repository#Num: jlord/sheetsee.js#26


# Blockquotes

> Blockquotes are very handy in email to emulate reply text
> This line is part of the same quote

Quote break.
> This is a very long line that will still be quoted properly when it wrap. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

# Inline HTML

You can also use raw HTML in your Markdown, and it'll MOSTLY work pretty well. 

<dl>
    <dt>Definition list </dt>
    <dd>Is something people use sometimes.</dd>
    
    <dt>Markdown in HTML</dt>
    <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

# Horizontal Rule

Three or more ...

---

Hyphens

***

Asterisks

___

underscores

# Line Breaks

My basic recommendation for learning how line breaks work is to experiment and 
discover -- hit <Enter> once (i.e., insert one newline), then hit it twice 
(i.e., insert two newlines0, see what happens. You'll soon learn to get what you want. 
"Markdown Toggle" is your friend.

Here are some things to try out:

```
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraphs*.

This line is also a separate paragraph, but....
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraphs*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

# Youtube videos

They can't be added directly but you can add an image with a link to the video like this:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
