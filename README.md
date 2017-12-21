# Summary

This Docker container is used to build the planet.mozilla.org website content.
Pushes to this repository will result in a new container image on Docker Hub.
This container image is referenced by [Nubis
Haul](https://github.com/mozilla-it/haul/blob/master/sites/planet-mozilla.groovy#L12)
and Jenkins will use it to build the new site content.
