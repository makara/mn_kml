The mn_kml module allows administrators to add KML overlays to the fullscreen
map view on Managing News.

IMPORTANT: The default OpenLayers library in use by Managing News does not
include KML support, which is required by this module. You must change this
configuration at admin/build/openlayers. The hosted version of OpenLayers does
include KML support and is located at the following URL:
http://openlayers.org/api/OpenLayers.js

After installation, navigate to admin/settings/mn_kml to configure KML layers.
The KML files must be located on the same domain as your site due to browser
security restrictions.
