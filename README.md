# Dekaoto_Label_App
Image labeling
Dekaokto Photo Studio

A single-page tool for property photos. Runs fully in the browser. No server, no uploads.

Features: labels (New listing, Exclusive, Under offer, Sold and more), Dekaokto logo (wordmark or icon, vector), crop with fixed shapes, combine several photos into one, batch download as ZIP.

Publish on GitHub Pages
Create a repository and upload index.html (the assets folder is optional).
Open Settings, then Pages.
Under Source choose "Deploy from a branch", branch main, folder / (root).
The tool goes live at https://<user>.github.io/<repo>/.
Logo files

The logo is embedded inside index.html as vector paths, taken from dekaokto_final_logotypes.pdf. assets/ holds the same logos as standalone SVG files in Charcoal, Bone, Deep Olive and Gold.

Change labels or colours

Open index.html and edit LABELS and COLORS near the top of the script.
