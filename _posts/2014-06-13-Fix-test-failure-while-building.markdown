---
layout: post
title: Fix test failure while building
category: BugFix

excerpt: Set fopen-fail timeout to 300

---

Update the timeout for the fopen fail test to 300 seconds, since the
test was taking longer than the default 5 seconds to run. The root
cause was discovered by Víctor M. Jáquez L. (Closes: #748657)
See [detils here.](https://github.com/srivasta/debian.packaging.make/commit/c1761a68627209c60ce54736e72da5a9492f1b4e)
