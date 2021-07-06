---
layout: article
title:  "Markdown: How to Escape Special Characters"
author: Staff
date:   2021-06-23
image-name: "Image by Annie Spratt (Unsplash.com)"
image-location: "/assets/images/waves-of-grain.jpg"
---

#### 4.16 Escape special characters

Some characters have special meanings in the Markdown syntax. If you want these
characters verbatim, you have to escape them. For<!--more--> example, a pair of underscores
surrounding text usually makes the text italic. You need to escape the
underscores if you want verbatim underscores instead of italic text. The way to
escape a special character is to add a backslash before it, e.g., ```I do not want
\_italic text\_ here```. Similarly, if # does not indicate a section heading, you
may write ```\# This is not a heading```.

As mentioned in Section 4.12, a sequence of whitespaces will be rendered as a
single regular space. If you want to render the sequence of spaces literally,
you need to escape each of them, e.g., ```keep the social \ \ \ distance```. When a
space is escaped, it is converted to a “non-breaking space,” which means the
line will not be wrapped at this space, e.g., ```Mr.\ Dervieux```.
