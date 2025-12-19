## Reproduction

Clone this repository:

```sh
git clone https://github.com/deining/hugo-v0.153.0-warning.git
cd hugo-v0.153.0-warning
```

Invoke a site preview:

```sh
hugo server --logLevel info
```

This deprecation info will appear:

```sh
INFO  deprecated: module.mounts.lang was deprecated in Hugo v0.153.0 and will be removed in a future release. Replaced by the more powerful 'sites.matrix' setting, see https://gohugo.io/configuration/module/#mounts
```
