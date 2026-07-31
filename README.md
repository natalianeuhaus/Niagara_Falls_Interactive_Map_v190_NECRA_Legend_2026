Version 1.59 factory-icon zoom update

Clicking a factory/site icon directly on the map now uses the same close-up zoom level and popup positioning as Process “Show on map” and the 1985 “Highlight on map” action.

# Niagara + Erie Hotspots Map & Industrial History — v1.57  

## v1.57 update
- Process-tab **Show on map** buttons now zoom to level 16, matching the close-up behavior of the 1985 survey **Highlight on map** buttons.
- The selected facility popup and numbered process emphasis are preserved.
- All basemap, layer, marker, legend, and center-map behavior remains unchanged from v1.55.

Version 1.35 marker separation update

# Niagara Interactive Map — v0.83

GitHub Pages package for the Niagara industrial and radiological history map.

## v0.83 update

- The historical-map canvas is now black, so missing or transparent aerial tiles appear black instead of beige or white.

- Restored Rattlesnake Creek with a revised trace based on the supplied USACE map
- Restored Two Mile Creek from the Niagara River south to the Kenmore Avenue area  
- Added clickable popups with radiological context and supporting DOE/NYSDEC links  
- Added separate legend and layer-control entries for the two waterways
- Retained clear warnings that the traces are approximate documentary overlays, not surveyed GIS centerlines or contamination boundaries 

Upload all files to the repository root and publish GitHub Pages from the `main` branch and `/ (root)`. 


## v0.83 waterway correction
Two Mile Creek was shifted west to follow the mapped channel beside Two Mile Creek Road, under I-290, through Sheridan Park, and toward Kenmore Avenue. Rattlesnake Creek was redrawn as the western tributary through Tonawanda North Unit 2.


## v0.83 waterway update
- Rattlesnake Creek geometry retained.
- Two Mile Creek now winds through Sheridan Park and Sheridan Park Golf Course and bends southeast toward the former Linde area.
- Waterway lines remain approximate documentary overlays, not surveyed GIS centerlines.


## v0.83
- Radiation guide button changed to black with white lettering.
- Historical NHAP imagery is now the opening basemap.
- At zoom level 16 and closer, the map automatically switches to the modern street map; zooming back out returns to the historical aerial.


## v0.83 display correction
The NHAP tile service contains white pixels inside some raster tiles, rather than transparent gaps. This version applies a luminance-based transparency filter to white and near-white historical-map pixels, revealing the black map background underneath. At close zoom, the map still switches to the modern street basemap.

- v0.83 aligns the Radiation guide button horizontally with the map layer/legend control.


Version 0.60 starts at a fixed Niagara corridor view, enables the 1978–1979 aerial survey layer by default, and moves editable styling into style.css.


## v0.83 opening view correction
- Uses a sidebar-aware horizontal offset after the map layout is measured.
- Opens at zoom 12 with the Niagara corridor shifted right into the visible map area, matching the supplied screenshot more closely.
- The 1978–1979 aerial radiological survey remains enabled at startup.


Panel frame controls are located at the very bottom of style.css. Edit --panel-frame-size and --panel-frame-color there.


v1.23 adds a collapsible Process tab. Clicking “Show on map” zooms to the corresponding facility, opens its popup, and displays a numbered temporary label.


v1.23 keeps the Process tab open when a facility is selected. The map still zooms, labels the site, and opens its popup; only the user changes tabs.


v1.23 keeps the 1985 Survey tab open when an anomaly is selected. The page now opens with the modern street map; visitors may select the historical aerial imagery through the layer control.


v1.23 adds a linked ORNL survey explanation before the “1984 scan / 1985 follow-up” section. The PDF opens in a new tab.


v1.23 updates the separate Bliss & Laughlin, Bethlehem Steel, and Guterl process descriptions. It also replaces the coordinate-review note with a direct download link to the complete 1985 ORNL survey.


v1.23 adds the Lake Ontario Ordnance Works / Niagara Falls Storage Site as a separate waste-storage and disposal stage after Hooker Chemical. It also links to the updated unaccounted-waste estimate and notes that tons of radioactive waste never reached LOOW.


v1.23 correctly displays LOOW/NFSS as process step 5 and renumbers the later facilities. The 1985 survey explanation now appears below its heading, followed by a short 'Click to view' source link. The completion message also becomes the same report link.


v1.23 removes the brown LOOW border, restores the correct 1–10 process sequence, renames step 1 “Uranium Ore from Belgian Congo,” removes the duplicate 1985 survey link, and adds a clickable Electromet archival-video link to its map popup.


v1.23 moves the archival-video link from Electromet to the Niagara Falls Storage Site / LOOW map popup.


