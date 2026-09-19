# Flicker Stitch — Assembly Instructions

Stitch a working circuit onto fabric. In this kit you sew small electronics
onto an embroidered badge using **conductive thread**, and when you flip the
switch, the LEDs light up.

By [@borisnotes](https://borisnotes.com)

![Finished badge](photos/finished_badge.jpg)


---

## 1. What's in the bag

<!-- TODO: photo of everything laid out, labelled -->
![Bag contents](photos/bag_contents.jpg)

| # | Item | Qty |
|---|------|-----|
| 1 | Canvas | 1 |
| 2 | Design paper | 1 |
| 3 | Needle | 1 |
| 4 | Needle threader | 1 |
| 5 | Conductive thread | 1 |
| 6 | Outline thread (black) | 1 |
| 7 | Colour thread 1 | 1 |
| 8 | Colour thread 2 | 1 |
| 9 | Battery module with switch | 1 |
| 10 | Blinky LED module | 2 |

> **Not in the bag, but useful:** good light, a flat table, a small pair of
> scissors, clear nail polish (optional, for sealing knots).

---

## 2. How the electronics work

![Schematic](photos/schematic.png)

Electricity needs a **loop**. It leaves one side of the battery, passes through
the parts, and comes back to the other side. If the loop is broken anywhere,
nothing lights up.

The circuit in this kit is just a battery, a switch and two blinky LEDs:

- **Battery (CR2032)** — the power source, 3 V. It has a **+** side and a
  **–** side.
- **Switch** — opens and closes the loop. Off means the loop is open.
- **Blinky LED modules (×2)** — each one has a tiny chip inside that turns its
  LED on and off by itself. They only work **one way round**: current must go
  in the **+** side and out the **–** side. The resistor that protects the LED
  is already on the module, so you don't need any extra parts.
- **Conductive thread** — the wires. Each line of stitching carries current
  from one pad to the next.

Follow the lines on the schematic:

1. From the battery **+**, current goes through the **switch**.
2. After the switch it reaches a junction (the top green dot) that feeds
   **both LEDs at once**. This is called wiring in *parallel*, so each LED gets
   the full battery voltage and blinks on its own.
3. Both LEDs return to the battery **–** through a second junction (the bottom
   green dot), which closes the loop.

### Two rules for the thread

1. **+ and – must never touch.** If two stitches from opposite sides of the
   battery touch, the current takes a shortcut and the LEDs stay dark (and the
   battery drains).
2. **Every joint needs contact.** The thread has to actually touch the metal
   pad, and be pulled snug against it.

<!-- TODO: add polarity markings here: where is + and – on each board? -->

---

## 3. Threading the needle

<!-- TODO: photo -->
![Threading](photos/threading.jpg)

1. **Cut about TODO cm** of conductive thread. Longer is not better; it
   tangles and frays.
2. Push the end through the eye of the needle. If it won't go, snip the end
   at a sharp angle to remove loose fibres. Wetting the tip helps.
3. Pull it through until you have about **TODO cm** on the short side.
4. **Tie a knot** at the long end. This is the anchor that stops the thread
   pulling through.

### Tying the knot

<!-- Uses the existing photo -->
![Simple knot](photos/simple_knot.png)

1. Make a loop around your finger.
2. Roll the thread off your fingertip so it twists into a small coil.
3. Pinch the coil and pull the thread through to the end. A small, firm knot
   forms.
4. Snip off the tail, leaving ~3 mm.

> **Tip:** conductive thread is slippery. Make the knot a double knot.

---

## 4. Running stitch: connecting the parts

A **running stitch** is the simplest stitch: the needle goes down, up, down,
up, in a dotted line. It's how you'll draw each "wire".

<!-- TODO: diagram of running stitch -->
![Running stitch](photos/running_stitch.jpg)

### The basic motion

1. Bring the needle **up** from the back of the fabric.
2. Take the needle **down**, a short distance ahead (3–5 mm).
3. Bring it **up** again, one stitch-length further.
4. Repeat. The thread shows as dashes on the front, and as longer dashes on
   the back.

Keep stitches small and even, and pull the thread **snug but not tight**, so the
fabric doesn't pucker.

### Stitching to a pad

<!-- TODO: photo of thread around a pad -->
![Stitching to a pad](photos/stitch_pad.jpg)

1. Start with the knot on the **back**, near the first pad.
2. Bring the needle up through the **hole** in the pad.
3. Go back down through the same hole, then up again. Do this **2–3 times**,
   pulling snug each time. This wraps the thread on the metal for a solid
   contact.
4. Now run stitches along the path to the next pad, following the lines
   on the canvas.
5. At the next pad, wrap through the hole **2–3 times** again.

### Step by step: the circuit

<!-- TODO: fill in once the canvas layout is final -->
1. **TODO** — Battery + to switch
2. **TODO** — Switch to LED +
3. **TODO** — LED – back to battery –
4. **TODO** — Repeat for the next LED

### Ending a thread

1. Finish with a wrap through the last pad.
2. Take the needle to the **back**, and tie a double knot close to the fabric.
3. Trim the tail to ~3 mm, so it can't touch another line.
4. Optional: dab clear nail polish on the knot to lock it.

### If you run out of thread

Finish it as above and start a new piece **on the same pad**. Overlap the old
and the new for a few stitches to keep the connection.

---

## 5. Test it

1. Check the battery is in and the right way up.
2. Slide the switch to **ON**.
3. The LEDs should light or start blinking.

### Nothing lights up?

| Problem | Fix |
|---------|-----|
| No LEDs at all | Check the battery, and that the switch is on. |
| One LED is dark | Check it's the right way round, and re-wrap the thread on its pads. |
| Dim or flickering | A loose contact. Pull the stitches snug, and add another wrap on the pad. |
| Nothing works, battery warm | **+** and **–** are touching. Look for stray threads, and trim them. |
