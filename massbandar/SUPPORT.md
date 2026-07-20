# Support — Digitales Maßband (Tape Measure AR)

## What it does

Digitales Maßband is an AR-based tape measure for iPhone. Point your camera
at any object and instantly read the distance between two points — in
meters, centimeters, inches, or feet. No subscription, no ads, no data
collection.

Optimised for **accuracy**:

- Multi-stage raycast prioritises detected planes (and LiDAR mesh when
  available) over visual estimation.
- 6-frame rolling average for the world-position read-out reduces hand-jitter.
- LiDAR-equipped iPhones (12 Pro and later Pro models) reach ±1 cm.
- Non-LiDAR iPhones use ARKit visual SLAM (typical accuracy ±2–5 cm at
  arm's length).

## Quick Start

1. **Grant camera access** the first time you open the app.
2. **Move your iPhone slowly** for a few seconds — the AR system needs to
   detect surfaces. The status banner will tell you what to do
   (e.g. *"Move more slowly"*).
3. **Aim the centre crosshair** at the starting point.
4. **Tap the large `+` button** — a yellow start dot anchors.
5. **Move to the second point** — a live distance appears in the
   crosshair label.
6. **Tap `+` again** — the segment turns purple and is added to history.
7. **Tap the camera icon** to save a screenshot to your Photos library.

## Function Reference

| Control | Meaning |
|---|---|
| Top-left ruler chip | Switch units: m · cm · in · ft |
| LiDAR badge | Shown only on LiDAR-equipped iPhones |
| Undo (↶) | Removes start point, or last measurement |
| Clear (🗑) | Erases all measurements |
| History (🕓) | Lists last 50 measurements with timestamp + accuracy |
| Accuracy chip | `LiDAR · ±1 cm` (best) · `Accurate` (detected plane) · `Estimated` (visual SLAM) |
| Tracking banner | Coaching messages: *Initializing AR…*, *Move more slowly*, *Needs more light or texture* |

## Frequently Asked Questions

**How accurate is it?**
LiDAR iPhones: ±1 cm under normal lighting. Non-LiDAR iPhones: typically
±2–5 cm at arm's length, degrading at longer distances. Both modes benefit
from good lighting and surface texture.

**Why is the accuracy chip yellow ("Estimated")?**
The system couldn't lock onto a detected surface yet. Slowly scan the
target surface (table, floor, wall) for a few seconds — the chip should
turn green ("Accurate") or purple ("LiDAR") and the reading will stabilise.

**Does it work without LiDAR?**
Yes. Any iPhone with ARKit support (iPhone 6s and later, running iOS 17+)
works. LiDAR just adds millimetre-class precision.

**Can I export a floor plan or PDF?**
Not in v1.0. We focus on point-to-point distance with no subscription. Tell
us if you need export.

**Does it use my data?**
No. Digitales Maßband makes no network requests and collects no data.
See [PRIVACY.md](./PRIVACY.md).

**Which iPhones does it support?**
iOS 17 or later. iPhone only (iPad version coming).

## Contact

- **Bug reports / feature requests**: [open an issue](https://github.com/fengyiqicoder/open/issues)
- **Email**: annaaiannaaiannaai@gmail.com
