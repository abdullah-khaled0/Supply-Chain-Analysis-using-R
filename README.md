# Supply Chain Analysis

![](https://png.pngtree.com/thumb_back/fw800/background/20230722/pngtree-futuristic-automobiles-and-digital-supply-chain-3d-rendering-and-illustrator-design-image_3868888.jpg)

## Overview
This repository provides an analysis of **DataCo Global's** supply chain data, covering key areas such as **Provisioning, Production, Sales,** and **Commercial Distribution**. The analysis leverages **R** for data manipulation and visualization, providing insights to improve supply chain efficiency.

## Dataset
### 1. Structured Data:
- **DataCoSupplyChainDataset.csv**: Contains data on various supply chain processes, including inventory, production, and sales performance.

### 2. Variable Description:
- **DescriptionDataCoSupplyChain.csv**: Contains detailed descriptions of each variable found in the structured dataset.

## Project Goals
- **Exploratory Data Analysis (EDA)**: Understand trends and performance in supply chain operations.
- **Visualization**: Create intuitive visualizations to showcase trends and findings.


## Prerequisites
Before running the analysis, ensure that R and the necessary packages are installed.

### Install Required R Packages
Use the following commands in your R environment to install the required packages:

```r
# Install necessary packages if not already installed
install.packages(c("tidyverse", "skimr", "corrplot", "maps", "ggmap"))
install.packages("gridExtra")
install.packages("plotly")
