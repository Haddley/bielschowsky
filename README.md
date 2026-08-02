# Between the shoulders

An interactive demonstration of how a **right superior oblique (fourth nerve)
palsy** behaves as the head rolls from one shoulder to the other — and of a
correction that only a head-mounted display can deliver.

**→ [haddley.github.io/bielschowsky](https://haddley.github.io/bielschowsky/)**

**Work in progress.** This is an open notebook, not a result: one person, one
day, and the person is also the author. Expect the numbers to move.

## What the Bielschowsky test is

Described by Alfred Bielschowsky in 1935 and still how a fourth nerve palsy is
identified, usually as the third step of a three-step examination needing no
equipment at all.

1. Head straight — which eye sits higher?
2. Does that get worse looking left, or right?
3. **The head tilt** — does it get worse toward one shoulder or the other?

Step three is the clever one. Tilting the head makes the eyes counter-roll, and
intorting the right eye is shared between the superior oblique and the superior
rectus. With the oblique weak, the rectus supplies the missing twist — and being
an elevator, it lifts the eye as a side effect. The eye that was already higher
goes higher still.

A right superior oblique palsy reads: **right eye higher, worse looking left,
worse tilting right.** That last part is the positive sign, and it is why
someone with this palsy holds their head toward the *other* shoulder without
ever being taught to.

This page adds resolution. In a clinic that third step is three head positions
and a judgement of "worse". Here it is a continuous sweep, and instead of a
judgement the subject dials the image until it goes single — so "worse" becomes
a number of degrees, at every angle in between.

## What you are looking at

Roll the head and four things move together:

- **both eyes' torsional orientation**, against where they ought to sit — the
  left eye counter-rolls correctly, the right one cannot intort and falls short;
- **the right eye rising**, because the superior rectus recruited to supply the
  missing intorsion is also an elevator — the mechanism behind Bielschowsky's
  head-tilt test;
- **a level horizon as each eye receives it**, superimposed, so the wedge
  between the two is the double vision;
- **the mismatch against a measured ±3.5° cyclofusional range.**

A toggle applies the correction and leaves a ghost of what was removed.

## Why a headset

The correction has three components, and the page shows them separately because
they are not equally well established:

| component | at head level | evidence |
|---|---|---|
| **rotation** | −5.5°, rising to −11.6° at the right shoulder | measured — 15 hand-dialled nulls, 4 sessions |
| vertical prism | ~8 Δ | measured at head **level only** |
| horizontal prism | ~1 Δ | barely measured, possibly nothing |

Ordinary spectacles already carry the lower two — a prism translates an image.
**No optic rotates one.** So the torsional component of a fourth-nerve palsy is
conventionally left uncorrected and carried by head posture. It is also, at
every head position here, the largest of the three. A headset has two
independent displays and knows its own roll against gravity ninety times a
second, which is the whole argument.

## What is measured and what is not

- The **rotation curve** is fitted to fifteen corrections dialled by hand across
  four sessions in one day. Those points are plotted on the page as ticks.
- The **vertical** is measured at head level only. How it varies with head roll
  has never been measured; the page *assumes* it scales with the rotation and
  draws that assumption hatched everywhere it appears.
- The **direction** of the torsional tilt comes from the subject's own report,
  not from an instrument. No eye tracker made or sold measures the sign of
  cyclotorsion — it needs iris-pattern tracking. The magnitude is measured; the
  sign is testimony.

## Not a medical device

This is an educational demonstration. It is not validated, and it is **n = 1** —
one person, who is also the person who built it. It should not replace an
examination with a neuro-optometrist or ophthalmologist, and nothing here is an
offer of treatment. **New or changing double vision needs a clinician urgently.**

## Building it

One self-contained HTML file. No build step, no dependencies, no network calls —
open `index.html` in a browser.
