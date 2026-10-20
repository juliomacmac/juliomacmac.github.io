# Julio Maculan — PCB design portfolio

[View the portfolio](https://juliomacmac.github.io/)

Boards developed with EESC-USP Tupã Formula SAE, including the four-layer Power Distribution Module, ShieldESP display, BSPD, BSS, precharge, HV interface, and SSI indicator.

The featured PDM includes a complete top-down 3D board view, individual SIG1/GND/PWR/SIG2 copper views, and the Altium stackup. The site also includes 25 schematic sheets in SVG format.

## Local use

Open index.html. The website is static and does not require a build step or JavaScript to browse.

To edit project descriptions or schematic lists, update project-data.json and run `node build.mjs`. Style changes go in style.css. Board models, routing views and schematic drawings are in assets/.

## Publishing

GitHub Pages publishes the main branch from the repository root. Keep .nojekyll and the assets directory.

## Project notes

Board images are Altium 3D models, not photographs of assembled hardware. Personal contributions are described on each project page. Manufacture, testing and installation are explicitly stated for the PDM. Altium source links may require workspace access; the schematic SVGs are included directly in the site.

