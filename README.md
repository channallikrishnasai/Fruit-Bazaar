# Fruit Bazaar demo

A responsive, two-page website prototype for the Fruit Bazaar sample business.

The previous version is saved at `../Model A` as a restore point.

## Experience

- index.html is a brand and company-story homepage. It does not display the fruit catalogue.
- Selecting “Explore 70 fruits” starts the same five-second, full-screen falling-photo collage using the same Wikipedia fruit and plant thumbnails and fallback photos as the catalogue.
- catalog.html organizes the 70 fruit profiles into four sections: 18 daily fruits, 18 nutritious fruits, 18 exotic fruits, and 16 seasonal fruits. It includes catalogue search, an orchard / whole fruit / cut fruit / farm photo gallery, and detailed profiles.
- styles.css and experience.css provide responsive styling, layered photo motion, and reduced-motion handling.

## Fruit photography

Fruit thumbnails and five-sentence botanical background notes are requested from the English Wikipedia API. Each detail panel links to its article and image source. Higher-resolution gallery images are requested from Wikimedia Commons when a fruit profile is opened. The catalogue reports the names of fruit pages that return no usable thumbnail, so those photos can be supplied and added.

The Mango profile includes a verified high-resolution mango farm photograph from Wikimedia Commons (`Mango farm.jpg`, by Syedabdhakir, CC BY-SA 4.0). The farm gallery search uses fruit common names and orchard, harvest, and picking terms.

Photo backgrounds and web fonts load online. The website is a visual demo; it is not connected to inventory or ordering.

## Visiting card

`fruit-bazaar-card-front.svg` and `fruit-bazaar-card-back.svg` are the print-ready two-sided card artwork, designed at 3.75 × 2.25 inches including 1/8-inch bleed. The back has the website QR embedded as an unchanged square code inside a fruit-basket frame. Trim to 3.5 × 2 inches after printing.
