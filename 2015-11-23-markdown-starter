# MarkDown

1. [Overview](#overview)
    * [Philosophy](#philosophy)
    * [Inline HTML](#html)
(#autoescape)
1. [Block Elements](#block)
    * [Paragraphs and Line Breaks](#p)
    * [Headers](#header)
    * [Blockquotes](#blockquote)
    * [Lists](#list)
    * [Code Blocks](#precode)
    * [Horizontal Rules](#hr)
1. [Span Elements](#span)
    * [Links](#link)
    * [Emphasis](#em)
    * [Code](#code)
    * [Images](#img)
1. [Miscellaneous](#misc)
    * [Automatic Links](#autolink)
    * [Backslash Escapes](#backslash)
   

## Overview

#### Philosophy

Markdown is intented to be as easy-to-read and easy-to-write as is feasible.

A markdown-formatted document should be like plain text, without looking like it's been marked up with tags or formatting instructions.

Markdown syntax is comprised entirely of puncutation characters, which puncutation characters have been carefully chosen so as to look like what they mean. E.g., asterisks around a word actually look like *emphasis*.

#### Inline HTML
For any markup that is not covered by Markdown's syntax, you simply use HTML itself. There's no need to preface it or delimit is to indicate that you're swicthing from Markdown to HTML. You just use the tags.

For example, to add a HTML table to Markdown article:

- - -
This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.
- - -

## Block Elements

#### Paragraphs and Line Breaks

A paragraph is just consecutive lines of text, seperated by one or more blank lines. Normal paragraph shouldn't be indented by space or tabs.

Markdown doesn't traslate every line break into a `</br>` tag. In Markdown, you end a line with two or more spaces, then type return.

#### Headers

Markdown supports two styles of headers, **Setext** and **atx**.

Setext style headers are underlined with equal signs ( for fisrt-level headers ) and dashes ( for second-level ). For examples:

- - - - - - - - - - - - 
This is an H1.
=============
This is an H2.
----------------
- - - - - - - - - - - -

Atx style headers uses 1-6 hashes at the start of the line, corresponding to header level 1-6. For example:

- - - - - - - - - - - - 
# This is an H1
## This is an H2
###### This is an H6
- - - - - - - - - - - - 

#### Blockquotes

Markdown uses email-style > character for blockquoting. You and put a > before every line.

>This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
>consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
>
>Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
>id sem consectetuer libero luctus adipiscing.

Markdown allows you to be lazy and only put the > before first line of every hard-wrapped paragraph.

>This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
 consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.

>Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
 id sem consectetuer libero luctus adipiscing.
 
Blockquotes can be nested.

> This is the first level of quoting.
> 
>> This is nested quoting.
>
> Back to the first level of quoting.

#### Lists

Markdown supports numbered and unnumbered lists.

Unnumbered lists uses asterisks, hyphens and pluses, interchangably.

*   Red
*   Green
*   Blue

is equivalent to:

+   Red
+   Green
+   Blue

and:

-   Red
-   Green
-   Blue

numbered lists use numbers followed by a period:

1. Red
2. Green
3. Blue

#### Code Blocks

To produce a code block in Markdown, simply indent every line of code with four spaces or a tab. For example:

This is a normal paragraph.

	This is a code block.

#### Horizontal Rules

You can produce a horizontal rule tag by putting three or more asterisks, hypens or underscores on a line by themselves.

* * *

***

*****

- - -

## Span Elements

#### Links

Markdown supports two style of links: inline and reference.

Inline links:
[example](http://example.com)

[`example`](http://example.com)

If refering a local resource on the same server, you can use relative path.

See my [about](/about/) page for detail.

reference links:

This is [an example][id] of reference link.
[id]: http://example.com

#### Emphasis

Markdown uses asterisks and underscore as indicators of emphasis.

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

#### Code

To indicate a span of code, wrap it with backtick quotes.

Use the `printf()` function

#### Images

Inline image syntax looks like this:

![cat](http://c.hiphotos.baidu.com/baike/w%3D268/sign=1fbe081cd7c8a786be2a4d085f08c9c7/38dbb6fd5266d016338536ce912bd40734fa35b3.jpg)

## Miscellaneous

#### Automatic Links

Markdown supports a shortcut style for creating automatic links for URL and email addresses.

<http://example.com/>

<address@example.com>

#### Backslash Escapes

Markdown allows backslach escape to generate literal characters which would otherwise have special meaning in Markdown's formatting syntax.

