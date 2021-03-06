# docker-ubuntu-node

A NodeJS Docker image based on Ubuntu LTS Minimal, ready to use as a base image for development, testing or production environments on projects running LTS on Ubuntu.

This repository contains a `Dockerfile` used for auto-build on docker hub.

The `ubuntu-node` image is published on Docker Hub at that URL

* https://hub.docker.com/r/rbecheras/ubuntu-node

`Node.js` is bundled with the latest `npm` and `yarn` package managers.

See:

* [Docker Home](https://www.docker.com)
* [Docker Hub](https://hub.docker.com)
* [Ubuntu Home](https://www.ubuntu.com)
* [Minimal Ubuntu, on public clouds and Docker Hub](https://blog.ubuntu.com/2018/07/09/minimal-ubuntu-released)
* [Ubuntu on Docker Hub](https://hub.docker.com/_/ubuntu/)
* [NodeJS Home](https://nodejs.org)
* [NodeJS on Docker Hub](https://hub.docker.com/_/node/)
* [Yarn Home](https://yarnpkg.com)
* [npm Home](https://www.npmjs.com)

## Git Tags and Docker Tags

- Any change on the branch `master` triggers a rebuild on docker hub and updates the docker tag `latest`
- Any new pushed `1.x` git tag triggers a rebuild on docker hub and updates the docker tag as `18.04-8` and `carbon`:
    * The first parts, `18.04` and `bionic`, gives the major version of `Ubuntu LTS` used as the base image
    * The second parts, `8` and `carbon`, gives the major version of `NodeJS LTS` installed in the image


- Any the git tag `2.0.0` will be created and pushed when the next LTS of Ubuntu or Node.js will be released. And this line will be updated.

## License

[MIT License](LICENSE)
