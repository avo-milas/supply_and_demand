<a id="readme-top"></a>
  <h1 align="center">supply_and_demand</h1>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is implemented as part of the Computer Workshop in Economics course in the "Economics and Data Analysis" program at HSE University.

To bring a market for a particular good into equilibrium, a certain number of interactions between sellers and buyers must take place for both sides to adjust their expectations and actions. This project examines this process within the framework of a single commodity.

In the basic version of the presented model, each seller has a minimum price below which they are not willing to sell the product, and each buyer has a maximum purchasing price. Their expected prices are changing within the constraints of these limiting prices. In each period, a random pair of seller-buyer is selected,  they interact, resulting in them adjusting their expectations regarding the buying and selling prices respectively for the following periods.

Then, a series of complexities are introduced. Noise is added before each period, causing the limiting prices to change. Sellers are given the ability to sell multiple items instead of just one, and a black market emerges.

Each part consists of a description of the interaction, visualization of the model, and intuition regarding the obtained results.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

necessary libraries:
- graphviz
- tqdm

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

In each model block, the parameter values can be changed as shown in the image below:

<img src="https://github.com/avo-milas/supply_and_demand/blob/main/parameters.png" alt="parameters" width="400" />

The following are illustrations of the operation of the model with random parametrs:

1. Dynamics of expexted prices

<img src="https://github.com/avo-milas/supply_and_demand/blob/main/exp_prices.png" alt="exp_prices" width="500" />

2. Dynamics of deals share
   
<img src="https://github.com/avo-milas/supply_and_demand/blob/main/deals_perc.png" alt="deals_perc" width="500" />

3. Supply and demand at a given moment

<img src="https://github.com/avo-milas/supply_and_demand/blob/main/sup_dem.png" alt="sup_dem" width="500" />

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Alina Salimova - [@avo_milas](https://t.me/avo_milas) - avo_milas@mail.ru

Project Link: [https://github.com/avo-milas/supply_and_demand](https://github.com/avo-milas/supply_and_demand)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
