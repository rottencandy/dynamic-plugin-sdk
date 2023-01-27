# Changelog for `@openshift/dynamic-plugin-sdk-webpack`

## 2.0.0 - 2023-01-23

- Support building plugins using webpack library type other than `jsonp` ([#182])
- Emit error when a separate runtime chunk is used with `jsonp` library type ([#182])
- Allow customizing the filename of entry script and plugin manifest ([#182])
- Ensure that all APIs referenced through the package index are exported ([#184])

## 1.0.0 - 2022-10-27

> Initial release.

[#182]: https://github.com/openshift/dynamic-plugin-sdk/pull/182
[#184]: https://github.com/openshift/dynamic-plugin-sdk/pull/184