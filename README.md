# Secret Passages

**Secret Passages** is a GPS-based treasure hunt game. Walk in the direction of the arrow to find hidden waypoints. When you’re close enough, a secret message (and optional images or audio) will unlock. Your walked path is drawn on the map, creating shapes as you explore.

## Play the Demo
https://YOUR-USERNAME.github.io/secret-passages/  
- Allow location access when prompted  
- Follow the arrow toward each waypoint  
- Unlock secrets as you get within ~15 m  

## Author Mode
Author Mode lets you create and edit your own maps.

Open:  
https://YOUR-USERNAME.github.io/secret-passages/?author=1  
PIN for demo: `4321`

**In Author Mode you can:**  
- Click the map to add waypoints  
- Drag to move them  
- Click the path to insert a waypoint between two others  
- Use the List panel to edit titles, messages, images, and audio  
- Export the map as a JSON file  

## Sharing Your Map
1. Export your JSON from Author Mode.  
2. Save it in the `levels/` folder of this repo.  
3. Commit & push to GitHub Pages.  
4. Share with this format:  
https://YOUR-USERNAME.github.io/secret-passages/?levelUrl=https://YOUR-USERNAME.github.io/secret-passages/levels/YOUR-MAP.json

## Tech Notes
- Uses [MapLibre GL JS](https://maplibre.org/) for maps (no API billing)  
- Mobile-friendly (iOS + Android)  
- Unlock radius ~15 m  
- Language toggle: English / French  
- All logic is in `index.html` — easy to host anywhere with HTTPS