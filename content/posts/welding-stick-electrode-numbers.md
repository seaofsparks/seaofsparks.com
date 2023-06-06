---
title: "What do welding stick electrode numbers mean?"
date: 2023-06-05T18:50:35+02:00
draft: false
tags:
- stick
- SMAW
- explanation
---
If you've picked up a pack of welding electrodes (or sticks) you've probably seen the numbers that are written on the packaging and on the electrodes. We all have our favorite numbers for specific welds and materials but what do those numbers actually mean? Do all numbers work in all machines? Can you weld everything with 6013? Let's dig in.

The numbers on your sticks are determined by the [American Welding Society](https://aws.org) and determine the strength, position, and coating of your electrode. To be complete, these numbers all start with the letter `E` for *electrode*. You will see these numbers in use all over the world.

## The First Two Numbers

The first two numbers written on your stick determine the tensile strength of the filler material in it. `60` means 60 000 PSI and so `70` means 70 000 PSI of tensile strength. This number is straightforward. We're halfway through the number but things are about to get a little bit more complex. There's a bit of a gotcha here and that is that if the electrode number is `5` digits long then the first three digits are the tensile strengte: `E100xx` is taken to mean a 100 000 psi tensile strength stick.

### The Third Number

The third number indicates the position the stick should be used in. Note the should because you can probably overcome some of the positional difficulties. You should take this number mostly to mean how quickly the weld pool will solidify. An all-position number-`1` stick will have a weld pool that dries up quickly while a flat-position only number-`2` stick will have a weld pool that is slower to dry up making it more likely to drip or deform when welding vertical or overhead.

The full list of numbers for this position is:

* `1`: All positions.
* `2`: Flat and horizontal positions.
* `4`: Flat, horizontal, vertical-down, overhead positions.

To put that together we can now decipher three quarters of a number. For example the electrode `E601x` means a 60 000 psi tensile strength stick that can be used in all positions. An `E1002x` is a 100 000 psi tensile strength stick that can be used in the flat and horizontal positions.

### The Last Number

Probably the most difficult number to remember is the last number in the series. This indicates the coating that is used on the stick but it *also* says in which polarities this electrode can be used. Let's get a table first and then dig into what the numbers *actually* mean.

| Digit | Coating                             | Polarity     |
|-------|-------------------------------------|--------------|
| 0     | High Cellulose Sodium               | DC+          |
| 1     | High Cellulose Potassium            | AC, DC+, DC- |
| 2     | High Titania Sodium                 | AC, DC-      |
| 3     | High Titania Potassium              | AC, DC+      |
| 4     | Iron Powder, Titania                | AC, DC+, DC- |
| 5     | Low Hydrogen Sodium                 | DC+          |
| 6     | Low Hydrogen Potassium              | AC, DC+      |
| 7     | High Iron Oxide, Iron Powder        | AC, DC+, DC- |
| 8     | Low Hydrogen Potassium, Iron Powder | AC, DC+, DC- |

Many of the numbers on this list you might never find in real life but it helps us decipher the rest of the electrode.

Electrodes with a Low Hydrogen coating are often called *basic electrodes* and will attract moisture from the air, you generally want to keep them as dry as possible. Special ovens are made to keep these sticks at a high temperature to keep them dry. The reason for this is that hydrogen causes defects in your weld, these electrodes will deposit minimum hydrogen in your weld pool which often leads to less defects, but they also need to be kept dry to make sure they can do so. It is also import to know that low hydrogen electrodes generally need a higher open circuit voltage to get started. Many smaller inverter welder boxes will be unable to properly light up a low hydrogen stick.

### Common Electrode Numbers

* `E6010`, a common root or repair stick. It penetrates deep and is often used on dirty surfaces.
* `E6011`, a common repair stick that can be used on AC. It penetrates deep and is often used on dirty surfaces.
* `E6013`, a common all purpose electrode that has an arc that digs less into the base material and is easy to clean up spatter and slag wise.
* `E7018`, a high deposit rate electrode with a higher tensile strength that has a basic coating (you need to keep it dry!), very commonly used for filling and capping.
