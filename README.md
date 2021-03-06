# ownCloud: Enterprise

> **Deprectaed:** Merged with [owncloud-docker/server](https://github.com/owncloud-docker/server), see our [Release Notes](https://doc.owncloud.com/server/10.5/admin_manual/release_notes.html#changes-in-delivery).

[![Build Status](https://cloud.drone.io/api/badges/owncloud-docker/enterprise/status.svg)](https://cloud.drone.io/owncloud-docker/enterprise)

This is the official ownCloud image for the enterprise edition, it is built from our [base container](https://registry.hub.docker.com/u/owncloud/base/). This ownCloud image is designed to work with a data volume in the host filesystem and with separate MariaDB and Redis containers.

For a guide how to get started with this Docker image please take a look at our [official documentation](https://doc.owncloud.com/server/latest/admin_manual/installation/docker/).

## Versions

* `latest` available as `registry.owncloud.com/owncloud/enterprise:latest` (it's 10.4.0)
* `10.4.0` available as `registry.owncloud.com/owncloud/enterprise:10.4.0`, `registry.owncloud.com/owncloud/enterprise:10.4`,  `registry.owncloud.com/owncloud/enterprise:10`
* `10.3.2` available as `registry.owncloud.com/owncloud/enterprise:10.3.2`, `registry.owncloud.com/owncloud/enterprise:10.3`
* `10.2.1` available as `registry.owncloud.com/owncloud/enterprise:10.2.1
* ...`

## Volumes

* /mnt/data

## Ports

* 8080

## Available environment variables

```

```

## Inherited environment variables

* [owncloud/base](https://github.com/owncloud-docker/base#available-environment-variables)
* [owncloud/php](https://github.com/owncloud-docker/php#available-environment-variables)
* [owncloud/ubuntu](https://github.com/owncloud-docker/ubuntu#available-environment-variables)

## Issues, Feedback and Ideas

Open an [Issue](https://github.com/owncloud-docker/enterprise/issues)

## Contributing

Fork -> Patch -> Push -> Pull Request

## Authors

* [Thomas Boerger](https://github.com/tboerger)
* [Felix Boehm](https://github.com/felixboehm)

## License

MIT

## Copyright

```
Copyright (c) 2018 Thomas Boerger <tboerger@owncloud.com>
```
