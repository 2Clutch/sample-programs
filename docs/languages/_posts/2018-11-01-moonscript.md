---
title: The MoonScript Programming Language
layout: default
last-modified: 2018-11-05
tags: [moonscript]
authors:
  - bassem_mohamed
---

According to [MoonScript.org][1], MoonScript is a dynamic scripting language that
compiles into Lua. What is Lua? Lua is a powerful, efficient, lightweight,
embeddable scripting language. It supports procedural programming, object-oriented
programming, functional programming, data-driven programming, and data description.

Back to MoonScript, it gives you the full power of Lua while providing a clean
easy syntax without the keyword noise typically seen in a Lua script. MoonScript
can either be compiled into Lua, or it can be dynamically compiled and run using
the moonloader.

How did MoonScript start you may ask? Well, its author [Leaf Corcoran][2] built
MoonScript, started building games with MoonScript, added them to [itch.io][3]—an
online platform for indie games which is also built with MoonScript—then
generalized the code base to a general purpose web framework with both
MoonScript and Lua APIs called Lapis.[^1]

## Articles

{% include article_list.md collection=site.tags.moonscript %}

---

#### References

[^1]: B. Mohamed, “Hello World in MoonScript,” The Renegade Coder, 02-Sep-2018. [Online]. Available: <https://therenegadecoder.com/code/hello-world-in-moonscript/>. [Accessed: 31-Oct-2018].

[1]: https://moonscript.org/
[2]: https://github.com/leafo
[3]: http://itch.io/
