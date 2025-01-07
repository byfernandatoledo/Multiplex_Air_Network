# COVID-19 impact in the Brazilian Multiplex Air Transportation Network

## How to run the experiment

- Step 1. Install Microsoft R Open (v. 4.0.2)
- Step 2. Install the MuxViz R package, that can be downloaded in: [MuxViz](https://github.com/manlius/muxViz), following the installation steps
- Step 3. The Graphical User Interface version of MuxViz can be used accessing the old version of MuxViz, available in the gui-old folder
- Step 4. Make sure de working directory of your machine is correct (using getwd() and setwd() )
- Step 5. Open the GUI interface of MuxViz in R environment: source('muxVizGUI.R')
- Step 6: Select the characteristics of the network to be build and the dataset according to the input format. Dataset for the network of 2019 and 2020 are available.
- Step 7: Run the network to calculate the network topological charactericts.

## Dataset for this paper is available in the dataset folder.

- Subfolder [Cias2019](https://github.com/byfernandatoledo/Multiplex_Air_Network/tree/main/dataset/Cias2019) contains the edges information for each layer (airline), configuration of layers and layout providing the node label (airport IATA code) for the year 2019.
- Subfolder [Cias2020](https://github.com/byfernandatoledo/Multiplex_Air_Network/tree/main/dataset/Cias2020) contains the same data as above for the year 2020.


