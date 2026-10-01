SmallRoute v0.1
================

Prototype features:
- Mobile map
- Live GPS location
- Destination search
- Vehicle selector: 50cc, 150cc, motorcycle, motorized bicycle
- Highway/toll/restricted-road preference controls (routing enforcement is next)
- Route display using public prototype routing services
- Navigation-start UI
- Basic report button placeholder

How to use on iPhone:
1. Open index.html from a web host or local development server.
2. Allow location access.
3. Enter a destination and tap GO.
4. Select a vehicle profile.

Important:
This is an early prototype. The current public routing service is a generic car router; it does NOT yet guarantee vehicle-legal routing. The next development step is replacing it with a vehicle-aware routing engine (e.g. Valhalla/GraphHopper) and authoritative road restrictions.
