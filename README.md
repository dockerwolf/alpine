# OpenJDK OpenJ9

[![](https://images.microbadger.com/badges/image/cwlf/openjdk-openj9.svg)](https://microbadger.com/images/cwlf/openjdk-openj9)

This is our minimal customized OpenJDK base image based on [AdoptOpenJDK's OpenJ9 build](https://registry.hub.docker.com/adoptopenjdk/openjdk8-openj9/). Optionally you can enable a cron daemon, to get it running you need to provide the environment variable `CRON_ENABLED=true` or `CRON_ENABLED=1`. You can see the available variables below. Be aware that you have to start `s6` to get the cron daemon started automatically.

## Versions

To get an overview about the available versions please take a look at the [GitHub branches](https://github.com/dockerwolf/openjdk-openj9/branches/all) or our [Docker Hub tags](https://hub.docker.com/r/cwlf/openjdk-openj9/tags/), these lists are always up to date.


## Volumes

* None


## Ports

* None


## Available environment variables

```bash
ENV CRON_ENABLED false
```


## Inherited environment variables

* None


## Contributing

Fork -> Patch -> Push -> Pull Request


## Authors

* [Thomas Boerger](https://github.com/tboerger)
* [Chip Wolf](https://github.com/chipwolf)

## License

MIT


## Copyright

```
Copyright (c) 2015 Thomas Boerger <http://www.webhippie.de>
Copyright (c) 2019 Chip Wolf <https://chipwolf.uk>
```