v1.23 opens on the Process tab, orders tabs as Process / 1985 Survey / Legend / Archive, renames Map to Legend, reduces process fly-to zoom by two levels, and keeps the process facilities plus NFSS highlighted on initial load.


v1.23 removes the accidental active state from the Legend tab, zooms two additional levels outward for every Process destination, adds historical context to the Hooker process marker, and recenters opened facility popups within the usable map area.


v1.23 renames all internal project files to the current version, identifies Shinkolobwe as being in the present-day Democratic Republic of the Congo (DRC), adds permanent numbered map badges for process facilities and NFSS, zooms farther out for Process selections, and repositions historical-context popups so they remain inside the visible map area beside the open panel. All visual styling remains in style.css.


v1.23 removes factory-name map labels while retaining the permanent numbered badges. Process popups now use the same facility names as the Process tab, including Hooker Chemical and Carborundum. The historical-context bubble opens to the right of the selected facility, allowing a closer map zoom. All styling remains in style.css.


v1.23 restores the v1.23 popup behavior while keeping all v1.23 improvements: numbered badges only, consistent Process-tab names, closer zoom, DRC wording, updated internal filenames, and separate CSS.


v1.23 raises the permanent process numbers above all map icons, adds historical context to Carborundum, simplifies the 1985 survey introduction, adds the RASCAL missile to Bell Aerospace history, and standardizes all site links to black. CSS remains separate.


v1.23 updates the Linde/Electromet historical context, adds Hooker archive sources, adds the common uranium-chain introduction to the steel histories, replaces the map description and links it to Greetings from Niagara, adds an X to close the layers panel, and places process numbers in a dedicated pane above all map icons. Links remain black and CSS remains separate.


v1.23 adds plutonium-related research to the Carborundum description and historical context; changes the introductory project link to “Read more at Greetings from Niagara”; places process-number markers below popup windows but above ordinary map icons; and moves each number eight pixels upward with a short leader line. CSS remains separate.


v1.23 moves the permanent process numbers 20 pixels farther upward, keeps their leader lines connected to the mapped locations, makes each number clickable so it opens the associated historical-context popup, and adds a View heading above the Street map option in the layers panel. All new styling remains in style.css.


v1.23 adds the GAM-63 RASCAL to Bell Aerospace's historical context, expands Linde's history to explain that uranium ore was refined into uranium tetrafluoride (UF4/green salt), clarifies UF4 in the Electromet process text, and places the VIEW heading directly above Street map in the layers panel. All styling remains in style.css.


v1.23 explains green salt in the Electromet historical-context popup; replaces Bell's Carborundum Wheatfield candidate link with a GAM-63 RASCAL history link; starts all numbered Process cards collapsed; and reliably places VIEW directly above Street map in the layers panel. CSS remains separate.


v1.23 replaces the Union Carbide landfill historical context with the private investigator's 1979 findings, adds a direct OSTI archival report on Carborundum's plutonium fuel-development work, and loads all Process steps open. CSS remains separate.


v1.23 opens the LOOW/NFSS Process section on load, adds a direct map anchor to the Union Carbide landfill, adds the archival NFSS video as its official reference, and revises the introduction to mention factories, waste sites, and other sources of radiological contamination. CSS remains separate.


v1.23 revises the LOOW/NFSS process text, adds the New York State Assembly investigation context, embeds the Union Carbide landfill map anchor directly in the sentence, removes the separate landfill button, and adds the archival-video and unaccounted-waste links.


## v1.23 update
- Places the 1978–1979 aerial survey in a lower Leaflet pane so factories and hotspots remain clickable above it.
- Leaves the 1978–1979 survey unchecked by default on screens 900 px wide or narrower while keeping it available in the layer control.


## v1.30 search behavior
The original Legend search remains visually unchanged. Press Enter to zoom to a matching site; category terms such as TENORM zoom to the combined extent of all matches. Valid street addresses are limited to Erie and Niagara Counties and only change the map view. No-match searches report “Nothing to show.” Search never filters or fades the map.


## v1.30 development update
- Offset the Tonawanda Coke factory marker slightly northwest of its TENORM finding so both the orange Visible Site Groups marker and the standard TENORM symbol remain visible and clickable.
- Searching “Tonawanda Coke” continues to frame both matching locations.


## v1.31 development update

- Consolidated TENORM map symbols under **Documented onsite radiological finding** in the Modern Findings legend.
- Removed the separate **Documented TENORM finding** legend entry.
- Robert Moses Parkway survey locations now use the same onsite-radiological-finding symbol.
- TENORM details, measurements, and remediation status remain in each marker popup.
- The 1985 survey remains a separate layer, tab, symbol system, and dataset.

