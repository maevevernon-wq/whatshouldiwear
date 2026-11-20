# My Virtual Closet

A browser-local wardrobe and 3D outfit planner built with React, TypeScript, Tailwind CSS, Three.js, React Three Fiber and Drei.

## Run locally

Install Node.js 20 or newer, then run:

```sh
npm install
npm run dev
```

Open the local address printed by Vite. To create a production build, run `npm run build`, then `npm run preview`.

Wardrobe images, metadata, and saved looks live in this browser's IndexedDB; model preferences use localStorage. Clearing browser data removes them. Sample garments are illustrations and can be edited or deleted. Garment templates are approximations, not 3D reconstructions of uploaded photos.
