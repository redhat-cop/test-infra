# Red Hat CoP Test Infra

This repo contains configurations for the Testing and CI Infastructure used by the [redhat-cop](https://github.com/redhat-cop) organization.

* [Prow](https://github.com/kubernetes/test-infra/tree/master/prow) configs
  * [config.yaml](config/prow/config.yaml) contains centralized configs for CI jobs
  * [plugins.yaml](config/prow/config.yaml) contains centralized plugin configs for repos

These configs are self-updating, meaning that when changes are merged to this repo, Prow will automatically update itself using the [inrepoconfig](https://github.com/kubernetes/test-infra/blob/master/prow/inrepoconfig.md) feature.
