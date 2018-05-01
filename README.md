# Fluid Simulator (Name TBD)


| Smoke         | PIC/FLIP           |
| :-------------: |:-------------:|
| ![Smoke Sim](images/smoke.gif)      | ![Fluid Sim](images/fluid.gif) |


## How to Run
```
// Build program
mkdir build
cd build
cmake ..
make

// Run program
cd ..
cd src
./SIM <fluid or smoke>
```

**To change to 3D Fluid**
- In `main.cpp` comment out `#define TWO_DIM`

## References
- [Siggraph 2007 Course Notes](https://www.cs.ubc.ca/~rbridson/fluidsimulation/fluids_notes.pdf)
- [Aline Normoyle's Tutorial](http://www.alinenormoyle.com/TutorialFluid.html)
- [Stable Fluids by Stam](http://www.dgp.toronto.edu/people/stam/reality/Research/pdf/ns.pdf)
- [Visual Simulation of Smoke by Fedkiw, Stam, & Jensen](http://physbam.stanford.edu/~fedkiw/papers/stanford2001-01.pdf)
- [Fluid Simulation for Computer Graphics by Braley and Sandu](http://users.encs.concordia.ca/~grogono/Graphics/fluid-5.pdf)