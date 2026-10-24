## Catalyst Keyboards

### Disclaimer
Currently the Catalyst V1 PCB schematic is untested, if you decide to build this understand the risk that the schematic may have issues. Also bear in mind that the keyboard itself hasn't been tested physically yet and may not be ergonomically sound for everyone.
***

### Goals of Catalyst

The goal of this project is to provide a much more refined and efficient solution compared to ergonomic row staggered keyboards. Typically those keyboards don't address some of the root weaknesses of the row staggered having inequality of distance to the index and pinky corners and generally being inconsistent.

The ulterior goal of the project is to provide economic options for any type of user to assemble or commission with price of components considered. It's very important to me to make the barrier to entry on ergonomic keyboards as low as possible.
***

### Future goals

My immediate future goals for the project is to add many more compatible parts with the default Catalyst46 unibody board. Multiple cases, Choc switch support, Hotswap, through hole diodes, and variants for many more common wired and wireless microcontrollers.

Post those goals I would like to have reduced key count variants, split pcb variants and then venture into more experimental variants that could be more ergonomic for some or provide functionality people ask for.
***



### The Ortholinear / Columnar staggered problem

Most of the spotlight in custom ergonomic keyboards have been centred around columnar staggered keyboards, aligning height of those columns with the length of our fingers with consideration for form and adding splay in accordance with the natural extension path of our fingers not being perfectly straight.

The main issue in this approach is that without any change in the alignment of rows you are forced to have index corners that are largely uniform. It's certainly an improvement over the worst corners in row staggered keyboards e.g. Qwerty `b` and `y` but is further away than its best corners `t` and `n`. 

Working around those issues is not impossible with alternate keyboard layouts which allow you to avoid those corners with decent success, but if you're uninterested in that you will have a worse experience than row staggered on Qwerty assuming good form.

The most common hardware solution has been reducing the pinky and inner index columns (furthest away from home) to 2 keys. This fixes the issue but now requires you to account for the missing characters with your custom config. This is much easier on alternate layouts but is very annoying for Qwerty and definitely will take time to retrain (not worth the effort at this point to maintain Qwerty in my opinion).
***

### Where symmetrical stagger fits

The largest issues with row staggered has been its inconsistent quality, left hand bottom row can be very awful if not properly accounted for and it's common for people to injury themselves or adapt to its issues in form because they don't avoid common stretches in that area. 

Symmetrical stagger comes in multiple forms but the one I have chosen brings all index corners equidistant but also closer to home compared to ortholinear / column staggered keyboards. 

The other benefit of adding row stagger is a lateral splay to the upper pinky key, this comes at the cost of adding the exact same splay to the bottom pinky key which in both alternate layouts and Qwerty are rarely used.
***

### License

This Repository is licensed under the CERN-OHL-V2-S the terms of which can be found in the License.txt document in this repository.
***