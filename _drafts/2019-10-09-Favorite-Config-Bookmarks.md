---
title: "My favorite config references"
category: links
tags:
  - emacs
  - devops
  - literate programming
  - magit
  - projectile
  - helm
  - spacemacs
---

I'm an odd sort. Stuff like [literate DevOps in emacs][litdev] really
excites me.  So do various entire machine [configurations][motard].  Below are
some interesting links and ramblings of mine.

{% include video id="dljNabciEGg" provider="youtube" %}

# Emacs
Customizing my environment is something that I take fairly seriously - from both
a productivity standpoint, and a consistency standpoint...  And I also just like
`emacs` I guess.  `org-mode` was the thing that started to hook me, but then
there are other packages and reasons that I've become further involved.

While this may seem rambling at first, I plan to cover quite a few links that
are to both configurations and tools I've found to be incredibly useful.

## Several Amazing emacs demos

I actually have many places that my current emacs configuration has been
inspired from over the years...  a few of these demonstrations inspired me

* [magit - a visual walk-through][magit] - My favorite git integration of all
  time.
  
* [A Package in a league of it's own: Helm][helm-intro] - Another one of my
  favorite packages - [`helm`][helm] - and it's even got some great animated
  demonstrations of the usage.
  
* [Exploring large projects with Projectile and Helm
  Projectile][helm-projectile] - This was yet another set of animations that I
  could barely wrap my head around at the time.  [`projectile`][projectile] is
  really neat.  Little did I know the joy that
  some of the other packages would still bring me.

* [Peek Definition in emacs][peek-definition]: Just to prove that you can do
  some pretty amazing visual studio like things in emacs, see the above link of
  peek definition at work.


## emacs configuration inspiration

* [Organize your life with org mode][norang] - This was probably the first emacs
  configuration that actually inspired me.
  
* For your truely in-depth emacs config, see [novoid][novoid].  This may be the
  largest emacs configuration I've seen in a single org file.
  
* [Purcell's .emacs.d][purcell]: While this one doesn't use literate
  programming, it's still yet another interesting configuration
  

## Completely different emacs environments

This sort of discussion wouldn't be complete without a little about my latest
obsession, [Spacemacs][spacemacs] or [Prelude][prelude] which both provide (very
different) sorts of starter environments.

## Building C# Code

Thanks to [omnisharp][os] ([demo][omnisharp-demo]) as well as a couple of other packages, I've been able to
move some of my C# development to emacs.


[litdev]: http://www.howardism.org/Technical/Emacs/literate-devops.html
[norang]: http://doc.norang.ca/org-mode
[helm-intro]: http://tuhdo.github.io/helm-intro.html
[helm-projectile]: http://tuhdo.github.io/helm-projectile.html
[peek-definition]: http://tuhdo.github.io/emacs-frame-peek.html
[purcell]: https://github.com/purcell/emacs.d
[spacemacs]: https://github.com/syl20bnr/spacemacs/blob/master/README.md
[helm]: https://emacs-helm.github.io/helm/
[projectile]: https://www.projectile.mx/en/latest/
[novoid]: https://github.com/novoid/dot-emacs/blob/master/config.org
[prelude]: https://prelude.emacsredux.com/en/latest/
[magit]: https://magit.vc/screenshots/
[omnisharp-demo]: https://github.com/nosami/omnisharp-demo
[motard]: https://github.com/patrick-motard/dotfiles/wiki
[os]: http://www.omnisharp.net
