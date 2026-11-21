test line 1
  indented `x` ${y} \ back
end# Ormoc Bay WQMA – Establishments within 5 km

Interactive map of the 225 establishments in Albuera, Ormoc City and Merida (Leyte) that lie within 5 km of the Ormoc Bay WQMA rivers (Anilao, Malbasag, Panilahan, Albuera, Merida, Pagsangahan) or its marine monitoring stations.

**Live map:** https://masquezane.github.io/ormoc-bay-wqma-map/

## Files
| File | What it is |
|---|---|
| `index.html` | The map page (Leaflet 1.9.4) with street, satellite and topographic basemaps |
| `data.js` | Establishments, river lines, 5 km river zone and monitoring stations (compact encoding) |

## Method
Distances are straight-line from each establishment to the nearest point on the river centreline, or to the marine station point. River lines come from OpenStreetMap (named river plus connected unnamed river channels), matched to the WQMA freshwater station coordinates.

## Credits
River lines, roads and place names © OpenStreetMap contributors (ODbL). Imagery © Esri, Maxar, Earthstar Geographics. Topographic tiles © OpenTopoMap (CC-BY-SA).

