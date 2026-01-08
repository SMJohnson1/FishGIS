<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cold Spring Brook — Map Demo (Leaflet + OSM)</title>
  <link
    rel="stylesheet"
    href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"
    integrity="sha256-p4NxAoJBhIIN+hmNHrzRCf9tD/miZyoHS5obTRR9BMY="
    crossorigin=""
  />
  <style>
    html, body { height: 100%; margin: 0; }
    #map { height: 100%; width: 100%; }
    .popup img { display:block; max-width: 260px; height: auto; border-radius: 6px; margin-top: 6px; }
    .popup h3 { margin: 0 0 4px 0; font-size: 16px; }
    .popup p { margin: 4px 0 0 0; font-size: 13px; line-height: 1.35; }
    .legend { position: absolute; top: 10px; left: 10px; background: #fff; padding: 8px 10px; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,.1); z-index: 1000; font: 14px/1.2 system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif; }
    .legend b { display:block; margin-bottom: 4px; }
    .legend small { color:#666; }
  </style>
</head>
<body>
  <div id="map"></div>
  <div class="legend">
    <b>Cold Spring Brook (Newton, MA)</b>
    <small>Tap a marker to view image + notes</small>
  </div>  <script
    src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"
    integrity="sha256-20nQCchB9co0qIjJZRGuk2/Z9VM+kNiyxNV1lvTlZBo="
    crossorigin=""
  ></script>  <script>
    // --- Base map ---
    const map = L.map('map');

    const osm = L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }).addTo(map);

    // --- Demo data (approximate coordinates) ---
    // Note: These sample points are for demo purposes only.
    const points = [
      {
        id: 1,
        title: 'Beacon St Trailhead (Cold Spring Park)',
        coords: [42.3302, -71.2139],
        image: 'https://picsum.photos/id/1018/600/400',
        blurb: 'North entrance near Beacon St parking. Boardwalks and wetlands are nearby, with access to the main loop trail.'
      },
      {
        id: 2,
        title: 'Interior Wetland / Brook Crossing',
        coords: [42.329074, -71.214550],
        image: 'https://picsum.photos/id/1025/600/400',
        blurb: 'Shaded stretch where the trail meets a small brook and vernal wetland—great for birding after rain.'
      },
      {
        id: 3,
        title: 'South Meadow Brook — Needham St Culvert',
        coords: [42.3166, -71.1979],
        image: 'https://picsum.photos/id/1039/600/400',
        blurb: 'Culvert section where South Meadow Brook passes under Needham St; frequent high-water observations.'
      },
      {
        id: 4,
        title: 'Kennard Conservation Area Connector',
        coords: [42.3218, -71.2048],
        image: 'https://picsum.photos/id/1043/600/400',
        blurb: 'Connector path through woods and wetlands associated with South Meadow Brook; seasonal boardwalks in places.'
      },
      {
        id: 5,
        title: 'Cold Spring Park — Central Meadow',
        coords: [42.3287, -71.2145],
        image: 'https://picsum.photos/id/1056/600/400',
        blurb: 'Open meadow near the loop trail, often used for field activities; brook edges visible towards the south.'
      }
    ];

    // Fit map to all points
    const group = L.featureGroup(points.map(p => L.marker(p.coords)));
    map.fitBounds(group.getBounds().pad(0.2));

    // Add markers with popups
    points.forEach(p => {
      const content = `
        <div class="popup">
          <h3>${p.title}</h3>
          <p>${p.blurb}</p>
          <img src="${p.image}" alt="${p.title}" />
        </div>`;
      L.marker(p.coords).addTo(map).bindPopup(content, { maxWidth: 280 });
    });

    // Optional: tap-to-locate (helpful on iPad)
    map.on('click', (e) => {
      // You could add behavior here (e.g., record notes, open a form)
      // console.log('Tapped at', e.latlng);
    });
  </script></body>
</html>
