---
layout: default
title: /index.fun
description: Homepage
metasub: news
noToc: false
tags:
- xw3
- project
- cgi
- static
- jekyll
_description: The programming language that just makes fun!
noComments: true
---

<div class="post">
  <header class="post-header">
    <h1 class="post-title" id="terminal">{{ site.title }} {{ page.title }}</h1>
    <p style="padding: 0px 0px 0px 0px;">{{ site.subtitle }}</p>
  </header>
</div>

## What is Fun?

Fun is an experiment, just for fun, but Fun works!

Fun is a highly strict programming language, but also highly simple. It looks like Python (My favorite language), but there are differences.

Influenced by **[Bash](https://www.gnu.org/software/bash/){:class="ext"}**, **[C](https://en.wikipedia.org/wiki/The_C_Programming_Language){:class="ext"}**, **[Lua](https://www.lua.org/){:class="ext"}**, PHP, **[Python](https://www.python.org/){:class="ext"}**, and Rust (Most influences came from linked languages).

Fun is and will ever be 100% free under the terms of the [Apache-2.0 License](https://opensource.org/license/apache-2-0){:class="ext"}.

## Idea

- Simplicity
- Consistency
- Joy in coding
- Fun!

## Characteristics

- Dynamic and optionally statically typed
- Type safety
- Written in C (C99) and Fun
- Internal libs are written with no_camel_case even when written in Fun, except class names
- Only a minimal function set is written in C, and most other core functions and libraries are implemented in Fun

## The Fun Manifesto

Fun is a programming language built on a simple idea:
Coding should be enjoyable, elegant, and consistent.

### Philosophy

- **Fun is Fun**<br>
  Programming should spark creativity, not frustration. Code in Fun feels light, playful, and rewarding.
- **Fun Uses Nothing**<br>
  Minimalism is power. No unnecessary features, no endless syntax variations, no formatting debates. Just clean, uniform code.
- **Indentation is Truth**<br>
  Two spaces, always. No tabs, no four-space wars. Code should look the same everywhere, from your laptop to /usr/bin/fun.
- **One Way to Do It**<br>
  No clutter, no 15 ways of writing the same thing. Simplicity means clarity.
- **Hackable by Nature**<br>
  Fun should be small and embeddable, like Lua. Easy to understand, extend, and tinker with — true to the hacker spirit.
- **Beautiful Defaults**<br>
  A language that doesn’t need linters, formatters, or style guides. Beauty is built in.

## The Community

Fun is not about being the fastest or the most feature-rich. It’s about sharing joy in coding. The community should be:

- Respectful
- Curious
- Creative

Like the name says: Fun Unites Nerds.

Please visit the [Fun Community Page](https://fun-lang.xyz/community/) to get in touch.

## The Goal

A language that feels like home for developers who:

- Love minimal, elegant tools
- Believe consistency is freedom
- Want to write code that looks good and feels good

Fun may not change the world — but it will make programming a little more fun.

## Features

### Core

- functions/classes/objects
- if/else if/else
- try/catch/finally

### Lib

...

### Extensions

- [CGI](https://en.wikipedia.org/wiki/Common_Gateway_Interface){:class="ext"} support builtin using [kcgi](https://kristaps.bsd.lv/kcgi/){:class="ext"} (optional) <span style="color:red;font-weight:bold;">&#9744;</span>
- [cURL](https://curl.se/){:class="ext"} support builtin using [libcurl](https://curl.se/libcurl/){:class="ext"} (optional) <span style="color:green;font-weight:bold;">&#9745;</span>
- [INI](https://en.wikipedia.org/wiki/INI_file){:class="ext"} support builtin using [iniparser](https://gitlab.com/iniparser/iniparser/){:class="ext"} (optional) <span style="color:red;font-weight:bold;">&#9744;</span>
- [JSON](https://www.json.org/){:class="ext"} support builtin using [json-c](https://github.com/json-c/json-c){:class="ext"} (optional) <span style="color:green;font-weight:bold;">&#9745;</span>
- [libSQL](https://github.com/tursodatabase/libsql){:class="ext"} support builtin as a compatible alternative to SQLite (optional) <span style="color:green;font-weight:bold;">&#9745;</span>
- [PCRE2](https://pcre2project.github.io/pcre2/){:class="ext"} support builtin for Perl-Compatible Regular Expressions (optional) <span style="color:green;font-weight:bold;">&#9745;</span>
- [PCSC](https://pcscworkgroup.com/){:class="ext"} smart card support builtin using [PCSC lite](https://pcsclite.apdu.fr/){:class="ext"} (optional) <span style="color:green;font-weight:bold;">&#9745;</span>
- [SQLite](https://sqlite.org/){:class="ext"} support builtin (optional) <span style="color:green;font-weight:bold;">&#9745;</span>
- [Tk](https://www.tcl-lang.org/){:class="ext"} support builtin for GUI application development (optional) <span style="color:red;font-weight:bold;">&#9744;</span>
- [TOML](https://en.wikipedia.org/wiki/TOML){:class="ext"} support builtin using [tomlc99](https://github.com/cktan/tomlc99){:class="ext"} (optional) <span style="color:red;font-weight:bold;">&#9744;</span>
- [XML](https://www.w3.org/XML/){:class="ext"} support builtin using [libxml2](https://gitlab.gnome.org/GNOME/libxml2/-/wikis/home){:class="ext"} (optional) <span style="color:red;font-weight:bold;">&#9744;</span>
- [YAML](https://yaml.org/){:class="ext"} support builtin using [libfyaml](https://github.com/pantoniou/libfyaml){:class="ext"} (optional) <span style="color:red;font-weight:bold;">&#9744;</span>

<span style="color:green;font-weight:bold;">&#9745;</span> = Done / <span style="color:red;font-weight:bold;">&#9744;</span> = Planned or in progress.

Note: Not all of the above features will be implemented. Those who are marked "Done" will probaly remain in Fun, but I don't know actually... ;)

There are some libs written in Fun available in the [./lib/](https://git.xw3.org/fun/fun/src/branch/main/lib){:class="ext"} diretory. In the future most Fun enhancements should be written in Fun itself.

## Documentation

This is actually a work in progress...

Current documentation is only found in the [Fun Handbook](https://git.xw3.org/fun/fun/src/branch/main/docs/handbook.md){:class="ext"}.

In the [./examples/](https://git.xw3.org/fun/fun/src/branch/main/examples){:class="ext"} directory should be an example of most Fun features.

Fun internals are found directly in the [./src/](https://git.xw3.org/fun/fun/src/branch/main/src){:class="ext"} diretory. Fun [Opcodes](https://en.wikipedia.org/wiki/Opcode){:class="ext"} are found in [./src/vm/](https://git.xw3.org/fun/fun/src/branch/main/src/vm){:class="ext"}.

Since things are actually changing sometimes, I will not write the documentation for this as of now.

Complete API documentation will follow.

## Code

 - [https://git.xw3.org/fun/fun/](https://git.xw3.org/fun/fun/){:class="git"}

