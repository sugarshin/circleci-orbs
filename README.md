# circleci-orbs

[![CircleCI](https://circleci.com/gh/sugarshin/circleci-orbs.svg?style=svg&circle-token=458b463470dc380b3dee27c6f8f2264d2a5122bb)](https://circleci.com/gh/sugarshin/circleci-orbs)

Sources for the [CircleCI Orbs](https://circleci.com/orbs/).

- https://circleci.com/orbs/registry/orb/sugarshin/npm

## Promote production

Merge to master branch, then create git tag with naming `/master-(?:patch|minor|major).*/` on local, then push to GitHub start to promote production release.
