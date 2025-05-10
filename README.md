# c13wrt
Kumpulan IPK openwrt

# c13wrt OpenWRT Repo

This is a repository for OpenWRT packages (IPK) that can be installed via `opkg`.

## Adding the repository to OpenWRT

To add this repository to your OpenWRT system, follow these steps:

1. SSH into your OpenWRT device.
2. Edit the `customfeeds.conf` file:
   ```
   vi /etc/opkg/customfeeds.conf
   ```
3. Add the following line:
   ```
   src/gz c13wrt https://github.com/chandrasoekmawan/c13wrt/raw/main/
   ```
4. Run `opkg update` to refresh the package list.
5. Install packages with `opkg install <package-name>`.

## Available packages
- Package 1
- Package 2
