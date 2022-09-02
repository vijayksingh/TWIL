# TWIL
Will add notes and references to things that i've learn on daily basis


## 1 Exploration:

### Maths

Contains links of most math explorables which are easy to understand.

[Linear Algebra](https://www.youtube.com/playlist?list=PLg-OiIIbfPj3Wldtb0QfV0Yse8tL2nLGm)


### CS

**Functional Programming**

[Monad](https://youtu.be/C2w45qRc3aU)

## 2 Notes

### CSS

How to design your UI components local CSS ? <br>
🎥 [CSS Architecture for Modern Web Applications by Mike Riethmuller](https://youtu.be/ZWPMzJfJHnc)

- [ ] TODO: Add the notes here for the above video.

## 3 Insights / Tips


## Courses 
### Build a Component Library

**Component Boundaries**
- First step in creating a new component library is identifying which component to build.

We will use concept of Atomic Design and learn how it can be used by library authors to identify shareable components. 

In Atomic Design, user experiences can be broken into five distinct levels: 
- Atoms
- Molecules
- Organisms
- Templates
- Pages

_Atoms :_
Building blocks of matter.   
Include standalone HTML elements as well as more abstract concepts like colors, typography, and spacing. 
They are flexible, but they're often too abstrac to provide a consister user experience. (Tailwing could be a usefule implementation for this concept)

_Molecules :_
Molucules are composed of smaller atoms.   
They can combine atomic styles like color and spacing with more complex concpets like accessibility, layout, and internal state. (Ex: Buttons, Inputs, Radio, Tabs, Drop-Down)

> Molecules are the most common types of shared component.

_Organisms, Templates, Pages :_
They continue to build on each other to provide more complex experiences.   
Works well for design System but often include business logic and other complexity that limits the flexibility of our component library. 
