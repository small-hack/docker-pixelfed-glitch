# Pixelfed Glitch Docker Images

Forked from the [pixelfed-glitch Dockerfiles](https://github.com/pixelfed-glitch/pixelfed/tree/main/docker) primarily because I wanted nginx as the web daemon and something to publish to use in a Helm chart.

Tags are rebuilt daily so you should use the SHA hash if mutability concerns you.

Images at [docker.io/jessebot/pixelfed-glitch](https://hub.docker.com/r/jessebot/pixelfed-glitch/tags).

Available tags:
- develop-nginx (built from the develop branch)
- main-nginx (built from the main branch)
- latest pixelfed-glitch release (repo checked daily for new releases)

## Attribution

This repo is a fork of the repo managed by Matt Kulka <matt@lqx.net>, so that we can use the pixelfed-glitch fork. Check out their repo upstream if you want to use vanilla pixelfed, as it's great and they are friendly! :)
