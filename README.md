

![RAVSim: Run-time Analysis and Visualization Simulator for SNN Models](https://github.com/Rao-Sanaullah/RAVSim/blob/main/RAVSim%20logo.png)

RAVSim stands for Run-time Analysis and Visualization Simulator. It is solely designed with the aim of helping early-stage researchers and students to fully understand the mechanism of SNNs where users can interact with the simulator in run-time by providing the essential parameters. Practically, RAVSim is used to simulate LIF by using a noisy input model.
RAVSim is developed on a graphical programming language platform called LabVIEW (Laboratory Virtual Instrument Engineering Workbench)

Leaky Integration and Fire by using the Noisy Input model (NLIF) [2] has been implemented to perform run-time simulation. Furthermore, it is capable of Spike detection by using the continuous noisy input, Spike detection by using input current, and generating a winner takes all network (WTA) [3], which establishes communication between the neurons.

The RAVSim (v1.0) is an open-source simulator and it is available publicly at [https://www.ni.com/de-de/support/downloads/tools-network/download.real-time-analysis-and-visualization-simulator--ravsim-.html#443936]. The video demo of RAVSim can also be seen at [https://www.youtube.com/watch?v=Ozv0MXXj89Y].

**Requirements**
- You need to have a graphical programming approach LabVIEW Runtime 2021 or above.
- A minimum computer requirement:
  
  • Processor: i3 CPU @ 2.3 GHz
  
  • RAM: 4.0 GB
  
  • System Type: 32/64-bit OS
  
  • Operating System: Mac OS, Window

To install Runtime LabVIEW:
https://www.ni.com/kokr/support/downloads/softwareproducts/download.labview.html#305931

WTA Network: List of conditions:

  1- Fully connected network

  ![Fully connected network](https://github.com/Rao-Sanaullah/RAVSim/blob/main/Apr-06-22%20Time%2012%2049%2051.png)

  2- source != target index neurons

  ![source != target index neurons](https://github.com/Rao-Sanaullah/RAVSim/blob/main/Apr-06-22%20Time%2012%2049%2053.png)

Mixed Signal Plot:

  ![Mixed Signal Plot](https://github.com/Rao-Sanaullah/RAVSim/blob/main/Apr-06-22%20Time%2012%2049%2058.png)

For any help, please contact

Sanaullah (mr.raosanaullah@gmail.com)
