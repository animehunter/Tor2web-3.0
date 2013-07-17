# Tor2web Documentation

  * [Tor2web-3.0 specific documentation](https://github.com/globaleaks/Tor2Web-3.0/wiki/Home)
  * [GlobaLeaks documentation](https://github.com/globaleaks/GlobaLeaks/wiki/Home) (leading project of Tor2Web)
  * How does [Tor Hidden Services (HSs)](https://www.torproject.org/docs/tor-hidden-service.html.en) works
  * Previous release: [Tor2web 2.0](https://github.com/globaleaks/tor2web-2.0)
  * Official website: of [www.tor2web.org](http://tor2web.org)

Additional Hacks by Animehunter

  * Removed tor2web banner
  * User-agent spoofing via config file
  * Removed x-tor2web from the http header
  * Removed "redirect to https" to make reverse proxy possible (user (https) -> proxypass -> tor2web (http))
  * Removed all x- headers to improve privacy
