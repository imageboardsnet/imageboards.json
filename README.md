This is a list of anonymous or registration-free imageboards in JSON format maintained by imageboards.net.

Feel free to pull request !

Derived from ccd0's list, Creamy's list, other imageboard lists, online searches, imageboard threads, and various other sources. Contributions welcome.

JSON endpoints:
https://imageboardsnet.github.io/imageboards.json/imageboards.json

Archives and closed boards that it is no longer possible to post to will not be listed.
To avoid disturbing very slow boards, sites will not be listed unless they have at least 12 posts per year.
Exceptions will be made for new sites, demo sites for imageboard software, and sites that specifically request to be added.

Codes used for the "software" field are documented at [software.md](software.md).

The "mirrors" field describes alternate ways of accessing the site with substantially the same interface. It does not include URLs that merely redirect to the main URL. It is an array in the following format:
* The first element is a part of the site URL ("url" field) and of other URLs (e.g. "boardlist"), usually the protocol and domain part.
* Subsequent elements are what the first element should be replaced with to reach corresponding pages on the site's mirrors.

The "interfaces" field describes alternate ways of accessing the site with substantially different interfaces.

The "entrances", "redirects", and "fallbacks" fields are arrays containing various types of alternate URLs for the site.
* "entrances" are sites that contain links to the main site.
* "redirects" are URLs that redirect to the site or redirect to a page linking to the site.
* "fallbacks" are URLs not yet used but which may be activated if the main site goes down.
