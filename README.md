# Pitch Lists for Toontrack's Superior Drummer 3

This repository offers a compilation of Studio One `.pitchlist` files designed for various Superior Drummer 3
extensions, commonly referred to as `SDX`.

## Installation

> Note: The following instructions assume the presence of the StudioOne workspace at `D:\StudioOne`.

Each `.pitchlist` file should be placed in StudioOne's User Preset directory:

`D:\Studio One\Presets\User Presets\Pitch Names`

After insertion, refresh the loaded presets from the home tab of the Studio One Browser (F5) to make it readily
available for usage.

## Common Specifications

- Aliases are omitted, ensuring each articulation is unique in a pitchmap.
- Less common hits such as `C1: Muted` or `SD: Flam` are hidden by default.
- The coloring for each instrument is consistent among pitchmaps.

## Mapped Extensions

As of now, only a subset of the product range is mapped:

| Product   | Extension |                                              |
|-----------|-----------|----------------------------------------------|
| Death SDX | SL-Death  | [.pitchlist](Pitchlists/Death.SDX.pitchlist) |

## Mapped Instruments

Superior Drummer 3, along with its extensions, presents an extensive array of shells, cymbals, and accessories.

To maintain consistency in pitch names across all pitch lists, each individual instrument is assigned a token. This
token serves as a prefix to the pitch's articulation. For example, `SD: Center` denotes a center-hit on the snare drum,
while `F2: Rimshot` signifies a rimshot on floor tom 2.

Certain tokens may be available in every extension (e.g., `K1` and `SD`), while others are exclusive. The listing below
displays all unique instruments available in all extensions combined:

### Shells

| Token | Instrument   |    Exclusive to     |
|-------|--------------|:-------------------:|
| `K1`  | Kick 1/R     |                     |
| `K2`  | Kick 2/L     |                     |
| `SD`  | Snare        |                     |
| `H1`  | High Tom 1   |                     |
| `H2`  | High Tom 1   |                     |
| `H3`  | High Tom 1   |                     |
| `H4`  | High Tom 4   |                     |
| `T1`  | Rack Tom 1   |                     |
| `T2`  | Rack Tom 2   |                     |
| `T3`  | Rack Tom 3   |                     |
| `F1`  | Floor Tom 1  |                     |
| `F2`  | Floor Tom 2  |                     |
| `BT`  | Bass Tom     |  `Metal Machinery`  |
| `RM`  | Rim          | `Hitmaker Machines` |
| `E1`  | Tom 1        | `Hitmaker Machines` |
| `E2`  | Tom 2        | `Hitmaker Machines` |
| `E3`  | Tom 3        | `Hitmaker Machines` |
| `E4`  | Tom 4        | `Hitmaker Machines` |
| `P1`  | Percussion 1 | `Hitmaker Machines` |
| `P2`  | Percussion 2 | `Hitmaker Machines` |
| `P3`  | Percussion 3 | `Hitmaker Machines` |
| `P4`  | Percussion 4 | `Hitmaker Machines` |
| `P5`  | Percussion 5 | `Hitmaker Machines` |
| `P6`  | Percussion 6 | `Hitmaker Machines` |
| `I1`  | Timpani 1    |  `Legacy of Rock`   |
| `I2`  | Timpani 2    |  `Legacy of Rock`   |
| `GD`  | Gongdrum     |     `Hitmaker`      |

### Cymbals

| Token | Instrument |   Exclusive to   |
|-------|------------|:----------------:|
| `HH`  | Hi-Hat     |                  |
| `C1`  | Crash 1    |                  |
| `C2`  | Crash 2    |                  |
| `C3`  | Crash 3    |                  |
| `C4`  | Crash 4    |                  |
| `C5`  | Crash 5    |                  |
| `C6`  | Crash 6    |                  |
| `R1`  | Ride 1     |                  |
| `R2`  | Ride 2     |                  |
| `R3`  | Ride 3     |                  |
| `X1`  | China 1    |                  |
| `X2`  | China 2    |                  |
| `Z1`  | Splash 1   |                  |
| `Z2`  | Splash 2   |                  |
| `Z3`  | Splash 3   |    `Hitmaker`    |
| `SP`  | Spock      |                  |
| `GG`  | Gong       | `Legacy of Rock` |

### Accessories

| Token | Instrument |  Exclusive to  |
|-------|------------|:--------------:|
| `ST`  | Stick      |                |
| `CB`  | Cowbell    |                |
| `CP`  | Claps      |                |
| `TX`  | Tambourine | `Indiependent` |