# MSS OpenWrt Packages Repository

Custom OpenWrt packages repository by MSS.

## Available Packages

| Package | Description | Status |
|---------|-------------|--------|
| luci-app-helium | LuCI interface for Helium DNS Ad Blocker | ✅ Active |

## Installation

### Add Repository

```sh
# Add to custom feeds
echo "src/gz mss-packages https://raw.githubusercontent.com/mss-col/openwrt-packages/main/packages/all" >> /etc/opkg/customfeeds.conf

# Update package lists
opkg update
```

### Install Packages

```sh
# Install Helium LuCI App
opkg install luci-app-helium
```

## Prerequisites for Helium

Before installing luci-app-helium, install Helium core:

```sh
wget -O - https://raw.githubusercontent.com/mss-col/helium/main/install.sh | sh
```

## Compatibility

- ✅ OpenWrt 21.02+
- ✅ OpenWrt 22.03+
- ✅ OpenWrt 23.05+
- ✅ ImmortalWrt 21.02+
- ✅ ImmortalWrt 23.05+
- ✅ ArcadiyaWRT
- ✅ QWRT

## Support

- GitHub Issues: [luci-app-helium](https://github.com/mss-col/luci-app-helium/issues)
- Website: [mss-col.github.io](https://mss-col.github.io)

## License

Apache-2.0
