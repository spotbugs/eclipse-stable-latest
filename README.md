# Update Site for SpotBugs Eclipse Plugin

This repository serves update site for SpotBugs Eclipse Plugin.
About the usage of SpotBugs Eclipse Plugin, please visit [official manual](http://spotbugs.readthedocs.io/en/latest/eclipse.html).

## URL for Eclipse Update site

Please use following URL when you install SpotBugs Eclipse Plugin:

https://spotbugs.github.io/eclipse-stable-latest/

## How we push changes to this repository

When changes have been merged to [spotbugs](https://github.com/spotbugs/spotbugs) repository,
Travis CI builds Eclipse Plugin and [deploys](https://docs.travis-ci.com/user/deployment/pages/) it to the `gh-pages` branch of this repository.
