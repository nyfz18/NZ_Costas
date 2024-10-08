Project by: Nina Zhang 

Selected cell model: neuronal model `626170421` from allen SDK database. 

`my_sim` directory and `sim.ipynb` simulates various intracellular current injections on model 626170421. Currents tested are as follows: 40 pA, 70 pA, 80 pA, 90 pA, 120 pA. Membrane potential and calcium concentration were recorded and graphed. 

`task2_analysis.ipynb` analyzes the graphs that were gathered from the experimentation of the first simulation (`my_sim`)

`my_sim02` directory and `sim2.ipynb` simulates and generates an extracellular spike waveform data set. The input for the external stimuli were provided from `neuropixel_electrode_1um.csv`. Membrane potential and calcium concentration were recorded and graphed.

`sim2_task4.ipynb` is an analysis on the extracellular AP waveform. It extracts features such as the amplitude, half-width, and EAP. 

`task3_4_analysis.ipynb` analyzes the graphs and data that were gathered from the experimentation of the second simulation (`my_sim02`)

`model_3D.ipynb` is the stretch goal. 