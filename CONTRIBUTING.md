# Contributing to this project

We're always seeking:

* user feedback
* help from  volunteers
* community leaders

If you haven't already, come introduce yourself on [Discord].

## Tasks

An exhaustive task list can be found on our [documentation] site, but the
following tasks need regular attention:

* [Documentation]
* [Features]
* [General tasks]
* [Testing]
* [Bugs]
* [Github Moderation]
* [Discord Moderation]

## Streamlining Collaboration

We strive to streamline our support and collaboration channels so that:

* We can engage with our community to a high degree of consistency
* We can track our support/feedback and find patterns to help us improve
* Moderators/team leaders/developers can:

  * focus on the problems at hand
  * in a single location
  * instead of being spread thin between services

## Collaborative Development Tools
<!-- (provide linked reasoning for each) -->
As mentioned above, we take great care in solving problems by making the most of
a limited toolset including:

1. On-going work: git/github
1. Long-term documentation/support: readthedocs
1. Real-time community engagement: discord

## Development resources

<!-- (link directly to each resource on github/services above) -->
* [Development process]
* [Development status]
* [Roadmap]
* [Discord Channel][Discord]
  * [How to Setup Discord Channels](https://support.discordapp.com/hc/en-us/articles/115001580171-Channel-Categories-101)

<!--
  * [OpenGovernment for Developers](http://opengovernment.org/pages/developer)
    tells you where we are,
  * [Our roadmap](http://opengovernment.org/pages/wish-list) is the 10k foot
    view of where we're going, and
  * [Pivotal Tracker](http://pivotaltracker.com/projects/64842) is our
    day-to-day project management space.
  * Mailing list: Join our [developer
    list](http://groups.google.com/group/opengovernment/)
  * Bugs?
    [Lighthouse](https://participatorypolitics.lighthouseapp.com/projects/
    47665-opengovernment/overview)
    is where to report them
  * IRC: chat.freenode.net channel
    [#opengovernment](irc://chat.freenode.net/opengovernment). We're usually
    there during business hours.
-->

<!--
We have a handful of Cucumber features, but most of our testbed consists of
RSpec examples. Please write RSpec examples for new code you create. -->

## Submitting Bug Reports and Feature Requests

* Bugs can be reported [here][Bugs] using the [Bug Report Template].
* Bugs can be requested [here][Features] using the [Feature Request Template].

## Submitting Changes

<!--(from here: https://github.com/stephencelis/ghi)-->
Once you have an idea of what you want to do, there is a section in the
[documentation] to provide more detailed information but the basic steps are as
follows:

1. Fork this repo
1. Do your work
1. Make your changes
1. Run your build process
1. Test - make sure your changes work
1. Open a pull request!

 Please review the following components for more detail on how to submit changes.

### Commit Messages

When writing commits:

1. Always write a clear log message for your commits including a clear list of
   work you've done.
1. Make sure all of your commits are atomic (one feature per commit).
1. One-line messages are fine for small changes, but bigger changes should look
   like this:

```BASH
$ git commit -m "A brief summary of the commit
>
> A paragraph describing what changed and its impact."
```

### Testing

Testing details forthcoming. Ideal pull requests include [Testing Framework]
examples. Our goal is 100% test coverage.

### Coding Conventions

Start reading our code and you'll notice most of the following. We optimize for readability:

* All Markdown files use extension .md
* Markdown uses Github Flavored Markdown [GFM] which is based on the [CommonMark
  Spec].
* Non-Markdown files indent using two spaces (soft tabs)
* We avoid logic in views, putting HTML generators into helpers
* We ALWAYS put spaces after list items and method parameters (`[1, 2, 3]`,
  not `[1,2,3]`), around operators (`x += 1`, not `x+=1`), and around hash
  arrows.
* This is open source software. Consider the people who will read your code,
  and make it look nice for them. It's sort of like driving a car: Perhaps you
  love doing donuts when you're alone, but with passengers the goal is to make
  the ride as smooth as possible.
* So that we can consistently serve images from a CDN, always use image_path
  or image_tag when referring to images. Never prepend "/images/" when using
  image_path or image_tag.
* Also for the CDN, always use cwd-relative paths rather than root-relative
  paths in image URLs in any CSS. So instead of url('/images/blah.gif'), use
  url('../images/blah.gif').

### Pull requests

Once all of the above is completed, you can submit a [Github Pull
Request](http://help.github.com/pull-requests/). A team leader will issue or
delegate a reviewer and comment with any questions/updates/etc.

## Code of Conduct

Please note that this project is released with a Contributor Code of Conduct
viewable at [CODE_OF_CONDUCT.md]. By participating in this project you agree to
abide by its terms.

## Leaders & Moderators

We need help writing code, tests, documentation, and moderating user
comments/chatrooms. If you would like to be responsible for managing some aspect
of this project, please  [submit a leadership inquiry].

***

## Legal

The nature of open source software is complex. So too are the legal implications
thereof, especially with the international laws like GDPR. Thankfully, there is
a fair degree of standardization, and numerous resources to help us make
meaningful, simple, and quick decisions.

### Contributors' Legal Requirements

This project DOES/DOES NOT require legal documentation, signatures, etcetera
from its contributors.

### License

This project is licensed under the MIT [LICENSE].

### License Review

All dependencies used in this project have been reviewed and are compatible with
the MIT License, as defined in our [LICENSE].

### Metrics/Analytics

This project USES XXX/DOES NOT USE software to collect anonymous information
about users and their use patterns. For information on how to integrate these
tools or access statistics, please reference:

* <https://developers.google.com/analytics/devguides/collection/protocol/v1/parameters>
* <https://opensource.guide/metrics/>

### Legal Resources for Open Source Projects

* [Open Source Guide - Legal]
* [Software Freedom FOSS Primer]
* [Corporate Open Source Compliance]

***

Sarandi Klikizos, Author - Project Name List any notable Core Team,
Contributors, Committers, Maintainers, etc. If this section exceeds a handful,
create a dedicated location to document.

***

## Donations & Monetary Contributions

We currently ARE/ARE NOT accepting money because XXX.

[Bug Report Template]: .github/ISSUE_TEMPLATE/bug_report.md

[Bugs]: https://github.com/user/repo/issues?q=is%3Aissue+is%3Aopen+label%3Abug

[CODE_OF_CONDUCT.md]: CODE_OF_CONDUCT.md

[CommonMark Spec]: http://spec.commonmark.org/

[Corporate Open Source Compliance]: https://www.linuxfoundation.org/blog/2015/06/why-companies-that-use-open-source-need-a-compliance-program/

[Development process]: readthedocs.com/user/repo/development-process

[Development status]: readthedocs.com/user/repo/development-status

[Discord]: [discordapp.com/channels/###/]

[Discord Moderation]: readthedocs.com/user/repo/moderation-discord

[Documentation]: readthedocs.com/user/repo

[Feature Request Template]: .github/ISSUE_TEMPLATE/feature_request.md

[Features]: https://github.com/user/repo/issues?q=is%3Aissue+is%3Aopen+label%3Afeature

[General tasks]: https://github.com/user/repo/issues?q=is%3Aissue+is%3Aopen+label%3Atask

[GFM]: https://github.github.com/gfm/

[Github Moderation]: readthedocs.com/user/repo/moderation-github

[GitHub Pull Request]: https://github.com/my/project/pull/new/master

[LICENSE]: LICENSE

[LICENSE.md]: LICENSE

[Open Source Guide]: https://opensource.guide/

[Open Source Guide - Legal]: https://opensource.guide/legal/

[Roadmap]: readthedocs.com/user/repo/roadmap

[Software Freedom FOSS Primer]: https://www.softwarefreedom.org/resources/2008/foss-primer.html

[submit a leadership inquiry]: readthedocs.com/user/repo/leadership

[Testing]: readthedocs.com/user/repo/testing

[Testing Framework]: https://jestjs.io/
