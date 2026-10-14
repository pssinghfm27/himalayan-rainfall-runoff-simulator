# Himalayan Springshed Hydrology Simulator

**An offline, installable web app that shows village communities and field staff where rainwater goes on a Himalayan hillside, and how trenches, pits and plantations change what reaches their spring.**

Built for community training in the **Central Himalayan Rural Action Group (CHIRAG)** springshed programme, Uttarakhand (Apr - Jun 2026).

![PWA](https://img.shields.io/badge/app-Progressive%20Web%20App-5a0fc8)
![Offline](https://img.shields.io/badge/works-offline-success)
![Stack](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20vanilla%20JS-f7df1e)

---

## Why

"Why should we dig trenches on that slope?" is the question every springshed programme has to answer in a village meeting. A paper diagram does not convince anyone. This simulator lets people change the rainfall, the slope, the rock and the forest, and watch the water split into runoff, evaporation, infiltration and deep percolation, and see the effect on spring discharge.

## What you can change

- **Rainfall and storm pattern**
- **Slope**
- **Rock type:** granite, gneiss, schist, quartzite, slate/phyllite, shale, sandstone, limestone, dolomite, colluvium/debris
- **Soil type**, including laterite and barren/rocky ground
- **Vegetation typical of Uttarakhand:** Banj oak, Chir pine, Sal, Burans (rhododendron), Ringal bamboo, mixed broadleaf, alpine grassland, degraded scrubland, CHIRAG mixed plantation
- **Recharge structures:** contour trenches (length, total volume) and pits

The model shows the resulting water balance (runoff, evapotranspiration, infiltration, deep percolation) and the change in spring flow.

## Use it

- Open `index.html` in any browser, or install it to a phone home screen as a PWA.
- No server, no login, no internet after the first load (fonts fall back to system fonts offline).

## Design notes

- Single-file app (~45 KB) so it can be shared over WhatsApp or USB and run on low-end Android phones.
- Mobile-first layout, max width 560 px, large touch targets for field use.
- Parameters are simplified, first-order coefficients for teaching and planning conversations, not a calibrated hydrological model.

## Author

**Prahlad Pratap Singh** · MBA (Forestry Management), Indian Institute of Forest Management, Bhopal

Developed for CHIRAG's springshed programme. MIT licence.
