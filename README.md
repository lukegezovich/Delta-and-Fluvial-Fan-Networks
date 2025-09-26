# Delta-and-Fluvial-Fan-Networks
Supplementary Data for Gezovich et al., 2025 - Discriminating fluvial fans and deltas: Channel network morphometrics reflect distinct formative processes

# Overview
This repository contains most of the mapped channel networks for deltas and fluvial fans included as shapefiles. The dataset includes channel order, lengths, widths, and branching angles in comma-separated value files. These data support the analyses presented in Gezovich et al., 2025.

# Contents
- `Shapefiles/` - Polyline features for each delta and fluvial fan channel network.
- `CSV/` - Channel measurements (length, widths, angles) in Python- and Pandas-readable format.

# Methods Summary
- Channel networks were mapped manually in ArcGIS Pro (v3.2.1) using the ESRI World Imagery basemap.  
- Channel widths and angles were measured at multiple points along each segment: immediately after a bifurcation node, immediately before the next node, and at the midpoint.
- Land–water boundaries were identified visually based on color, texture (e.g., ripples, smoothness), and vegetation contrast.  
- Widths were normalized to the first-order channel width to minimize variability caused by spatial resolution limits (~0.5 m/pixel) and seasonal flow differences.  
- Channel lengths were also normalized to first-order channel widths following Edmonds & Slingerland (2007).

# Citation
If you use these data, please cite:  

Gezovich et al., (2025). *Discriminating fluvial fans and deltas: Channel network morphometrics reflect distinct formative processes*. [EGU: Earth Surface Dynamics].  

## License
CC-BY 4.0

# Contact
For questions or issues regarding this dataset, please contact Luke Gezovich: lukegezovich@gmail.com
