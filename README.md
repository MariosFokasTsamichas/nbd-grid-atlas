# NBD DC & BESS – Grid Node Atlas (public edition)

Static site: `index.html` is self-contained (data embedded); d3 loads from cdnjs.

Deploy on Render: New → Static Site → this repo → Build command: (empty) → Publish directory: `.`
(or New → Blueprint, which reads `render.yaml`).

Public edition differences: TeleGeography submarine cables and landing points removed (licence does not allow
redistribution); landing names hidden in node panels. Search engines are asked not to index (meta robots, robots.txt,
X-Robots-Tag header). Anyone with the URL can still open it.

Data: © OpenStreetMap contributors (ODbL 1.0) · WRI Global Power Plant Database (CC BY 4.0) · Natural Earth (public domain)
· ENTSO-E grid map via GridKit · ADMIE connection lists · project sources as cited in the page. Scores are screening
proxies, not hosting capacity or connection offers.
