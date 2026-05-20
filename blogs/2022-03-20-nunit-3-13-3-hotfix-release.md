---
title: "NUnit 3.13.3 Hotfix Release"
url: "https://nunit.org/news/update/nunit/2022/03/20/nunit-3.13.3.html"
date: "Sun, 20 Mar 2022 12:00:00 +0000"
author: ""
feed_url: "https://nunit.org/feed"
---
This release includes several performance enhancements. @lahma provided a massive speed improvement for large parametrized test suites. In addition, equivalency tests with large unsortable collections run faster by determining if the collections are sortable before attempting to sort them. We’ve added several fixes for .NET 6.0 and we’ve stopped testing NUnit against .NET Core 2.1 which is now out of support.
