# Project Proposal Random Number Generator


Make 2 Virtual Planes

5 x 5

```
XXXXX
XXXXX
XXXXX
XXXXX
XXXXX
```


Smash them together like an Oreo

In between the planes we will create an object in the 3x3 slot

The object will 'take space'

Space cant be owned by more than one object

Create a function which will make object move depending on paths of least resistance

Resistance will be a factor but will equal zero

Objects will only be able to move 1 slot space at a time, this will represent how resistance works

New Objects will be inserted into the 3x3 slot exactly in the same position the other one was sitting in before it

The old object will be forced to move to ONE new plane position

The plane will want to be filled before any objects leave the plane this will be included as part of how the resistance works, it will be called the viscosity function

The random output will be the position at which the 26th object leaves the plane space
