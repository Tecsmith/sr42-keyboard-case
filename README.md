# SR42 Keyboard Case

**Fusion 360 source files for the SR42 keyboard**

---

<p align="center"><img alt="Do not build" src="docs/donotbuild.min.svg" width="213"></p>
<blockquote align="center"><b>NB:</b> This project design is complete, but has not been prototyped for validation.</blockquote>

---

<table>
  <tr><td colspan="12" align="center"><img src="docs/sr42-render.png"></td></tr>
  <tr>
    <td colspan="4" align="center"><img src="docs/assets/img/sr42-case-top.png" width="320"></td>
    <td colspan="4" align="center"><img src="docs/assets/img/sr42-plate.png" width="320"></td>
    <td colspan="4" align="center"><img src="docs/assets/img/sr42-case-btm.png" width="320"></td>
  </tr>
  <tr>
    <td colspan="3" align="center"><img src="docs/assets/img/sr42-cl-silver.png" width="213"></td>
    <td colspan="3" align="center"><img src="docs/assets/img/sr42-cl-blue.png" width="213"></td>
    <td colspan="3" align="center"><img src="docs/assets/img/sr42-cl-brown.png" width="213"></td>
    <td colspan="3" align="center"><img src="docs/assets/img/sr42-cl-orange.png" width="213"></td>
  </tr>
</table>

## Project Resources

- Source
  - Recovery [Fusion 360 source](Fusion360/SR42_Keyboard.f3z) file.
- Componentized, build STEP files
  - [Case Top](Fusion360/build/sr42_case_top.stp)
  - [Case Bottom](Fusion360/build/sr42_case_bottom.stp)
  - [Plate](Fusion360/build/sr42_plate.stp)
  - [Plate Foam](Fusion360/build/sr42_plate_foam.stp)


## PCB

This case is designed in conjunction with the [SR42 Keyboard PCB](https://github.com/tecsmith/sr42-keyboard-pcb).  These two projects are mutually inclusive and built as one solution.

---

## Case

### Color options

Keyboard will be made with 3 *(plus a 4<sup>th</sup> on request)* top case options, and 2 bottom case options.

#### Top Case

|| Mac Silver | Sky Blue | Bronze Brown | Burnt Orange |
|:---:|:---:|:---:|:---:|:---:|
| Color<sup>1</sup> | ![](./docs/assets/img/aaaaaa.svg) | ![](./docs/assets/img/446688.svg) | ![](./docs/assets/img/886633.svg) | ![](./docs/assets/img/cc6633.svg) | |
|| #AAA | #468 | #863 | #C63
| Panatone<sup>2</sup> | ![](./docs/assets/img/a6a9aa.svg) | ![](./docs/assets/img/486785.svg) | ![](./docs/assets/img/82643e.svg) | ![](./docs/assets/img/c96939.svg) |
|| Pantone / PMS Silver 10077 C | Pantone / PMS 2186 UP | Pantone / PMS 18-0937 TPG | Pantone / PMS 16-1448 TPG | 
| Anno | ![](./docs/assets/img/ua-satin-spanish-silver-clear.jpg) | ![](./docs/assets/img/ua-satin-reef-blue.jpg) | ![](./docs/assets/img/ua-satin-medium-bronze.jpg) | ![](./docs/assets/img/ua-satin-oriental.jpg) |
|| Spanish Silver | Reef Blue | Medium Bronze | Oriental | |

> <sup>1</sup> = This is the 3-digit hex color representation of the color, but not the actual color.<br>
> <sup>2</sup> = All attempts will be made to get as close to the Panatone color as possible, but anodization can vary, even between that same batches.

#### Bottom Case

Bottom case options will be:

- Mac Silver *(same as top case with that color option)*
- Untreated all Copper *(this **will** patina over time)*

#### Plate

- The default plates will be made in Aluminium, with the Mac Silver color.
- Other materials will be available, including:
  - FR4 Plate
  - Polycarbonate
- More materials may be added if the range extends to more production rounds, including:
  - Carbon Fiber
  - Copper

### Other components

#### USB Daughterboard

- *(1x)* [**Unified Daughterboard**](https://github.com/Unified-Daughterboard/UDB-C-EZM) C-series *(Pico EzMate variant)*

  <img src="docs/assets/img/udb_ezm.png" width="180">

#### Gasket System

- *(8x)* [**GEON Works** Tadpoles](https://geon.works/products/tadpole)

    *&lt;or&gt;*

- *(16x)* 18x3x4 mm & 18x4x3 mm *(LxHxW)* Poron Foam Gaskets *(example [from Ali](https://aliexpress.com/item/1005004199050037.html))*

#### Feet

- *(4x)* 42×6×0.5mm [Zambumon/**SKUF Feet**](https://github.com/Zambumon/SKUF)

#### Case Screws

- *(7x)* Hexagon Socket Head Cap Screws ISO 4762 - M1.6 x 5

#### Daughter Board Screws

- *(8x)* Hexalabular Socket Pan Head Screw ISO 14583 - M2 x 4

#### Plate Screws *(Optional)*

- *(4x)* M2 [*(KBDFans)* **Plate screw and standoff set** ](https://kbdfans.com/products/kbdfans-m2-3-countersunk-flat-head-screw-kit)

  <img src="docs/assets/img/kbdfans-m2-plate-screw-kit.jpg" width="320">

---

## Ideation / Inspiration

Design ideas came to me from the following designs:

- [JJWKB **Derivative** R1](https://jjwkb.com/pages/derivative-r1)
- [Connon Keys + `ai03` **Brutal V2**](https://cannonkeys.com/products/brutal-v2-1800-keyboard)


---

## License

The case design is available as open source under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International License](http://opensource.org/licenses/MIT).


&nbsp;<br>&nbsp;
---
Made with :heart: by **Silvino R.*
