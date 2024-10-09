Project by: Nina Zhang 

Selected cell model: neuronal model `626170421` from allen SDK database. 

`my_sim` directory and `sim.ipynb` simulates various intracellular current injections on model 626170421. Currents tested are as follows: 40 pA, 70 pA, 80 pA, 90 pA, 120 pA. Membrane potential and calcium concentration were recorded and graphed. 

`task2_analysis.ipynb` analyzes the graphs that were gathered from the experimentation of the first simulation (`my_sim`)

`my_sim02` directory and `sim2.ipynb` simulates and generates an extracellular spike waveform data set. The input for the external stimuli were provided from `neuropixel_electrode_1um.csv`. Membrane potential and calcium concentration were recorded and graphed.

`sim2_task4.ipynb` is a continuation of the second simulation (`my_sim02`), and is an analysis on the extracellular AP waveform. It extracts features such as the amplitude, half-width, and EAP. 

`task3_4_analysis.ipynb` analyzes the graphs and data that were gathered from the experimentation of the second simulation (`my_sim02`)

`stretch.ipynb` is the stretch goal. The animation is saved as `somatic_v_dynamics.mp4`. With `matplotlib` and its animation feature, I created an animation of a current injection with these following parameters: 

`amp` = 0.09 nA 
`delay` = 200 ms 
`duration of current` = 300 ms 
`total simulation` = 500 ms 

`stretch_analysis.ipynb` is the analysis of the stretch goal from `stretch.ipynb` and its output, `somatic_v_dynamics.mp4`. 

`images` holds the graphs for the various experiments. `626170421` is the files from the original download of the allen SDK database. 