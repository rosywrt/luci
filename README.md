# RosyWrt luci feed

[![Translation status](https://hosted.weblate.org/widgets/openwrt/-/svg-badge.svg)](https://hosted.weblate.org/engage/openwrt/?utm_source=widget)

## Description

NOTE: This is the RosyWrt "luci"-feed based on [LuCI](https://github.com/openwrt/luci). And it was merged upstream now. Try the [luci-theme-rosy](https://github.com/rosywrt/luci-theme-rosy) if your luci version is **openwrt-18.06** branch.

## Usage

**[Generally]**

This feed is enabled by default. Your feeds.conf.default (or feeds.conf) should contain a line like:
```
src-git luci https://github.com/rosywrt/luci.git
```

To install all its package definitions, run:
```
./scripts/feeds update luci
./scripts/feeds install -a -p luci
```

**[Openwrt-18.06 only]**

Make your feeds.conf.default file like this if your bsp is openwrt-18.06 branch.
```
src-git rosy https://github.com/rosywrt/luci-theme-rosy.git;openwrt-18.06
```

## Contact
* Bug Report : https://github.com/rosywrt/luci/issues

* QQ Gourp : 428742246

## License

See [LICENSE](LICENSE) file.

## References
* API [documentation](http://htmlpreview.github.io/?http://raw.githubusercontent.com/openwrt/luci/master/documentation/api/index.html).

* Development [Wiki](https://github.com/openwrt/luci/wiki).

* Package [Guidelines](CONTRIBUTING.md) file.

