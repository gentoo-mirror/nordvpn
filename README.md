# nordvpn

Gentoo overlay for [NordVPN](https://nordvpn.com) command line client.

Warning:
 - if you are using merged usr profile you should not use ipsymlink.
 - if you used split usr profile and want to switch to merged one make sure that you remove the ipsymlink and remove the ipsymlink option.

 in case of issues with ip command after switching to merge user prfile remerge iproute2 package and make suere ipsymlink use flag is not set!