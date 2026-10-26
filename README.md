# NUnit (nunit)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

NUnit is a unit-testing framework for all .NET languages. Initially ported from JUnit, the current production release has been completely rewritten with many new features and support for a wide range of .NET platforms. NUnit is a software testing framework, not a remote HTTP API service.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/nunit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 1st-Party

## Tags:

 - .NET, C#, Framework, Open Source, TDD, Testing, Unit Testing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### NUnit Framework API
The core NUnit testing framework programming API for writing and executing unit tests in .NET applications. Provides assertions, attributes, and lifecycle hooks consumed via the NUnit NuGet package.

**Human URL:** [https://docs.nunit.org/](https://docs.nunit.org/)

#### Tags:
 - Assertions, Attributes, Testing

#### Properties
- [Documentation](https://docs.nunit.org/articles/nunit/intro.html)
- [Getting Started](https://docs.nunit.org/articles/nunit/getting-started.html)
- [Reference](https://docs.nunit.org/api/)
- [NuGet Package](https://www.nuget.org/packages/NUnit)
- [Source Code](https://github.com/nunit/nunit)

### NUnit Console Runner
Console runner for executing NUnit tests from the command line, enabling automation in build pipelines and CI/CD systems.

**Human URL:** [https://docs.nunit.org/articles/nunit/running-tests/Console-Runner.html](https://docs.nunit.org/articles/nunit/running-tests/Console-Runner.html)

#### Tags:
 - Console, Test Runner, CLI

#### Properties
- [Documentation](https://docs.nunit.org/articles/nunit/running-tests/Console-Runner.html)
- [Command Line Reference](https://docs.nunit.org/articles/nunit/running-tests/Console-Command-Line.html)
- [NuGet Package](https://www.nuget.org/packages/NUnit.ConsoleRunner)

### NUnit3 Test Adapter
Test adapter for running NUnit tests in Visual Studio, dotnet test, and other VSTest-compatible test runners.

**Human URL:** [https://docs.nunit.org/articles/vs-test-adapter/Index.html](https://docs.nunit.org/articles/vs-test-adapter/Index.html)

#### Tags:
 - Visual Studio, Test Adapter, VSTest

#### Properties
- [Documentation](https://docs.nunit.org/articles/vs-test-adapter/Index.html)
- [NuGet Package](https://www.nuget.org/packages/NUnit3TestAdapter)
- [Source Code](https://github.com/nunit/nunit3-vs-adapter)

### NUnit Analyzers
Roslyn-based analyzers for NUnit that detect common test authoring mistakes and suggest fixes at compile time.

**Human URL:** [https://docs.nunit.org/articles/nunit-analyzers/NUnit-Analyzers.html](https://docs.nunit.org/articles/nunit-analyzers/NUnit-Analyzers.html)

#### Tags:
 - Analyzers, Roslyn, Code Quality

#### Properties
- [Documentation](https://docs.nunit.org/articles/nunit-analyzers/NUnit-Analyzers.html)
- [NuGet Package](https://www.nuget.org/packages/NUnit.Analyzers)
- [Source Code](https://github.com/nunit/nunit.analyzers)

## Common Properties

- [Website](https://nunit.org)
- [Documentation](https://docs.nunit.org)
- [GitHub Organization](https://github.com/nunit)
- [Blog](https://nunit.org/news/)
- [Community](https://nunit.org/community/)
- [Change Log](https://docs.nunit.org/articles/nunit/release-notes/)
- [License](https://docs.nunit.org/articles/nunit/license.html)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
