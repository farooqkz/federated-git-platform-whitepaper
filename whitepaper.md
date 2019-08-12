# Whitepaper for the Federated Git Platform

> this whitepaper is under construction.

## The problem we're trying to solve
GitHub is a US-based company (so are GitLab.com and BitBucket.org). This means the US has directly control over it, enabling them to exploit their power to hold rights of developers from target regions hostage.

No one wants their rights in other people's hands. It's not right. We want a place we *know* what rights we have, and no one can ever deprive us of them. This is our goal.

## The shoulders of giants
### Mastodon
In [this blog post](https://blog.fkfd.me/4) by @fakefred, he mentioned [mastodon](https://joinmastodon.org), a well-known social platform built upon the protocol [ActivityPub](https://www.w3.org/TR/activitypub/). Mastodon is federated, and is powering numerous instances spanning the globe. Although to some extent abused, it is nevertheless the best example to talk about and learn from in our project. It demonstrates a federated network hosting social data, which when substituted with git data, becomes what we desire. We can also learn about administration, fundraising and other useful knowledge that will help us build a healthy and vibrant community of developers. (It should be easy; there are lots of developers among mastodon users and admins.)

### FOSS git hosting applications
Applications like [gitea](https://gitea.io/), [gogs](https://gogs.io/), [GitLab CE](https://gitlab.com/gitlab-org/gitlab-ce/) and [phabricator](https://www.phacility.com/phabricator/), to name a few, are doing the job of GitHub amazingly well. That said, ideally our product should be a protocol rather than a fork of barely one application, while integrating well with all of them, which provide users with fine-tuned UI/UX.

