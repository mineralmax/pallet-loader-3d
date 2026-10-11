# Pallet Loader 3D

A 3D box-stacking game: load 100 boxes onto pallets and ship each one out **over 10 ft tall**.

- Open `index.html` in a browser (needs internet for three.js and cannon-es from a CDN).
- **Crush:** some boxes squish under load and get a little crushed (they keep 80% of their height) if overloaded, mostly the first layer. Rigid boxes (heavy-duty and some standard ones) never crush. Fragile boxes have red tape.
- **Height:** build every pallet past the green 10 ft line before shipping. Shipping short counts against you. Limit is 5.2 m.
- **Take back:** `U` (or the button) takes back your last box, once per pallet.
- **🤖 Computer plays** (or `T`): the computer loads the truck; ×3 / ×8 speed it up. Click or press a key to take over.
- Controls: mouse aim, click/Space place, `R` turn 90°, `Z`/`X` rotate any angle, `F` flip on side, arrows nudge, `Q`/`E` or drag to orbit, scroll to zoom.
- Dropped boxes stay on the floor.

`2d/pallet-loader-2d.html` is the original 2D version (Matter.js).
