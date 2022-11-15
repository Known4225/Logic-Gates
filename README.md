# Logic-Gates
A small program for building logic circuits

Install: Download LogicGates.html and run it in your browser of choice.

Usage:

Create logic circuits by summoning components with keybinds and click and drag mechanics to wire and rearrange components.
This project has support for 8 types of unique components with all the infinite possibilities of functional completeness

The full list of keybinds:

1, e, p - POWER component (input/output)

2, w, n - NOT gate

3, a - AND gate

4, q, o - OR gate

5 - XOR gate

6 - NOR gate

7 - NAND gate

8 - BUFFER gate

x - delete component

click + drag - move components or screen

space + click + drag - create wire

s + click + drag - select

s + click - add component to selection

c - copy/paste selected

scroll wheel - zoom

up and down arrows - zoom

space + scroll wheel - rotate component (coarse)

sideways arrows - rotate component (fine)

space + sideways arrows - rotate selected (fine)

k - export

l - import (it's L and not i)

h - toggle sidebar


All the data for a Logic Gates™ setup is in just 5 lists, some of which store redundant information. File sizes are around 60 bytes per component. The only way to save and load data is with k and l keybinds. Save data in separate txt files.

NOT POWER POWER 0 -11 90 -79.9 33.1 90 75.1 -59.9 90 0 0 1 0 0 0 1 0 0 1 2 0 1 0 0 1 1 0 1 3 1 2 1 0
Example XOR setup ^^

ToDo:

Undo/Redo commands (very difficult, might require compact encoding)

Configurable keybinds - possibly just in code

User interface/Sidebar - might be unecessary

Custom gate creator

Multiplexer component

Triple (or more) input gates (currently incompatible with implementation, would require large reworks)
