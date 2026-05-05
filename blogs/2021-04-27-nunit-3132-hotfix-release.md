---
title: "NUnit 3.13.2 Hotfix Release"
url: "https://nunit.org/news/update/nunit/2021/04/27/nunit-3.13.2.html"
date: "2021-04-27T12:00:00+00:00"
author: ""
feed_url: "https://nunit.org/rss.xml"
---
<p>This release fixes a new issue with the <code class="language-plaintext highlighter-rouge">FixtureLifeCycle</code> attribute where <code class="language-plaintext highlighter-rouge">IDisposable</code> test fixtures were not being disposed properly. As always, <a href="https://github.com/gleb-osokin">@gleb-osokin</a> has been a great help with this new feature.</p>

<p>It also fixes a long-standing performance issue with <code class="language-plaintext highlighter-rouge">CollectionAssert.AreEquivalent</code> and the <code class="language-plaintext highlighter-rouge">CollectionEquivalentConstraint</code> when comparing large collections. The deep comparison that NUnit performs on the two collections will always have a worst case bound of O(n^2) but we have optimized it so that the majority of use cases will be closer to O(n).</p>

<p>We’ve also made significant optimizations to the OR filters for selecting tests using their full name. This dramatically improves test performance for large code bases that use <code class="language-plaintext highlighter-rouge">dotnet test</code>. Thanks to <a href="https://github.com/pakrym">@pakrym</a> for his help with this.</p>

<p>See the <a href="https://docs.nunit.org/articles/nunit/release-notes/framework.html">release notes</a> for more information.</p>
