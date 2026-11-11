SOUTH WALES CRIME MAPS: HOW TO USE

Files
  index.html   the page content
  style.css    all colours, fonts and layout

Adding your Datawrapper maps
  1. Open each published map in Datawrapper and click Publish & Embed.
  2. Copy the "Responsive iframe" code.
  3. In index.html, find the section for that map (MAP 1 to MAP 5).
  4. Paste the code inside <div class="map-embed"> and delete the
     <div class="placeholder"> block.

Editing
  - Map titles, descriptions and nav labels are plain text in index.html.
  - Colours and fonts are set at the top of style.css under :root.
  - Open index.html in any browser to preview. No server needed.
