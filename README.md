# Pristine Typescript OpenRPC Server

A typescript [OpenRPC Server](https://github.com/open-rpc/server-js) repository in its original condition.

Pristine Typescript OpenRPC Server a fork of [Pristine](https://github.com/etclabscore/pristine).

There are a lack of repositories to start from to build community driven open source projects. Pristine Typescript is a complete starting point, it follows a Documentation Driven Development approach, and can be used as a resource to augment existing documentation.

## Setup

1. To set up this repository you can use the [pristine-cli]() and choose this repo to start from
2. OR use it as a github template and run `.pristine/post-install.sh`

## Generated Clients
This pristine OpenRPC starting point auto generates clients to interact with this server when released via `semantic-release`. You can test out the generated ones from this repo:

### Typescript/Javascript

`npm install @etclabscore/pristine-typescript-openrpc-server-client`

### Rust

add this to your `Cargo.toml`

`pristine-typescript-openrpc-server-client = "1.1.2"`

## How to use Pristine in your project

There are 2 options for using pristine with your project.
1. Fork this repo as the start of your own, OR
2. [follow these instructions](https://thoughts.t37.net/merging-2-different-git-repositories-without-losing-your-history-de7a06bba804) to use it on an existing repository.

## Documentation Driven Development

There are many ways to drive open source development. Documenting the problem in the README gives a middle ground between technical and non-technical specifications. This allows organizing solutions to this challenge around community and documentation.

> [...] a beautifully crafted library with no documentation is also damn near worthless. If your software solves the wrong problem or nobody can figure out how to use it, there’s something very bad going on.

- [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) by Tom Preson-Werner

### Conventions and Specifications

This repository has some strong opinions built in like circleci, semantic-release, npm. So feel free to fork and change it at your own discretion. It is only meant to be a starting point. That being said:

Using conventions, documentation and specifications make it easier to:
- communicate the problem you are solving
- ease onboarding
- build and use composable tools
- promote open source contribution and engagement
- promote issue and feature discussion on Github itself

#### Resources

- [Pristine](https://github.com/etclabscore/pristine)
- [opensource.guide](https://opensource.guide/)
- [Github community profiles for public repositories](https://help.github.com/articles/about-community-profiles-for-public-repositories/)
- [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
- [pengwynn/flint](https://github.com/pengwynn/flint)
- [Working Backwards](https://www.allthingsdistributed.com/2006/11/working_backwards.html)
- [Literate programming](https://en.wikipedia.org/wiki/Literate_programming)
- [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc)
- [Inversion and The Power of Avoiding Stupidity](https://fs.blog/2013/10/inversion/)
- [choosealicense.com](http://choosealicense.com)

## Getting Started

To get started, [fork](https://help.github.com/articles/fork-a-repo/) or [duplicate](https://help.github.com/articles/duplicating-a-repository/) the repository. Then edit this file and delete everything above this line.

### Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.
