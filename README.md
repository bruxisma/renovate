# Overview

This repository currently contains a set of common configuration settings for
using [renovatebot](https://github.com/renovatebot/renovate), an alternative to
dependabot that can be configured to use custom regex, and automerge PRs.

# Usage

While renovate explicitly states that it will automatically recommend a user's
`renovate-config` repository, this repository is simply called `renovate` so
that explicit opt-in is required to be set for a given repository, especially
when renovate is opening "onboarding" PRs.
