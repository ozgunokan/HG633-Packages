# HG633 Packages

Eight individual opkg/IPK packages for the maintained HG633 port. The router keeps the original OpenWrt Software page: Update lists populates Available packages; Installed packages uses the real opkg database. Available packages also includes the complete installed inventory; installed rows show plain, noninteractive Installed text. The default All view and package search cover both installed and repository entries.

- hg633-core: LuCI and shared services
- hg633-network: Network and Firewall
- hg633-wifi: Wi-Fi
- hg633-dsl: DSL and SNR
- hg633-sqm: SQM QoS
- hg633-zapret: Zapret
- hg633-doh: DNS over HTTPS
- hg633-system: System tools

Current opkg feed: `v3/Packages.gz`. Signed board/kernel and SHA256 metadata: `v3/catalog.json`, `v3/catalog.sig`, `v3/public-key.pem`. IPK assets are attached to individual versioned Releases. The maintained LuCI adapter verifies HTTPS/signatures before refreshing the opkg index or installing selected packages and required dependencies. The old Backfire wget is not used for HTTPS downloads.

Packages preserve settings and personal RF calibration. There are no automatic reboot or service-restart scripts. Existing opkg inventory is retained; package ownership is recorded by actual opkg installation. v1 remains only for compatibility with the superseded bundle client. No v2 component-HGU feed was published.

Native source materials and license notices: [sources-opkg-20261031](https://github.com/ozgunokan/HG633-Packages/releases/tag/sources-opkg-20261031). Never upload signing keys, personal firmware, credentials, calibration or client logs.

Existing firmware-integrated components are enrolled through standard opkg only after matching the signed package payload. Personal image builds seed matching opkg ownership/version records after verifying every component file; this does not qualify generic fresh installation.
