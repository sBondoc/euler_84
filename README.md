# euler_84

Simple Euler's method utility for TI-84. Great for doing your B/C homework. ;)

## Getting Started

Follow these instructions to use this utility on a physical TI-84 or an emulator with a TI-84 ROM image loaded. The one referenced in this ReadMe is **jsTIfied**, an online graphing calculator emulator that can be found at [Cemetech.net](https://www.cemetech.net/projects/jstified/).

### Prerequisites

#### Calculator

* [TI Connect™ Software](https://education.ti.com/en/software/details/en/B59F6C83468C4574ABFEE93D2BC3F807/swticonnectsoftware) - Software for sending the program to the calculator

* [USB Mini B Cable](https://images-na.ssl-images-amazon.com/images/I/71570Bmv81L._SX355_.jpg) - Cable connecting the calculator to the computer

#### Emulator

* [TI-84 ROM Image](https://www.ticalc.org/programming/emulators/romdump.html) - A ROM image needs to be loaded onto the emulator for it to work

## Installation

Use TI Connect™ to send the `EULER.8xp` file to your calculator. You can also read the code in the `raw.txt` file of the repository and manually write it on your calculator if you're familiar with TI-BASIC.

## Usage

**1.)** Input the derivative expression in terms of `X` and `Y` into `y`<sub>`1`</sub> of the `Y=` window.

**2.)** Run the program `EULER` in the programs menu.

**3.)** Input values.
  * `X(0)` is the initial value of *x*
  * `Y(0)` is the initial value of *y*
  * `X(N)` is the target value of *x*
  * `H` is the step
  
### Example

*Use Euler's Method to approximate the value of y when x = 1 if y' = 3y-1 and y(0) = 1 with a step of 0.25.*

  * `X(0)` = 0
  * `Y(0)` = 1
  * `X(N)` = 1
  * `H` = 0.25


## Built With

* [TI-84 Plus](https://education.ti.com/en/products/calculators/graphing-calculators/ti-84-plus) - Calculator used to make the program
* [TI Connect™ Software](https://education.ti.com/en/software/details/en/B59F6C83468C4574ABFEE93D2BC3F807/swticonnectsoftware) - Used to export the program from the calculator to the computer in .8xp format
* [Source Coder 3 (Cemetech.net)](https://www.cemetech.net/sc/) - Simplifies debugging process

## Acknowledgments

* I have no idea what I'm doing
