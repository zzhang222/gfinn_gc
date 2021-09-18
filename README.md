# gfinn_gc
Gas container example in the GFINN paper

To run the gas container example, you need to run 
python example_gc.py --net=generic2b 
or 
python example_gc.py --net=generic2b

We are confident that our implementation should not have obvious problems because we checked the dE/dt and dS/dt and it looks like the laws of thermodynamics are satisfied. The consistency condition and the skew-symmetry/positive semidefiniteness of L/M are also satisfied.
