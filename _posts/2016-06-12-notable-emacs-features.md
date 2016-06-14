---
layout: post
title: "Notable Emacs Features"
date: 2016-06-12
excerpt: "A tour of some of the best features of emacs"
tags: [emacs, tech]
comments: true
---

## An introduction

Hey all,

This is an attempt to make a post about my emacs setup and why I (a
vim guy) now use emacs.  Has that been done before, by someone much
better with emacs than I am in a talk format?  Yes, but ignore that
for a second.  As someone who really does think emacs-style chording
isn't good for editing (and prefers modal editing à la vim) I still
think there's potential in the "editor" we call emacs.

## First, why emacs?

So, my real reasons for switching to emacs were twofold.  Let's look
into them:

### Org-mode

This was the first, and biggest, reason I made the jump to emacs.
[Org-mode][1] is an outline system, a todo-management program, a
LaTeX-exporter, a scheduling and agenda-making utility, a spreadsheet
editor, a blog-posting and wiki-editing utility, and likely a half
dozen other things I can't remember off the top of my head.

### Lisp interaction

This came about more recently, and has been an interesting experience.
I've been writing a bit of Common Lisp lately (in the process of
working through [Practical Common Lisp]) which has led me to emacs as
the code editor of choice.  The options aren't terribly numerous for a
good lisp development environment, where the REPL and the editor are
integrated.  Using my previous love, vim, to edit Lisp seemed like the
support was... weaker, and clumsier.

## So, how?

Well, it's been a fun transition.  Since I come from vim, the biggest
help for me has been [evil-mode][3].  Evil is a very good (from an
admittedly not-terribly-experienced-with-vim perspective) vi
functionality emulator that manages to avoid clashing much with emacs'
standard features.  Using this, I've found it fairly easy to adjust to
emacs and appreciate it for its impressive functionality.

[1]: http://orgmode.org/worg/
[2]: http://www.gigamonkeys.com/book/
[3]: https://www.emacswiki.org/emacs/Evil
