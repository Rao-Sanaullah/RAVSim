

![RAVSim: Run-time Analysis and Visualization Simulator for SNN Models](https://github.com/Rao-Sanaullah/RAVSim/blob/main/RAVSim%20logo.png)

RAVSim is an interactive virtual experiment environment for the simulation and analysis of spike neural network models. 
 - RAVSim v1.0, solely designed with the aim of helping early-stage researchers and students to fully understand the mechanism of SNNs where users can interact with the simulator in run-time by providing the essential parameters. There are a lot of parameters involved in the designing of SNNs and it is extremely important to understand the significance of these parameters for designing optimal neural networks. Thus, it is necessary to visualize the value of this parameter before applying it directly to the hardware. One should be aware of which parameters are essential, how the parameters interact and are dependent on each other, the optimal values of these parameters for achieving accurate and efficient SNNs to be as realistic as biological neurons [1].
 - RAVSim v1.1: It is not necessary for the end-user to know how to code backends with RAVSim when manipulating RGB image-based datasets. A face dataset without a mask and a wild image dataset with a mask is currently used for the implementation of the image classification algorithm.
 - A significant benefit of RAVSim v1.1 is its ability to allow end-users to import their own format of downloaded images without any extensions and to create a scalable database without integrating with any third-party APIs.  

RAVSim is developed on a graphical programming language platform called LabVIEW (Laboratory Virtual Instrument Engineering Workbench)[2].


The RAVSim is an open-source simulator and it is available publicly at [https://www.ni.com/de-de/support/downloads/tools-network/download.run-time-analysis-and-visualization-simulator--ravsim-.html#443936]. The video demo of RAVSim v1.0 can also be seen at [https://www.youtube.com/watch?v=Ozv0MXXj89Y].

**Requirements**
- You need to have a graphical programming approach LabVIEW Runtime 2021 or above.
- A minimum computer requirement:
  
  • Processor: i3 CPU @ 2.3 GHz
  
  • RAM: 4.0 GB
  
  • System Type: 32/64-bit OS
  
  • Operating System: Mac OS, Window

To install Runtime LabVIEW:
https://www.ni.com/kokr/support/downloads/softwareproducts/download.labview.html#305931

And for further installation procedures please follow the user manual.

Image Classification Algorithm used in RAVSim results using different sets of neurons in hidden layers of Spiking Neural Nets.
 
![Model Accuracy](https://github.com/Rao-Sanaullah/RAVSim/blob/main/results_v1.1.jpg)


WTA Network: List of conditions:

  1- Fully connected network

  ![Fully connected network](https://github.com/Rao-Sanaullah/RAVSim/blob/main/Apr-06-22%20Time%2012%2049%2051.png)

  2- source != target index neurons

  ![source != target index neurons](https://github.com/Rao-Sanaullah/RAVSim/blob/main/Apr-06-22%20Time%2012%2049%2053.png)
  
  3- source == target index neurons

  ![source == target index neurons](https://github.com/Rao-Sanaullah/RAVSim/blob/main/Apr-06-22%20Time%2014%2031%2054.png)

Mixed Signal Plot:

  ![Mixed Signal Plot](https://github.com/Rao-Sanaullah/RAVSim/blob/main/Apr-06-22%20Time%2012%2049%2058.png)

References:

[1]. Sanaullah, Koravuna, S., Rückert, U., Jungeblut, T. (2022). SNNs Model Analyzing and Visualizing Experimentation Using RAVSim. In: Iliadis, L., Jayne, C., Tefas, A., Pimenidis, E. (eds) Engineering Applications of Neural Networks. EANN 2022. Communications in Computer and Information Science, vol 1600. Springer, Cham. https://doi.org/10.1007/978-3-031-08223-8_4

[2]. NI LabVIEW, https://www.ni.com/de-de/shop/labview.html.

[3]. Gr gory Dumont, Jacques Henry, and Carmen Oana Tarniceriu. Noisy threshold in neuronal models: connections with the noisy leaky integrate-and-fire model. Journal of mathematical biology, 73(6):1413–1436, 2016.

[4]. Yanqing Chen. Mechanisms of winner-take-all and group selection in neuronal spiking networks. Frontiers in computational neuroscience,11:20, 2017.


For any help, please contact

Sanaullah (sanaullah@fh-bielefeld.de)
