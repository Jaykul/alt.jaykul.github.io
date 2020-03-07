---
layout: post
title: How the developer's brain works
tags: [development, personal]
date: 2014-10-27 05:47:43 -04:00
---

1. I need to finish [the PoshCode module][1], so I start working on that ...
2. I realize the "Configuration" module that is inside PoshCode, is actually more important than PoshCode (that is, I think more developers will use it, because even PowerShellGet users need this)
3. I decide to separate the Configuration module project and fully test it.
4. I start writing tests for [the Configuration module][2] but remember that I hate RSpec syntax.
5. I fork [Pester], and add support for Gherkin and feature definition files
6. I return to development on the Configuration module, using it as a testbed for missing features in Pester's Gherkin support.
7. I finally finish the Pester Gherkin support and [get it accepted][4] to the Pester repository, feeling a great sense of accomplishment
8. The Pester team wants to refactor the main module to make new interfaces like Gherkin easier to write, but puts it on a back burner for the next release.
9. I set my project aside until they have time to work on the refactor, forgetting that the whole reason I was working on this was so I could finish PoshCode ...
10. I decide to write a blog post about it ...
11. I remember that I'm still using a Python static blog generator ...
12. I find [Rob Mensching's TinySite][5], but it's basically an abandoned prototype, and I think it's ridiculous that it uses json ...
13. I wonder if a static generator in .Net would be a good way to present on templating langauges for our local user group
14. I consider how nice it would be if the generators had PowerShell cmdlets instead of weird multi-command mode commands that don't actually shell
15. And two weeks later, I have a first draft version of [PowerSite][6], my very own [static blog engine][6], that works well enough to switch this blog over to it, and I can write that blog post...

## But I totally can't remember why I thought the Pester/Configuration/PoshCode thing was worth blogging about in the first place.

#### Oh, wait, what ever happened to that Configuration module? Did I finish that?

###### Ohhhhh... shoot! The PoshCode module was supposed to be finished in August!

True story. This might be why God invented managers.


[1]: https://GitHub.com/PoshCode/PoshCode
[2]: https://GitHub.com/PoshCode/Configuration
[3]: https://GitHub.com/Pester/Pester
[4]: https://GitHub.com/Pester/Pester/tree/Gherkin
[5]: https://github.com/robmen/tinysite
[6]: https://github.com/Jaykul/PowerSite
