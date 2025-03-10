# Contributing

The Collaboration Campfires are a initiative of the 
[R Contribution Working Group][rcwg], which aims to foster
a larger, more diverse community of contributors to the open source R project.
We welcome contributions of all kinds:
new lessons,
fixes to existing material,
bug reports,
and reviews of proposed changes are all welcome.

## Contributor Agreement

By contributing,
you agree that we may redistribute your work under [our license](LICENSE.md).
In exchange,
we will address your issues and/or assess your change proposal as promptly as we can.
All contributors
agree to abide by our [code of conduct](CONDUCT.md).

## How to Contribute

The easiest way to get started is to file an issue
to tell us about a spelling mistake,
some awkward wording,
or a factual error.
This is a good way to introduce yourself
and to meet some of our community members.

1.  If you do not have a [GitHub][github] account, here are some other ways to contact us:
    - [Join the R-Devel Slack][slack] and comment on the #core-outreach channel.
    - [DM/mention the @R_Contributors Twitter account][twitter].
    - [Attend an R Contribution Working group event][events].

2.  If you have a [GitHub][github] account,
    or are willing to [create one][github-join],
    but do not know how to use Git,
    you can report problems or suggest improvements by [creating an issue][issues].
    This allows us to assign the item to someone
    and to respond to it in a threaded discussion.

3.  If you are comfortable with Git,
    and would like to add or change material,
    you can submit a pull request (PR).
    Instructions for doing this are [included below](#using-github).

## Where to Contribute

1.  If you wish to change this lesson,
    please work in <https://github.com/r-devel/r-bug-tracking-lesson>,
    which can be viewed at <https://contributor.r-project.org/r-bug-tracking-lesson/>.

2.  If you wish to change the template used for this lesson,
    please go to <https://github.com/carpentries/workbench-template-rmd>
    and check out their `CONTRIBUTING.md` file.

## What to Contribute

There are many ways to contribute,
from writing new exercises and improving existing ones
to updating or filling in the documentation
and submitting [bug reports][issues]
about things that don't work, aren't clear, or are missing.
If you are looking for ideas,
please see [the list of issues for this repository][issues].

Comments on issues and reviews of pull requests are just as welcome:
we are smarter together than we are on our own.
Reviews from novices and newcomers are particularly valuable:
it's easy for people who are familiar with the material
to forget how impenetrable some of it can be,
so fresh eyes are always welcome.

## What *Not* to Contribute

Our lessons already contain more material than we can cover in a typical workshop,
so we are usually *not* looking for more concepts or tools to add to them.
As a rule,
if you want to introduce a new idea,
you must (a) estimate how long it will take to teach
and (b) explain what you would take out to make room for it.
The first encourages contributors to be honest about requirements;
the second, to think hard about priorities.

We are also not looking for exercises or other material that only run on one platform.
Our workshops typically contain a mixture of Windows, macOS, and Linux users;
in order to be usable,
our lessons must run equally well on all three.

## Using GitHub

If you choose to contribute via GitHub,
you may want to look at
[How to Contribute to an Open Source Project on GitHub][how-contribute].
In brief:

1.  The source files for the lesson are on the `main` branch of the repository,
    Please create all branches from that,
    and merge [this repository][repo]'s `main` branch into your `main` branch
    before starting work.
    The published copy of the lesson is in the `gh-pages` branch of the repository
    - this is generated automatically by GitHub actions 
    when the source files on the `main` branch are updated.
    Please do *not* work directly in your `main` branch,
    since that will make it difficult for you to work on other contributions.

2.  We use [GitHub flow][github-flow] to manage changes:
    1.  Create a new branch in your copy of this repository for each significant change.
    2.  Commit the change in that branch.
    3.  Push that branch to your fork of this repository on GitHub.
    4.  Submit a pull request from that branch to [this repository][repo].
    5.  If you receive feedback,
        make changes on your copy and push to your branch on GitHub:
        the pull request will update automatically.

Each lesson has two maintainers who review issues and pull requests
or encourage others to do so.
The maintainers are community volunteers,
and have final say over what gets merged into the lesson.

## Other Resources

General discussion of outreach activities related to the R project 
happen on the [R-Devel Slack][slack] #core-outreach channel and at
the [R Contribution Working Group][rcwg] meetings,
which everyone is welcome to join.

## Acknowledgements

This contributing guide was adpated from the CONTRIBUTING.md file of 
[The Carpentries Workbench][carpentries-workbench] template, which is 
Copyright © [Software Carpentry][swc-site] 
under a [CC BY 4.0][cc-by-human] license. 

[cc-by-human]: https://creativecommons.org/licenses/by/4.0/
[events]: https://contributor.r-project.org/events/
[github]: http://github.com
[github-flow]: https://guides.github.com/introduction/flow/
[github-join]: https://github.com/join
[how-contribute]: https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github
[issues]: issues/
[rcwg]: https://contributor.r-project.org/working-group
[repo]: /
[slack]: https://contributor.r-project.org/slack
[swc-site]: http://software-carpentry.org/
[twitter]: https://twitter.com/R_Contributors

