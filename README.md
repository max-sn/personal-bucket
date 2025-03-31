# Scoop Bucket Template

[![Tests](https://github.com/max-sn/personal-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/max-sn/personal-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/max-sn/personal-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/max-sn/personal-bucket/actions/workflows/excavator.yml)

This bucket contains packages that I (@max-sn) use or wanted to try personally.

* [Gaphor](https://gaphor.org/): A UML, SysML, RAAML, and C4 modeling application.
* [kroki-cli](https://kroki.io/):

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add personal-bucket https://github.com/max-sn/personal-bucket
scoop install personal-bucket/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
