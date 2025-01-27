
These are the NEURON files for 10 different models of a reduced L5
pyramidal neuron. The parameters were obtained by automatically
fitting the models to experimental data using a multi objective
evolutionary search strategy. Details on the algorithm can be found at
www.g-node.org/emoo and in Bahl et al. (2012).

For testing: 

- Compile the channels with nrnivmodl (this model was developed under
  linux). You might then have to correct the path in reduced_model.hoc
- Test regular firing and ca-Spike examples: nrngui example1.hoc etc.
  By default the auto-launch button on ModelDB will start this file.
  After the example1.hoc is started press Init & Run.  You should see:

<img src="screenshot.png" alt="screenshot" width="550" height="405">

- You can also load the models directly: hoc files init_models_with_ca
  are models with calcium parameters properly set, while the hoc files
  in init_models_without_ca describe models with inactivated dendritic
  calcium dynamics.

Please contact me if you have problems or questions concerning the
models or the search algorithm.

Armin Bahl

References:

Bahl, A., Stemmler, M. B., Herz, A. V. M., & Roth, A. (2012).
Automated optimization of a reduced layer 5 pyramidal cell model based
on experimental data. Journal of Neuroscience Methods, 210(1), 22-34.
doi:10.1016/j.jneumeth.2012.04.006
