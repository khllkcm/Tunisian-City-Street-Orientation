# Tunisian City Street Orientation

![Loading image...](street-orientation.png)

Inspired by [this blog post]( http://geoffboeing.com/2018/07/city-street-orientations-world/) and [this jupyter notebook](https://github.com/gboeing/osmnx-examples/blob/master/notebooks/17-street-network-orientations.ipynb). The major difference is how the street networks were built. Since most Tunisian cities are not well defined on OpenStreetMaps, each city's street network was constructed by traversing the graph and only keeping the nodes that are within a certain distance from the center address.
