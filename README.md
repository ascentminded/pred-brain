# pred-brain
Building microcircuits that simulate how the predictive brain works. Incorporating hierarchy, uncertainty estimation and prediction error across multiple brain regions using just pure python. This was done without relying on pre-existing bayesian brain packages like PyHGF, etc.

In Part I, I build a basic version that self updates its predictions based on prediction error calculated against new input. It also implements precision-weighted updating.

Part II, I build upon this, using OOP and Neuron/interneuron groups -- Pyramidal (2 layered) , PV, SST, VIP groups and their many interactions to build a more robust and neurally accurate predictive system. This increases feedback/ top-down control, inhibitory action, precision-weighted updates, and more.

Check out the .ipynb files for more information, a more thorough description of the goals and processes, and a bibliography in Part II. It is perfectly ok to begin with part II, but feel free to look through Part I if lost -- it's the backbone on which Part II was built.

Thanks for dropping by,
~NB
