# Steezy60

Steezy60 is a 60% PCB in two versions: one for SMK gen 2 switches one for ALPS-compatible switches. Compatible with standard tray-mount cases.

## Some features:
- Extensive layout support for use with vintage keycap sets
- QMK
- Simple VIA support (just common layout options)
- USB C
- RGB underglow
- Cherry PCB-stab support for most layout options
- USB horizontal placement is classic GH60, same as GH60, plain60, voyager60 etc.
- JST-connector for daughter board (two different positions, one for bakeneko, one for cases compatible with wilba PCB.)

### SMK:
- Support for MX-mount switch on 6.25u and 7u spacebar position, this to enable use of silenced MX-switch on large spacebars. (no onion chopping spacebar sound)
- Support for some of the weird Alps switch positions for compatibility with SMK Alps mount switches and classic Alps keysets (not for cherry stem SMK switches).

## Altium view of ALPS PCB
![alt text](./readme-images/Steezy60-Alps_Rev_A5.jpg "PCB View - Rev A")

## Altium view of SMK PCB
![alt text](./readme-images/Steezy60-SMK_Rev_A5.jpg "PCB View - Rev A")

## Layout support:
![alt text](./readme-images/layout_support_A3.jpg "Layout support")

## Instructions for manufacturing.

The Project can be assembled in three different configurations:
1. Traditional tray mount with USB-C connector
2. Daughter board connector in two different configurations:
	- Bakeneko position
	- Position for cases made for wilba PCB's (not tested yet!)
In most versions, a "all" configuration is also included, this is not a "one config fits all", it's intended to be used for making your own config.

## For ordering:
The following files are needed for the PCB Fab:
- BOM (contains component specifications)
- Pick and Place (contains component placement data)
- Gerber (contains PCB drawings and drill files)
- (optional) Assembly drawing, for manual assembly

Select the files for the desired configuration. Gerber and Pick and Place files will be the same for all three configurations, BUT!, you need to select the correct BOM for your configuration.

If you want to make a bakeneko compatible PCB, select the bakeneko BOM when ordering PCB's etc.

## For clarity
- Revision: When updating the PCB I bump the revision. The revision is specified with a letter and a number. For big changes, the letter is changed (usually also include code changes), for minor changes, only the number is bumped.
- Version: Version specifies different switch types, PCB's specific to certain cases etc.
- Configuration: Different assembly options for a specific version of steezy60 

## Revisions:

### SMK 
- Rev A1: Initial prototype, issues: had 2 alps footprints left over from other pcb.
- Rev B1: Changed processor to atmega32u2, changed layout support, removed some mounting holes (for chinese cases).
- Rev A2: Rotated left shift stabilizer for better universal plate support, reset revision designator to A (old A-revision does not exist anymore), to match Steezy60-Alps. Removed PCB name and logo on top, removed flash command from silk.
- Rev A3: Added support for Canon Spherical Keycaps, improved routing, added support for rubber-band mouting.
- Rev A4: Moved daughter board connector to allign with other projects.
- Rev A5: Moved daughter board a bit to fit better in bakeneko cases, Added cutout for bakeneko V3 (untested), Added assembly option for PCB to fit in wilba cases (untested).

### ALPS
- Rev A1: Initial prototype based on SMK-version.
- Rev A2: Rotated left shift stabilizer for better universal plate support, removed PCB name and logo on top, removed flash command from silk.
- Rev A3: Added support for Canon Spherical Keycaps, improved routing, added support for rubber-band mouting.
- Rev A4: Moved daughter board connector to allign with other projects.
- Rev A5: Moved daughter board a bit to fit better in bakeneko cases, Added cutout for bakeneko V3 (untested), Added assembly option for PCB to fit in wilba cases (untested).

<a href='https://ko-fi.com/4pplet' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' />
