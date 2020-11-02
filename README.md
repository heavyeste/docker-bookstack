<!-- DO NOT EDIT THIS FILE MANUALLY  -->
<!-- Please read the CONTRIBUTING.md -->

[![linuxserver.io](https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/linuxserver_medium.png)](https://linuxserver.io)

[![Blog](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Blog)](https://blog.linuxserver.io "all the things you can do with our containers including How-To guides, opinions and much more!")
[![Discord](https://img.shields.io/discord/354974912613449730.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Discord&logo=discord)](https://discord.gg/YWrKVTn "realtime support / chat with the community and the team.")
[![Discourse](https://img.shields.io/discourse/https/discourse.linuxserver.io/topics.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=discourse)](https://discourse.linuxserver.io "post on our community forum.")
[![Fleet](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Fleet)](https://fleet.linuxserver.io "an online web interface which displays all of our maintained images.")
[![GitHub](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub&logo=github)](https://github.com/linuxserver "view the source for all of our repositories.")
[![Open Collective](https://img.shields.io/opencollective/all/linuxserver.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Supporters&logo=open%20collective)](https://opencollective.com/linuxserver "please consider helping us by either donating or contributing to our budget")

The [LinuxServer.io](https://linuxserver.io) team brings you another container release featuring:

 * regular and timely application updates
 * easy user mappings (PGID, PUID)
 * custom base image with s6 overlay
 * weekly base OS updates with common layers across the entire LinuxServer.io ecosystem to minimise space usage, down time and bandwidth
 * regular security updates

Find us at:
* [Blog](https://blog.linuxserver.io) - all the things you can do with our containers including How-To guides, opinions and much more!
* [Discord](https://discord.gg/YWrKVTn) - realtime support / chat with the community and the team.
* [Discourse](https://discourse.linuxserver.io) - post on our community forum.
* [Fleet](https://fleet.linuxserver.io) - an online web interface which displays all of our maintained images.
* [GitHub](https://github.com/linuxserver) - view the source for all of our repositories.
* [Open Collective](https://opencollective.com/linuxserver) - please consider helping us by either donating or contributing to our budget

# [linuxserver/bookstack](https://github.com/linuxserver/docker-bookstack)

[![GitHub Stars](https://img.shields.io/github/stars/linuxserver/docker-bookstack.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-bookstack)
[![GitHub Release](https://img.shields.io/github/release/linuxserver/docker-bookstack.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-bookstack/releases)
[![GitHub Package Repository](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub%20Package&logo=github)](https://github.com/linuxserver/docker-bookstack/packages)
[![GitLab Container Registry](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitLab%20Registry&logo=gitlab)](https://gitlab.com/Linuxserver.io/docker-bookstack/container_registry)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/linuxserver/bookstack.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge)](https://microbadger.com/images/linuxserver/bookstack "Get your own version badge on microbadger.com")
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/bookstack.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=pulls&logo=docker)](https://hub.docker.com/r/linuxserver/bookstack)
[![Docker Stars](https://img.shields.io/docker/stars/linuxserver/bookstack.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=stars&logo=docker)](https://hub.docker.com/r/linuxserver/bookstack)
[![Jenkins Build](https://img.shields.io/jenkins/build?labelColor=555555&logoColor=ffffff&style=for-the-badge&jobUrl=https%3A%2F%2Fci.linuxserver.io%2Fjob%2FDocker-Pipeline-Builders%2Fjob%2Fdocker-bookstack%2Fjob%2Fmaster%2F&logo=jenkins)](https://ci.linuxserver.io/job/Docker-Pipeline-Builders/job/docker-bookstack/job/master/)
[![LSIO CI](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=CI&query=CI&url=https%3A%2F%2Fci-tests.linuxserver.io%2Flinuxserver%2Fbookstack%2Flatest%2Fci-status.yml)](https://ci-tests.linuxserver.io/linuxserver/bookstack/latest/index.html)

[Bookstack](https://github.com/BookStackApp/BookStack) is a free and open source Wiki designed for creating beautiful documentation. Feautring a simple, but powerful WYSIWYG editor it allows for teams to create detailed and useful documentation with ease.

Powered by SQL and including a Markdown editor for those who prefer it, BookStack is geared towards making documentation more of a pleasure than a chore.

For more information on BookStack visit their website and check it out: https://www.bookstackapp.com


[![bookstack](https://s3-us-west-2.amazonaws.com/linuxserver-docs/images/bookstack-logo500x500.png)](https://github.com/BookStackApp/BookStack)

## Supported Architectures

Our images support multiple architectures such as `x86-64`, `arm64` and `armhf`. We utilise the docker manifest for multi-platform awareness. More information is available from docker [here](https://github.com/docker/distribution/blob/master/docs/spec/manifest-v2-2.md#manifest-list) and our announcement [here](https://blog.linuxserver.io/2019/02/21/the-lsio-pipeline-project/).

Simply pulling `ghcr.io/linuxserver/bookstack` should retrieve the correct image for your arch, but you can also pull specific arch images via tags.

The architectures supported by this image are:

| Architecture | Tag |
| :----: | --- |
| x86-64 | amd64-latest |
| arm64 | arm64v8-latest |
| armhf | arm32v7-latest |


## Usage

Here are some example snippets to help you get started creating a container.

### docker-compose ([recommended](https://docs.linuxserver.io/general/docker-compose))

Compatible with docker-compose v2 schemas.

```yaml
---
version: "2"
services:
  bookstack:
    image: linuxserver/bookstack
    container_name: bookstack
    environment:
      - PUID=1000
      - PGID=1000
      - DB_HOST=bookstack_db
      - DB_USER=bookstack
      - DB_PASS=<yourdbpass>
      - DB_DATABASE=bookstackapp
    volumes:
      - /path/to/data:/config
    ports:
      - 6875:80
    restart: unless-stopped
    depends_on:
      - bookstack_db
  bookstack_db:
    image: linuxserver/mariadb
    container_name: bookstack_db
    environment:
      - PUID=1000
      - PGID=1000
      - MYSQL_ROOT_PASSWORD=<yourdbpass>
      - TZ=Europe/London
      - MYSQL_DATABASE=bookstackapp
      - MYSQL_USER=bookstack
      - MYSQL_PASSWORD=<yourdbpass>
    volumes:
      - /path/to/data:/config
    restart: unless-stopped

```

### docker cli

```
docker run -d \
  --name=bookstack \
  -e PUID=1000 \
  -e PGID=1000 \
  -e DB_HOST=<yourdbhost> \
  -e DB_USER=<yourdbuser> \
  -e DB_PASS=<yourdbpass> \
  -e DB_DATABASE=bookstackapp \
  -e APP_URL=http://your.site.here.xyz `#optional` \
  -p 6875:80 \
  -v /path/to/data:/config \
  --restart unless-stopped \
  ghcr.io/linuxserver/bookstack
```


## Parameters

Container images are configured using parameters passed at runtime (such as those above). These parameters are separated by a colon and indicate `<external>:<internal>` respectively. For example, `-p 8080:80` would expose port `80` from inside the container to be accessible from the host's IP on port `8080` outside the container.

| Parameter | Function |
| :----: | --- |
| `-p 80` | will map the container's port 80 to port 6875 on the host |
| `-e PUID=1000` | for UserID - see below for explanation |
| `-e PGID=1000` | for GroupID - see below for explanation |
| `-e DB_HOST=<yourdbhost>` | for specifying the database host |
| `-e DB_USER=<yourdbuser>` | for specifying the database user |
| `-e DB_PASS=<yourdbpass>` | for specifying the database password |
| `-e DB_DATABASE=bookstackapp` | for specifying the database to be used |
| `-e APP_URL=http://your.site.here.xyz` | for specifying the url your application will be accessed on (required for correct operation of reverse proxy) |
| `-v /config` | this will store any uploaded data on the docker host |

## Environment variables from files (Docker secrets)

You can set any environment variable from a file by using a special prepend `FILE__`.

As an example:

```
-e FILE__PASSWORD=/run/secrets/mysecretpassword
```

Will set the environment variable `PASSWORD` based on the contents of the `/run/secrets/mysecretpassword` file.

## Umask for running applications

For all of our images we provide the ability to override the default umask settings for services started within the containers using the optional `-e UMASK=022` setting.
Keep in mind umask is not chmod it subtracts from permissions based on it's value it does not add. Please read up [here](https://en.wikipedia.org/wiki/Umask) before asking for support.

## User / Group Identifiers

When using volumes (`-v` flags) permissions issues can arise between the host OS and the container, we avoid this issue by allowing you to specify the user `PUID` and group `PGID`.

Ensure any volume directories on the host are owned by the same user you specify and any permissions issues will vanish like magic.

In this instance `PUID=1000` and `PGID=1000`, to find yours use `id user` as below:

```
  $ id username
    uid=1000(dockeruser) gid=1000(dockergroup) groups=1000(dockergroup)
```


&nbsp;
## Application Setup


The default username is admin@admin.com with the password of **password**, access the container at http://dockerhost:6875.

This application is dependent on a MySQL database be it one you already have or a new one. If you do not already have one, set up our MariaDB container here https://hub.docker.com/r/linuxserver/mariadb/.


If you intend to use this application behind a subfolder reverse proxy, such as our LetsEncrypt container or Traefik you will need to make sure that the `APP_URL` environment variable is set, or it will not work

Documentation for BookStack can be found at https://www.bookstackapp.com/docs/

### Advanced Users (full control over the .env file)
If you wish to use the extra functionality of BookStack such as email, Memcache, LDAP and so on you will need to make your own .env file with guidance from the BookStack documentation.
  
When you create the container, do not set any arguments for any SQL settings, or APP_URL. The container will copy an exemplary .env file to /config/www/.env on your host system for you to edit.

#### PDF Rendering
[wkhtmltopdf](https://wkhtmltopdf.org/) is available to use as an alternative PDF rendering generator as described at https://www.bookstackapp.com/docs/admin/pdf-rendering/.

The path to wkhtmltopdf in this image to include in your .env file is `/usr/bin/wkhtmltopdf`.


## Docker Mods
[![Docker Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=bookstack&query=%24.mods%5B%27bookstack%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=bookstack "view available mods for this container.") [![Docker Universal Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=universal&query=%24.mods%5B%27universal%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=universal "view available universal mods.")

We publish various [Docker Mods](https://github.com/linuxserver/docker-mods) to enable additional functionality within the containers. The list of Mods available for this image (if any) as well as universal mods that can be applied to any one of our images can be accessed via the dynamic badges above.


## Support Info

* Shell access whilst the container is running: `docker exec -it bookstack /bin/bash`
* To monitor the logs of the container in realtime: `docker logs -f bookstack`
* container version number
  * `docker inspect -f '{{ index .Config.Labels "build_version" }}' bookstack`
* image version number
  * `docker inspect -f '{{ index .Config.Labels "build_version" }}' ghcr.io/linuxserver/bookstack`

## Updating Info

Most of our images are static, versioned, and require an image update and container recreation to update the app inside. With some exceptions (ie. nextcloud, plex), we do not recommend or support updating apps inside the container. Please consult the [Application Setup](#application-setup) section above to see if it is recommended for the image.

Below are the instructions for updating containers:

### Via Docker Compose
* Update all images: `docker-compose pull`
  * or update a single image: `docker-compose pull bookstack`
* Let compose update all containers as necessary: `docker-compose up -d`
  * or update a single container: `docker-compose up -d bookstack`
* You can also remove the old dangling images: `docker image prune`

### Via Docker Run
* Update the image: `docker pull ghcr.io/linuxserver/bookstack`
* Stop the running container: `docker stop bookstack`
* Delete the container: `docker rm bookstack`
* Recreate a new container with the same docker run parameters as instructed above (if mapped correctly to a host folder, your `/config` folder and settings will be preserved)
* You can also remove the old dangling images: `docker image prune`

### Via Watchtower auto-updater (only use if you don't remember the original parameters)
* Pull the latest image at its tag and replace it with the same env variables in one run:
  ```
  docker run --rm \
  -v /var/run/docker.sock:/var/run/docker.sock \
  containrrr/watchtower \
  --run-once bookstack
  ```
* You can also remove the old dangling images: `docker image prune`

**Note:** We do not endorse the use of Watchtower as a solution to automated updates of existing Docker containers. In fact we generally discourage automated updates. However, this is a useful tool for one-time manual updates of containers where you have forgotten the original parameters. In the long term, we highly recommend using [Docker Compose](https://docs.linuxserver.io/general/docker-compose).

### Image Update Notifications - Diun (Docker Image Update Notifier)
* We recommend [Diun](https://crazymax.dev/diun/) for update notifications. Other tools that automatically update containers unattended are not recommended or supported.

## Building locally

If you want to make local modifications to these images for development purposes or just to customize the logic:
```
git clone https://github.com/linuxserver/docker-bookstack.git
cd docker-bookstack
docker build \
  --no-cache \
  --pull \
  -t ghcr.io/linuxserver/bookstack:latest .
```

The ARM variants can be built on x86_64 hardware using `multiarch/qemu-user-static`
```
docker run --rm --privileged multiarch/qemu-user-static:register --reset
```

Once registered you can define the dockerfile to use with `-f Dockerfile.aarch64`.

## Versions

* **17.09.20:** - Rebase to alpine 3.12. Fix APP_URL setting. Bump php post max and upload max filesizes to 100MB by default.
* **19.12.19:** - Rebasing to alpine 3.11.
* **26.07.19:** - Use old version of tidyhtml pending upstream fixes.
* **28.06.19:** - Rebasing to alpine 3.10.
* **14.06.19:** - Add wkhtmltopdf to image for PDF rendering.
* **20.04.19:** - Rebase to Alpine 3.9, add MySQL init logic.
* **22.03.19:** - Switching to new Base images, shift to arm32v7 tag.
* **20.01.19:** - Added php7-curl
* **04.11.18:** - Added php7-ldap
* **15.10.18:** - Changed functionality for advanced users
* **08.10.18:** - Advanced mode, symlink changes, sed fixing, docs updated, added some composer files
* **23.09.28:** - Updates pre-release
* **02.07.18:** - Initial Release.
