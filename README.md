# Week-Long Luxury Kenya Safari Map: Samburu, Kalama, Laikipia & Lewa
 
This is an interactive map of a 7-day luxury safari through northern Kenya's private conservancies. The trip starts at Nairobi's **Wilson Airport**, the hub for bush flights. It then visits the arid wilderness of **Samburu** and the **Kalama Community Conservancy**, continues to the high plateau of **Laikipia** with stays at Laikipia Wilderness Camp and **Ol Lentille**, and finishes at the rhino sanctuary of **Lewa Wildlife Conservancy**.
 
🗺️ **See the full itinerary and the live map:**
[Tygodniowe luksusowe safari w Kenii](https://safarikenia.com.pl/tygodniowe-luksusowe-safari-w-kenii/) on **Safari Kenia**
 
---
 
## The route
 
| Day | Destination | Accommodation / Area |
|-----|-------------|----------------------|
| Start | Arrival in Nairobi | Wilson Airport |
| Day 1 | Samburu region | Saruni Samburu |
| Day 2 | Samburu National Reserve | Samburu National Reserve |
| Day 3 | Kalama Conservancy | Kalama Community Conservancy |
| Day 4 | Laikipia | Laikipia Wilderness Camp |
| Day 5 | Northern Laikipia | Ol Lentille |
| Day 6 | Lewa Conservancy | Lewa Wildlife Conservancy |
| Day 7 | Departure | Jomo Kenyatta International Airport |
 
**Northern frontier:** Nairobi → Samburu → Samburu National Reserve → Kalama Conservancy
**Laikipia plateau:** Laikipia Wilderness Camp → Ol Lentille → Lewa Wildlife Conservancy
**Home:** Lewa → Nairobi (JKIA)
 
The interface labels are in Polish, matching the tour page it's embedded on.
 
## Features
 
- **Conservancy-focused itinerary.** The map highlights community and private conservancies (Kalama, Ol Lentille, Lewa) rather than only the national parks. These are the areas known for low-density, high-end safaris, the "Samburu Special Five" and rhino conservation.
- **Satellite basemap.** The map uses the Mapbox Standard Satellite style with a tilted camera, which shows the contrast between Samburu's dry scrubland and the greener Laikipia plateau beneath Mount Kenya.
- **Direct-line connections.** Stops are joined by straight lines, which suits a fly-in style itinerary built around Wilson Airport and bush airstrips.
- **Animated route line.** The route is drawn as a golden "marching ants" dashed line.
- **Interactive itinerary panel.** A glassmorphism sidebar lists all seven days. Clicking a card flies the camera to that stop and opens its popup.
- **Custom markers.** Gold SVG pins with popups show each day and its accommodation.
- **Mobile-friendly.** On small screens the sidebar becomes a bottom sheet, and cooperative gestures keep page scrolling smooth.
- **WordPress-ready.** Styles are scoped to a single container, so the code can be pasted into a Custom HTML block.
## Tech stack
 
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/) v3.9.0
- Vanilla JavaScript, no build step
- Plus Jakarta Sans (Google Fonts)
## Usage
 
1. Copy the HTML into a WordPress **Custom HTML** block or any web page.
2. Replace the Mapbox access token with your own, and restrict it to your domain in your [Mapbox account](https://account.mapbox.com/access-tokens/).
3. Adjust the container height in `.wp-safari-itinerary-container` to fit your layout.
To change the route, edit the `itineraryData` array. Each entry gets a marker, a popup and a sidebar card.
 
## About
 
Built for [Safari Kenia](https://safarikenia.com.pl/), Polish-language safari tours and travel guides for Kenya.
 
➡️ [View this luxury Kenya safari itinerary](https://safarikenia.com.pl/tygodniowe-luksusowe-safari-w-kenii/)
