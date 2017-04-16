---
layout: post
title: Ruby is Complicated!
date: 2017-04-16
---

After putting it off for weeks I finally decided to install a [ruby](https://ruby-lang.org) development environment to run [Jekyll](https://jekyllrb.com) (the platform this site runs on) locally. What I learned is that working with ruby is complicated as hell! The language itself seems simple, but there are so many layers of complexity on top of the language itself. I had to:
- read multiple guides on [setting up a github.io site](https://jmcglone.com/guides/github-pages/)
- [install ruby](https://rubyinstaller.org)
- install the [ruby development kit](http://rubyinstaller.org/downloads/)
- create a "Gemfile"
- run some arbitrary shell commands
- finally run a local server to host this site
Happily I got it all done, but in the end I found out that the only reason github.io didn't like my site was the double right pointing angle bracket in the example blog post layout I got from the setup guide. All in all it was a good learning experience, but terrible user experience.