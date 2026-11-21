SPACETEL CLIENT WEBSITE STARTER

This folder is the PUBLIC client website only.

Before publishing, add spacetel-public-data.json to this same folder.
Generate it using your separate Spacetel Inventory Admin HTML by uploading
the latest Inventory Report and Spacetel Calling Tree, then clicking
Download Client Data.

The client page expects this exact filename and location:
  ./spacetel-public-data.json

Only upload index.html and spacetel-public-data.json to Netlify.
Do NOT upload the admin HTML, source Excel reports, CSVs, or any serial-level
files. The JSON is served publicly and can be downloaded by anyone who can
access the website. It includes all published regions.

This is a static site. Netlify publish directory should be the repository root.
No build command is required.
