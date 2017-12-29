# FLoRa
FLoRa (Framework for LoRa) is a simulation framework for carrying out end-to-end simulations for LoRa networks. 
It is based on the [OMNeT++](https://omnetpp.org/) network simulator and uses components from the [INET framework](https://inet.omnetpp.org/) as well.

FLoRa allows the creation of LoRa networks with modules for LoRa nodes, gateway(s) and a network server. 
Application logic can be deployed as independent modules that are connected with the network server. 
The network server and nodes support dynamic management of configuration parameters through Adaptive Data Rate (ADR). 
Finally, the energy consumption statistics are collected in every node.
