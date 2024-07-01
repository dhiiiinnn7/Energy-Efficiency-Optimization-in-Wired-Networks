# Energy Efficiency Optimization in Wired Networks

## Overview

This project explores reducing energy usage in wired backbone networks through the simulation of a simplified GÉANT Network. Using NetSim, the OSPF protocol is implemented under low and high traffic conditions, enhanced with smart sleeping techniques for routers. The analysis focuses on evaluating energy consumption and network performance to demonstrate the effectiveness of strategic router inactivity.

## Table of Contents

- [Project Structure](#project-structure)
- [Project Description](#project-description)
- [Tools and Techniques](#tools-and-techniques)
- [Installation](#installation)
- [Running the Analysis](#running-the-analysis)
- [References](#references)
- [License](#license)

## Project Structure

- `Energy Efficiency Optimization in Wired Networks Analysing the Impact of Smart Sleeping Techniques on OSPF Protocol Performance.pdf`: Detailed report on the project, methodologies, and findings.
- `ENERGY CONSUMPTION.xlsx`: Contains data on energy consumption under different scenarios.
- `Packet Delay.xlsm`: Contains data on packet delays in the network.
- `High Traffic Simulation - Configuration.netsim`: NetSim configuration file for high traffic simulation.
- `High Traffic Simulation with Smart Sleeping - Configuration.netsim`: NetSim configuration file for high traffic simulation with smart sleeping.
- `Low Traffic Simulation - Configuration.netsim`: NetSim configuration file for low traffic simulation.
- `Low Traffic Simulation with Smart Sleeping - Configuration.netsim`: NetSim configuration file for low traffic simulation with smart sleeping.

  ## Project Description

The project investigates methods to improve energy efficiency in wired backbone networks using smart sleeping techniques in the OSPF routing framework. The network model is based on a simplified version of the GÉANT Network, which connects European research and education institutes. Various scenarios with low and high traffic loads are analyzed, both with and without smart sleeping implementations, to estimate potential energy savings and assess the impact on network performance.

Key findings include:
- **Energy Savings**: Smart sleeping techniques reduce energy consumption by approximately 22.7% in low traffic scenarios and 24% in high traffic scenarios.
- **Network Performance**: Smart sleeping introduces minimal initial latency but stabilizes, ensuring no significant impact on overall network performance.

## Tools and Techniques

The project utilizes several tools and techniques, including:
- **NetSim**: For simulating the network and analyzing performance metrics.
- **Excel**: For organizing and analyzing data on energy consumption and packet delays.

## Installation

### Clone the Repository

   ```bash
   git clone https://github.com/dhiiiinnn7/Energy-Efficiency-Optimization-in-Wired-Networks.git
   cd Energy-Efficiency-Optimization-in-Wired-Networks
  ```
### Install Dependencies

This project primarily uses NetSim and Excel for simulations and data analysis. Ensure these tools are installed on your system.

## Running the Analysis

To run the analysis, follow the procedures outlined in the detailed report. This involves setting up the network simulation in NetSim, running the scenarios with and without smart sleeping, and analyzing the results using the provided Excel files. Use the appropriate configuration files for each scenario:

- High Traffic Simulation - Configuration.netsim
- High Traffic Simulation with Smart Sleeping - Configuration.netsim
- Low Traffic Simulation - Configuration.netsim
- Low Traffic Simulation with Smart Sleeping - Configuration.netsim

## References
Refer to the detailed report provided in Energy Efficiency Optimization in Wired Networks Analysing the Impact of Smart Sleeping Techniques on OSPF Protocol Performance.pdf for an in-depth analysis, including:

- Estimating energy consumption in wired networks.
- Power-proportional networking and traffic optimization.
- Enhancing network energy efficiency through sleep-scheduling.
- Critical evaluation of network performance and energy efficiency.

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.
