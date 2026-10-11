# Pallet Loader 3D

A 3D box-stacking game: cartons arrive as full pallet layers, and you fit them together like a puzzle. Ship every pallet **over 10 ft tall**.

- Open `index.html` in a browser (needs internet for three.js and cannon-es from a CDN).
- **Units:** weights in lb, sizes in inches, on a standard 48 × 40 in pallet. Cartons are multiples of 4 in (16–32 in).
- **Snapping:** boxes snap flush to edges and neighbours; hold `Shift` to place freely.
- **Layers:** each layer is a pallet-sized slab cut into cartons of one height, shuffled. Press `G` to show where the box in hand belongs.
- **Packing:** a live Packed % is shown; the end screen gives your average.
- **Crush:** some boxes squish and get a little crushed (80% height) if overloaded, mostly the first layer. Rigid boxes never crush.
- **Height:** build every pallet past the green 10 ft line before shipping; shipping short counts against you. Limit is 5.2 m.
- **Take back:** `U` takes back your last box, once per pallet.
- **🤖 Computer plays** (or `T`): the computer loads the truck; ×3 / ×8 speed it up. Click or press a key to take over.
- Controls: mouse aim, click/Space place, `R` turn 90°, `Z`/`X` rotate any angle, `F` flip on side, arrows nudge, `Q`/`E` or drag to orbit, scroll to zoom.
- Dropped boxes stay on the floor.

`2d/pallet-loader-2d.html` is the original 2D version (Matter.js).
