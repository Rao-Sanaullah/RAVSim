

![RAVSim: Run-time Analysis and Visualization Simulator for SNN Models](https://github.com/Rao-Sanaullah/RAVSim/blob/main/RAVSim%20logo.png)

RAVSim, short for Run-time Analyzing and Visualization Simulator, is an interactive tool designed for the analysis and simulation of spiking neural network models. Developed on the LabVIEW (Laboratory Virtual Instrument Engineering Workbench) platform [1], RAVSim uses a multi-core architecture to provide users with a versatile environment for exploring the behavior of spiking neural networks.

RAVSim offers both deterministic (by solving Ordinary Differential Equations (ODEs)) [2] and stochastic (using stochastic leaky integrate-and-fire (LIF) neurons algorithm) simulations [3]. This dual simulation capability enables users to gain a comprehensive understanding of spiking neural network dynamics through various approaches. What sets RAVSim apart from other tools is its unique ability to execute, analyze, extract, and validate models using image-based datasets. This empowers users not only to analyze and simulate spiking neural networks but also to create custom datasets tailored to their specific image pixel, quality, and extension preferences.
Furthermore, RAVSim has recently introduced new features to enhance the user experience. It now offers a convenient option to generate weights for your spiking neural network models using image classification training. This feature eliminates the need for complex coding; you can simply utilize RAVSim to train your model and generate the required weights effortlessly.

In addition to weight generation, RAVSim facilitates the comparison of different spiking neural network models. Users can dynamically update sets of parameter values for each model at runtime and obtain comparative results. This functionality aids in identifying the most suitable model for your specific spiking neural network application.

The RAVSim is an open-source simulator and it is available publicly at [https://www.ni.com/de-de/support/downloads/tools-network/download.run-time-analysis-and-visualization-simulator--ravsim-.html#443936] (RAVSim v2.0 is under-review by LABView team). To learn how to effectively use this tool at runtime experiments, this document (https://github.com/Rao-Sanaullah/RAVSim/blob/main/User-Manual/RAVSim_v2..0_usermanual.pdf) provides a comprehensive guide on using RAVSim for performing run-time experiments. You can also watch a video demonstration at the following link:

1) RAVSim v1.0: https://www.youtube.com/watch?v=Ozv0MXXj89Y
2) RAVSim v2.0: https://www.youtube.com/watch?v=J9UR2IUA5Bc

   
**Requirements**
- You need to have a graphical programming approach LabVIEW Runtime 2021 or above.
- A minimum computer requirement:
  
  • Processor: i3 CPU @ 2.3 GHz
  
  • RAM: 8.0 GB
  
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

[1]. 	NI LabVIEW,  https://www.ni.com/de-de/shop/labview.html. 
[2]. 	Gardner, B., Gr¨uning, A.: Supervised learning in spiking neural networks for precise temporal encoding. PloS one 11(8), e0161335 (2016)
[3]. 	Morro, A., Canals, V., Oliver, A., Alomar, M.L., Gal´an-Prado, F., Ballester, P.J., Rossell´o, J.L.: A stochastic spiking neural network for virtual screening. IEEE transactions on neural networks and learning systems 29(4), 1371–1375 (2017)

[5]. 	Sanaullah, Koravuna, S., Rückert, U., & Jungeblut, T. (2022, June). SNNs model analyzing and visualizing experimentation using RAVSim. In International conference on engineering applications of neural networks (pp. 40-51). Cham: Springer International Publishing
[6]. 	Sanaullah, Koravuna, S., Rückert, U., & Jungeblut, T. (2023). Evaluation of Spiking Neural Nets-Based Image Classification Using the Runtime Simulator RAVSim. International Journal of Neural Systems, 2350044-2350044.
[7]. 	Sanaullah, Koravuna, Shamini, Ulrich Rückert, and Thorsten Jungeblut. "Exploring spiking neural networks: a comprehensive analysis of mathematical models and applications." Frontiers in Computational Neuroscience 17 (2023).



For any help, please contact

Sanaullah (sanaullah@hsbi.de)
