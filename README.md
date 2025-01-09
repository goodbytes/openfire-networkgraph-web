# XMPP network graph web

The HTML part of the XMPP network graph, as visible on https://xmppnetwork.goodbytes.im

It is made available to facilitate experimentation and changes.

This is a _copy_ of the web frontend which is part of a larger application, of which the sources are not made publicly available.

The files in this repository differ in a minor way from what's used by that application:
- this repository holds static copies of the data files `data.json` and `data3d.json`. In production, these endpoints are generated dynamically.
- this readme file isn't used in production

Feel free to submit PRs to suggest changes! Note that changes will be manually copied from this repository to the private repository that holds the actual application.

## Usage

Check out the entire repository, and open one of the HTML files in a browser. Your browser should render the network graph based on the static data files that are part of this repository.