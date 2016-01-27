# masala_exhibitor

This is a component of the [masala toolkit](https://github.com/PaytmLabs/masala).

This is a [wrapper cookbook](http://blog.vialstudios.com/the-environment-cookbook-pattern/#thewrappercookbook) for providing recipes for exhibitor-based zookeeper server deployment.

It will enable datadog zookeeper monitoring if enabled in masala_base

## Supported Platforms

The platforms supported are:
- Centos 6.7+ / Centos 7.1+
- Ubuntu 14.04 LTS (And future LTS releases)
- Debioan 8.2+

## Attributes

Please see the documentation for the cookbooks included by masala_exhibitor. (See [metadata.rb](https://github.com/PaytmLabs/masala_exhibitor/blob/develop/metadata.rb) file)

This cookbook does not add any attributes of it's own.

## Usage

### masala_exhibitor::default

Include `masala_exhibitor` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[masala_exhibitor::default]"
  ]
}
```

## License, authors, and how to contribute

See:
- [LICENSE](https://github.com/PaytmLabs/masala_exhibitor/blob/develop/LICENSE)
- [MAINTAINERS.md](https://github.com/PaytmLabs/masala_exhibitor/blob/develop/MAINTAINERS.md)
- [CONTRIBUTING.md](https://github.com/PaytmLabs/masala_exhibitor/blob/develop/CONTRIBUTING.md)

