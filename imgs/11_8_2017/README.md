# Build log dated 11th August, 1947

Today, a breadboard prototype of the circuit on the previous commit was done. The results, as shown by the images, were pathetic and had too much ripple and a very unstable feedback loop. The efficiency of the converter was around 71% and it was drawing 0.36 A from a 9V source, powering a 10E load at 5v.

A closer analysis has to be done on the LM2596 as well as the selection of external components. I believe the feedback resistors were too close to the breadboard and hence they were picking up inductive voltages. Will analyze in the coming days.