## v1.36 marker and legend corrections
- Increased separation between the factory circles and nearby FUSRAP / radiological symbols for Guterl, Bliss & Laughlin, NFSS, and Tonawanda Coke.
- Donovan Head Start now always uses the Documented onsite radiological finding symbol.
- Removed Confirmed contamination — cleanup completed from the legend; cleanup details remain in the popup.
- Preserved the existing FUSRAP legend symbol.


## v1.38 marker corrections
- Guterl FUSRAP marker moved northeast within the site area, away from the factory marker and hotspot cluster.
- NFSS FUSRAP marker moved farther east while remaining inside the mapped NFSS boundary.
- Tonawanda Coke has no FUSRAP marker.
- Donovan Head Start retains the Documented onsite radiological finding icon; remediation details remain in its popup.


## v1.38 changes
- Standardized factory-associated radiological survey triangles.
- Triangle fill now matches each factory circle color.
- Added a consistent orange-red radiological stroke to all factory survey triangles.
- Union Carbide / Electromet and former Electromet / Covanta triangles now use the same blue fill.
- Bliss & Laughlin and Guterl survey findings now use factory-colored triangles.
- Updated the factory survey legend and count.


## v1.43 update
- Standardized every hotspot outside the separate 1985 ORNL survey as **Documented onsite radiological finding**.
- Factory onsite findings and Bliss/Guterl hotspots now use the same umbrella finding symbol.
- The 1985 survey retains its distinct Ra-226 and Th-232 triangle symbols.
- Detailed classifications, measurements, dates, and remediation remain in popups.


## v1.43 changes
- Restored the last known-good v1.41 map as the base.
- Updated the panel title to “Niagara + Erie Radiological Hotspots Map & Industrial History.”
- Consolidated factory onsite hotspots with other post-1985 findings under the unified “Documented onsite radiological finding” symbol.
- Kept the separate 1985 survey symbols and layer unchanged.
- Removed the long factory onsite survey explanatory block from the left panel.
- Moved the numbered factory process badges and their dots 7 pixels higher.


## v1.45 update
- Renamed the top-right control to **Rad Symbol Legend**.
- Added radiological map symbols to the right-side panel without adding factory symbols.
- Preserved the elevated-reading and detector-reference guidance exactly as requested.


## v1.52
- Corrected the process-marker movement so the numbered badge, leader line, and colored factory dot all rise together by 7 px as a single unit.
- No basemap or other map behavior was changed.


## v1.55
Added a bottom-right Center map crosshair control. It restores the original opening center and zoom without changing the selected basemap or active overlays.


## v1.57 update
Factory popups now identify the present-day site/use and address for the major uranium-processing-chain locations. Carborundum Niagara Falls and Carborundum Wheatfield remain separate locations with separate popup information.


## v1.61
- All clickable point icons and symbols now zoom to level 16.
- Popups are centered within the usable map area to the right of the sidebar.


## v1.61 changes
- Aerial Ra-226/Bi-214 and Th-232 anomaly circles now zoom to show their full mapped extent.
- Removed the stale “Other industrial sites” filter.
- Added Pittsburgh Metallurgical / Airco / SKW / Globe Metallurgical as its own factory group and map marker.


## v1.63
- Removed the Rattlesnake Creek radiological-contamination entry from the left legend.
- Renamed that left-panel section to “Waterways.”

v1.66 waterway update:
- Two Mile Creek, Rattlesnake Creek, and Eighteenmile Creek use the same blue dashed line style.
- Top-right Rad Symbol Legend uses the matching blue dashed symbol.
- Added an approximate Eighteenmile Creek polyline from Lockport toward Olcott Harbor.


## v1.66
- Restored the Globe Metallurgical factory spot as a clearly visible brown factory marker above the brownfield and survey overlays.


## v1.68
- Moved the Globe Metallurgical factory marker slightly west and north so it is no longer hidden by the overlapping radiological survey-area symbol.
- Raised the Globe factory marker above overlapping hotspot and finding symbols.


Version 1.71: Universal sidebar-aware centering for all clicked markers, survey highlights, process buttons, address results, and multi-result bounds.


Version 1.72: Fixed 1985 Survey “Highlight on map” centering so it uses the same sidebar-aware popup/zoom behavior as factory markers.


## v1.84 update
- Prevents black background during Satellite / 1980–1989 NY NHAP switching by retaining a satellite fallback beneath selectable basemaps.
- Expands the FUSRAP explanation in the top-right Rad Symbol Legend.
- Adds yellow outlines to the red and green 1985 survey triangles in the left legend, on the map, and in the top-right legend.
- Moves both Electromet site dots, including the numbered process anchor, approximately 20 meters north.
