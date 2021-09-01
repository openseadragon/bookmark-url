# Bookmark URL

An OpenSeadragon plugin for updating the zoom/pan (and optionally the sequence "page") in the web page URL.

## Usage

Create your OpenSeadragon viewer and then:

`viewer.bookmarkUrl();` or `viewer.bookmarkUrl({ trackPage: true });`

It'll take the viewer to wherever the web page's hash parameters point, and it'll update the page URL with hash parameters. The optional `trackPage` parameter adds the active "page" of an OSD sequence to the hash parameters.

You can watch for the `bookmark-url-change` event on the viewer to be notified when the URL changes (the `url` property of the event is the new URL).

See demo.html for an example. You can also see it in the wild here: https://minecraft.greener.ca/byblos/map/overworld/

## Sponsored By

Thanks to [@jason-green-io](https://github.com/jason-green-io) for the generous support!
