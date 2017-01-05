# **ˈʃɑːltiː**

1. [To switch, turn on](https://en.wikipedia.org/wiki/Esperanto)
2. A [Firefox Extension](https://addons.mozilla.org/firefox/extensions/) to safely browse the [I2P anonymous network](https://getmonero.org/knowledge-base/moneropedia/i2p)

## What is ∫alti?
Simply put, ∫alti will ensure that you safely browse I2P sites with minimal configuration.

Current I2P directions to [configure your browser](https://geti2p.net/en/about/browser-config) are involved and can lead to improper configuration. When this happens, sensitive data can be leaked. There is also a need to dedicate a browser to I2P which, by doing so, is cumbersome and not desirable by many.

∫alti intends to both automatically and transparently route all web traffic for `.i2p` and `.b32.i2p` addresses to a router of your choosing and will also allow you to freely browse non-I2P sites as well. This extension also aims to work perfectly with [Tor Browser](https://www.torproject.org/projects/torbrowser.html) so you can browse [onion](https://www.torproject.org/docs/hidden-services.html)/[clearnet](https://getmonero.org/knowledge-base/moneropedia/clearnet)/[garlic](https://getmonero.org/knowledge-base/moneropedia/eepsite) sites with ease - all while maintaining your anonymity.

## Current Status
Because of [XPCOM/XUL deprecations](https://blog.mozilla.org/addons/2015/08/21/the-future-of-developing-firefox-add-ons/), we must use the [WebExtensions](https://developer.mozilla.org/Add-ons/WebExtensions) API. More research is needed into *how* we can complete our objective with WebExtensions and, if not, how we can complete our objective using a combination of WebExtensions and other methods. Creative alternatives have been discussed in [meetings](https://getmonero.org/blog/tags/dev%20diaries), so visit us using the contact info below or open an issue for more information. Pull-requests/ideas are welcome!

## Disclaimer
Currently **pre-alpha** software; under heavy development

## Contact
- IRC: [Freenode](https://webchat.freenode.net/) | [OFTC](https://webchat.oftc.net/) | Irc2P
  - `#kovri-dev` | Kovri Development Channel
  - `#monero-dev` | Monero Development Channel
