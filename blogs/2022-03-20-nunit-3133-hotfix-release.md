---
title: "NUnit 3.13.3 Hotfix Release"
url: "https://nunit.org/news/update/nunit/2022/03/20/nunit-3.13.3.html"
date: "2022-03-20T12:00:00+00:00"
author: ""
feed_url: "https://nunit.org/rss.xml"
---
<p>This release includes several performance enhancements. <a href="https://github.com/lahma">@lahma</a> provided a massive speed improvement for large parametrized test suites. In addition, equivalency tests with large unsortable collections run faster by determining if the collections are sortable before attempting to sort them.</p>

<p>We’ve added several fixes for .NET 6.0 and we’ve stopped testing NUnit against .NET Core 2.1 which is now out of support.</p>

<p>There are also several fixes for the new <code class="language-plaintext highlighter-rouge">FixtureLifeCycle</code> feature and other smaller bug fixes and performance improvements.</p>

<p>See the <a href="https://docs.nunit.org/articles/nunit/release-notes/framework.html">release notes</a> for more information.</p>
