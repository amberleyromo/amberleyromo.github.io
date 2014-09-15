---
layout: post
title: Bash profile death.
---

**TIL:** 

Today my comp froze, and when I restarted, none of my commands were available in the terminal. I'm not exactly sure what happened still, but somehow forcing the restart affected my .bash_profile. I googled until I found [this stackoverflow post](http://stackoverflow.com/questions/21067625/how-to-restore-bash-profile-on-a-mac-none-of-my-unix-terminal-are-working). While I still don't completely understand the PATH variable, this line allowed me to access vim by resetting.

`export PATH=/bin:/usr/bin:/usr/local/bin`

And voila, I could access .bash_profile via vim. 

`vi ~/.bash_profile` 

I managed to get to a point where it prompted me to choose a version. Somehow the freezing/restart created two conflicting versions? Either way, I'm back up and running, and didn't lose any of my bash settings. (Which is great, since most of them were blessed additions by friends who know what they're actually doing).

I also added an archive page listing to this site, snagging code from [this post from Joshua Lande](http://joshualande.com/jekyll-github-pages-poole/). Next up, learn more about Liquid templating.

