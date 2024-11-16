The files here simulate a microcircuit model of a hippocampal pyramidal cell and interneuron in Brian simulator. This was a masters thesis project and the abstract for the same is as follows:

Abstract: 

The hippocampus plays a critical role in cognitive processes such as memory encoding, driven by the precise timing of inhibitory and excitatory signals within its neuronal circuits. Disruptions in these signals, particularly due to demyelination, can lead to alterations in the rhythmic oscillations essential for proper brain function. 
This thesis investigates the impact of synaptic delays on theta rhythm modulation within a hippocampal microcircuit comprising of pyramidal cells and fast-spiking interneurons. Using computational modelling, a feedforward circuit of one two-compartment Pinsky-Rinzel model for pyramidal neurons and one Wang-Buzsáki model for interneuron was made. 
The circuit simulates the effects of varying synaptic conductance and delays on the changes in activity of the pyramidal cell. The model reveals that even minor delays in inhibitory signal can disrupt the synchrony required for excitatory and inhibitory balance of activity. By analysing the firing rates, inter-spike intervals, 
activity patterns pyramidal cells under different synaptic delay conditions, power spectrums and correlations, this project demonstrates how demyelination-induced delays in inhibitory input may lead to the slowing or disruption of theta rhythms. The findings highlight the critical role of maintaining proper network dynamics, 
providing a possible explanation for underlying disruption of theta rhythm due to demyelinated interneurons.

The files here include:
1. The complete microcircuit model named FF_Circuit
2. Individual cell models named FN_Int and FN_PC
3. Data analysis files for both dendritic and somatic inhibiton
4. A MATLAB to Python converted script to change the sampling rate of the input of input current
