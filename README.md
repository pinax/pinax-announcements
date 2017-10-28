![](http://pinaxproject.com/pinax-design/patches/pinax-announcements.svg)

# Pinax Announcements

[![](https://img.shields.io/pypi/v/pinax-announcements.svg)](https://pypi.python.org/pypi/pinax-announcements/)
[![](https://img.shields.io/badge/license-MIT-blue.svg)](https://pypi.python.org/pypi/pinax-announcements/)

[![CircleCi](https://img.shields.io/circleci/project/github/pinax/pinax-announcements.svg)](https://circleci.com/gh/pinax/pinax-announcements)
[![Codecov](https://img.shields.io/codecov/c/github/pinax/pinax-announcements.svg)](https://codecov.io/gh/pinax/pinax-announcements)
![](https://img.shields.io/github/contributors/pinax/pinax-announcements.svg)
![](https://img.shields.io/github/issues-pr/pinax/pinax-announcements.svg)
![](https://img.shields.io/github/issues-pr-closed/pinax/pinax-announcements.svg)

[![](http://slack.pinaxproject.com/badge.svg)](http://slack.pinaxproject.com/)

## Pinax

[Pinax](http://pinaxproject.com/pinax/) is an open-source platform built on the
Django Web Framework. It is an ecosystem of reusable Django apps, themes, and
starter project templates.

This app is part of the Pinax ecosystem and is designed for use both with and
independently of other Pinax apps.

## pinax-announcements

`pinax-announcements` is a well tested, documented, and proven solution
for any site wanting announcements for it's users.

Announcements have title and content, with options for filtering their display:

* `site_wide` - True or False
* `members_only` - True or False
* `publish_start` - date/time or none
* `publish_end` - date/time or none

`pinax-announcements` has three options for dismissing an announcement:

* `DISMISSAL_NO` - always visible
* `DISMISSAL_SESSION` - dismiss for the session
* `DISMISSAL_PERMANENT` - dismiss forever

## Requirements

* Django 1.8, 1.10, 1.11, and 2.0
* Python 2.7, 3.4, 3.5, and 3.6

## Getting Started and Documentation

Follow steps outlined in [Pinax Announcements Documentation](https://github.com/pinax/pinax-announcements/blob/master/docs/index.md).

## Contribute

See [this blog post](http://blog.pinaxproject.com/2016/02/26/recap-february-pinax-hangout/) including a video, or our [How to Contribute](http://pinaxproject.com/pinax/how_to_contribute/) section for an overview on how contributing to Pinax works. For concrete contribution ideas, please see our [Ways to Contribute/What We Need Help With](http://pinaxproject.com/pinax/ways_to_contribute/) section.

In case of any questions we recommend you [join our Pinax Slack team](http://slack.pinaxproject.com) and ping us there instead of creating an issue on GitHub. Creating issues on GitHub is of course also valid but we are usually able to help you faster if you ping us in Slack.

We also highly recommend reading our [Open Source and Self-Care blog post](http://blog.pinaxproject.com/2016/01/19/open-source-and-self-care/).


## Code of Conduct

In order to foster a kind, inclusive, and harassment-free community, the Pinax Project has a code of conduct, which can be found here http://pinaxproject.com/pinax/code_of_conduct/. We ask you to treat everyone as a smart human programmer that shares an interest in Python, Django, and Pinax with you.


## Pinax Project Blog and Twitter

For updates and news regarding the Pinax Project, please follow us on Twitter at @pinaxproject and check out our blog http://blog.pinaxproject.com.
