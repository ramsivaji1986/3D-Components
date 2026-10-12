# 3D Components

Client preview of lightweight, reusable 3D parts for an industrial warehouse visualization.

The page is a single interactive scene: pallet racks, cartons, floor pallets, an aisle, status beacons, a forklift, and a dock door. Drag to orbit and use the view list to focus each part.

## View the preview

Open `index.html` from a local server so the 3D module can load:

```bash
python -m http.server 5173
```

Then visit [http://localhost:5173](http://localhost:5173).

## Stack for the production components

React, Vite, and React Three Fiber. This repository is the visual sample used to review the component set with a client.
