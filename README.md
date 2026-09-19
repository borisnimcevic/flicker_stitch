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

| # | Item | Qty | Notes |
|---|------|-----|-------|
| 1 | Embroidered badge canvas | 1 | Credit-card sized |
| 2 | Needle | 1 | TODO: size / type |
| 3 | Conductive thread | 1 | TODO: length. Grey and slightly shiny. This is your "wire". |
| 4 | Coloured thread (red, white, black, peach) | TODO | For decoration only. It does not conduct. |
| 5 | Green LEDs (with resistor) | TODO | Steady light |
| 6 | Self-blinking LEDs, fast | TODO | Flash on their own |
| 7 | Self-blinking LEDs, slow | TODO | Flash on their own |
| 8 | Battery holder board with switch | 1 | Holds the coin cell |
| 9 | CR2032 coin cell | 1 | TODO: already installed, or separate? |

> **Not in the bag, but useful:** good light, a flat table, a small pair of
> scissors, clear nail polish (optional, for sealing knots).

---

## 2. How the electronics work

<!-- TODO: circuit diagram or photo with the path drawn on it -->
![Circuit overview](photos/circuit_overview.jpg)

Electricity needs a **loop**. It leaves one side of the battery, passes through
the parts, and comes back to the other side. If the loop is broken anywhere,
nothing lights up.

In this kit:

- **Battery (CR2032)** — the power source, 3 V. It has a **+** side and a
  **–** side.
- **Switch** — opens and closes the loop. Off means the loop is open.
- **Conductive thread** — the wires. Each line of stitching carries current
  from one pad to the next.
- **LED** — a light that only works **one way round**. Current must go in the
  **+** side (anode) and out the **–** side (cathode). Put it in backwards and
  it stays dark (it won't be damaged).
- **Resistor** — limits the current so the LED doesn't burn out. It is already
  on the LED board, so you don't need to add one.
- **Self-blinking LED** — has a tiny chip inside that turns it on and off by
  itself. It needs no extra parts. It still has a **+** and a **–**.

The loop, in order:

```
  battery +  →  switch  →  LED (+ to –)  →  battery –
```

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
