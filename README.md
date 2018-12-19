fork to create a development redmine container.
rails in development mode
byebug gem installed
add nano ubuntu package
do not remove ubuntu packed
get redmine source from github
1 volume to store redmine source
samba server to access sources from host.

create containers with docker-compose up
create database model with docker exec 34_redmine_1 bash then rakedb:migrate
open \\10.0.75.2\redmine
see log and interact with debugger with docker attach 34_redmine_1


# https://github.com/docker-library/redmine

## Maintained by: [the Docker Community](https://github.com/docker-library/redmine)

This is the Git repo of the [Docker "Official Image"](https://docs.docker.com/docker-hub/official_repos/) for [redmine](https://hub.docker.com/_/redmine/) (not to be confused with any official redmine image provided by redmine upstream). See [the Docker Hub page](https://hub.docker.com/_/redmine/) for the full readme on how to use this Docker image and for information regarding contributing and issues.

The [full description from Docker Hub](https://hub.docker.com/_/redmine/) is generated over in [docker-library/docs](https://github.com/docker-library/docs), specifically in [docker-library/docs/redmine](https://github.com/docker-library/docs/tree/master/redmine).

## See a change merged here that doesn't show up on Docker Hub yet?

Check [the "library/redmine" manifest file in the docker-library/official-images repo](https://github.com/docker-library/official-images/blob/master/library/redmine), especially [PRs with the "library/redmine" label on that repo](https://github.com/docker-library/official-images/labels/library%2Fredmine).

For more information about the official images process, see the [docker-library/official-images readme](https://github.com/docker-library/official-images/blob/master/README.md).

---

-	[Travis CI:  
	![build status badge](https://img.shields.io/travis/docker-library/redmine/master.svg)](https://travis-ci.org/docker-library/redmine/branches)
-	[Automated `update.sh`:  
	![build status badge](https://doi-janky.infosiftr.net/job/update.sh/job/redmine/badge/icon)](https://doi-janky.infosiftr.net/job/update.sh/job/redmine)

| Build | Status | Badges | (per-arch) |
|:-:|:-:|:-:|:-:|
| [`amd64`<br />![build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/amd64/job/redmine/badge/icon)](https://doi-janky.infosiftr.net/job/multiarch/job/amd64/job/redmine) | [`arm32v5`<br />![build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v5/job/redmine/badge/icon)](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v5/job/redmine) | [`arm32v7`<br />![build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v7/job/redmine/badge/icon)](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v7/job/redmine) | [`arm64v8`<br />![build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/redmine/badge/icon)](https://doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/redmine) |
| [`i386`<br />![build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/i386/job/redmine/badge/icon)](https://doi-janky.infosiftr.net/job/multiarch/job/i386/job/redmine) | [`ppc64le`<br />![build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/redmine/badge/icon)](https://doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/redmine) | [`s390x`<br />![build status badge](https://doi-janky.infosiftr.net/job/multiarch/job/s390x/job/redmine/badge/icon)](https://doi-janky.infosiftr.net/job/multiarch/job/s390x/job/redmine) |

<!-- THIS FILE IS GENERATED BY https://github.com/docker-library/docs/blob/master/generate-repo-stub-readme.sh -->
