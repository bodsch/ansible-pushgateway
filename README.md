
# Ansible Role:  `pushgateway`

Ansible role to setup [pushgateway](https://github.com/prometheus/pushgateway).


[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/bodsch/ansible-pushgateway/CI)][ci]
[![GitHub issues](https://img.shields.io/github/issues/bodsch/ansible-pushgateway)][issues]
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/bodsch/ansible-pushgateway)][releases]

[ci]: https://github.com/bodsch/ansible-pushgateway/actions
[issues]: https://github.com/bodsch/ansible-pushgateway/issues?q=is%3Aopen+is%3Aissue
[releases]: https://github.com/bodsch/ansible-pushgateway/releases


## Requirements & Dependencies

- None

### Operating systems

Tested on

* Arch Linux
* Debian based
    - Debian 10 / 11
    - Ubuntu 20.10
* RedHat based
    - Alma Linux 8
    - Rocky Linux 8
    - Oracle Linux 8

## usage

### default configuration

```yaml
pushgateway_version: "1.4.2"

pushgateway_release: {}

pushgateway_system_user: pushgateway
pushgateway_system_group: pushgateway

pushgateway_direct_download: false

pushgateway_logging: {}

pushgateway_web: {}

pushgateway_persistence: {}
```


## Contribution

Please read [Contribution](CONTRIBUTING.md)

## Development,  Branches (Git Tags)

The `master` Branch is my *Working Horse* includes the "latest, hot shit" and can be complete broken!

If you want to use something stable, please use a [Tagged Version](https://gitlab.com/bodsch/ansible-pushgateway/-/tags)!

---

## Author and License

- Bodo Schulz

## License

[Apache](LICENSE)

**FREE SOFTWARE, HELL YEAH!**
