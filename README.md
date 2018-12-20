# Virtualmon [![](https://img.shields.io/github/last-commit/raioramalho/virtualmon.svg)](https://github.com/raioramalho/virtualmon/releases/) [![](https://img.shields.io/github/release-date/raioramalho/virtualmon.svg?style=popout)](https://github.com/raioramalho/virtualmon) [![](https://img.shields.io/github/release/raioramalho/virtualmon.svg?style=popout)](https://github.com/raioramalho/virtualmon/releases) [![Twitter Follow](https://img.shields.io/twitter/follow/raioramalho.svg?style=social&label=Follow)](https://twitter.com/raioramalho)

```
# virtualmon v1.0 (https://gitlab.com/raioramalho/virtualmon)

Generate virtual wireless interfaces in monitor mode.
This tool has been translated from Portuguese[br] into English[us].
I do not take responsibility for your actions.
This code uses a GPL license.

Usage: virtualmon --mk <mon0> -i <wlan interface> <extra options>

Engine Options:
	-mk <name>: Create a virtual wireless interface.
	-rm <name>: Remove a virtual wireless interface.
	-i <wlan interface>: Specifies which interface will generate the virtual monitor.
Extra Options:
	--c <number>: Specifies the monitor channel.
	--channel-hop <on/off>: Enable or disable the channel-hop.
