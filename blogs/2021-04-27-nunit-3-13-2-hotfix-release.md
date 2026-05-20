---
title: "NUnit 3.13.2 Hotfix Release"
url: "https://nunit.org/news/update/nunit/2021/04/27/nunit-3.13.2.html"
date: "Tue, 27 Apr 2021 12:00:00 +0000"
author: ""
feed_url: "https://nunit.org/feed"
---
This release fixes a new issue with the FixtureLifeCycle attribute where IDisposable test fixtures were not being disposed properly. As always, @gleb-osokin has been a great help with this new feature. It also fixes a long-standing performance issue with CollectionAssert.AreEquivalent and the CollectionEquivalentConstraint when comparing large collections.
