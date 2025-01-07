# COVID-19 impact in the Brazilian Multiplex Air Transportation Network

This repository contains the experimental data from the paper "COVID-19 impact in the Brazilian Multiplex Air Transportation Network" published in IEEE Latin America Transactions by Fernanda Toledo and Nelson Ebecken, from the Federal University of Rio de Janeiro, Civil Engineering Department, Rio de Janeiro, Brazil.

## Running the experiment

### Dataset for this paper is available in the dataset folder

- Subfolder [Cias2019](https://github.com/byfernandatoledo/Multiplex_Air_Network/tree/main/dataset/Cias2019) contains the edges information for each layer (corresponding each airline), configuration of layers and layout information providing the node label (airport ICAO code) for the year 2019.
- Subfolder [Cias2020](https://github.com/byfernandatoledo/Multiplex_Air_Network/tree/main/dataset/Cias2020) contains the same data as above for the year 2020.

### MuxViz Setup 
- Install Microsoft R Open (v. 4.0.2)
- Install the MuxViz R package, that can be downloaded in: [MuxViz](https://github.com/manlius/muxViz), following the installation steps
- Copy the dataset subfolders to the following directory:
```sh
"C:/path_to/muxviz-master/gui-old/data"
```
- The Graphical User Interface version of MuxViz can be used accessing the old version of MuxViz
- Set the R working directory to the MuxViz folder on your computer as the example below 
```sh
> setwd("C:/path_to/muxviz-master/gui-old")
```
- Open the GUI interface of MuxViz in R environment with the following command: 
```sh
> source('muxVizGUI.R')
```

### Building the network and analysis
- In the config file window click browse and select the config file of the network to be build (for 2019 or 2020).
- In the network type window, select directed and weighted network. Then click import network.
- In the diagnostics tab, plot each of the characterics available in the Statistics subtab.
- The results from the tables in the paper can be obtained by running the calculations in the Diagnostics tab: Statistics, Correlation, Centrality, Connected Components.

  
