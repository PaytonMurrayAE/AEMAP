# AE Marketing Territory Map — Market Potential Final

This is the corrected GitHub Pages build.

## Confirmed behavior

- Keeps the standard territory map for company markers and coverage circles.
- Removes the external population-density map/tile overlay entirely.
- Includes a Market Density filter: Low, Moderate, High, Very High.
- Includes Market Density in every office location's Add/Edit form.
- Includes the Market Potential card that updates after selecting a marker.
- Includes density badges in office popups.
- Removes the Top Market Opportunities ranked section.
- Contains no ArcGIS, Esri, or population-density tile service code.

## Publish

Upload these files directly to the root of the GitHub `AEMAP` repository:

- `index.html`
- `.nojekyll`
- `GOHIGHLEVEL-IFRAME.html` (reference file; not required for GitHub Pages)

Replace the existing `index.html`, commit to `main`, and wait for GitHub Pages to deploy.

Use the iframe code in `GOHIGHLEVEL-IFRAME.html`. Its version query helps bypass an older cached build.
