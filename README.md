# 2401FTDS_Regression_Project

![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

<div id="main image" align="center">
  <img src="https://github.com/marcmarais/2401FTDS_Regression_Project/blob/main/agri_image.png" width="450" height="300" alt=""/>
</div>

## Table of contents

- [1. Project Overview](#project-description)
- [2. Dataset](#dataset)
- [3. Packages](#packages)
- [4. Environment](#environment)
- [5. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>

A team of environmental consultants and data scientists has been tasked by a coalition of agricultural stakeholders to analyze and predict the impact of CO2 emissions from the agri-food sector on climate change. The coalition comprises policymakers, agricultural businesses, and environmental organizations. The project aims to understand the effects of agricultural activities on climate change and develop strategies for sustainable practices.

By utilizing a comprehensive dataset compiled from the Food and Agriculture Organization (FAO) and the Intergovernmental Panel on Climate Change (IPCC), the team will explore various emission sources. Regression analysis will be employed to predict temperature variations. The findings and recommendations will provide actionable insights for stakeholders.

Upon project completion, the team will have a thorough understanding of the impact of agricultural activities on CO2 emissions and climate change. The insights and recommendations will contribute to the ongoing efforts to promote sustainability within the agri-food sector, offering valuable guidance to the involved stakeholders.

## 2. Dataset <a class="anchor" id="dataset"></a>

Emissions from the agri-food sector play a crucial role in climate change, as they represent a significant share of global annual emissions. The dataset highlights the substantial contribution of the various sources of emissions. Therefore, it is essential to understand and address the environmental impact of the agri-food industry to mitigate climate change and promote sustainable practices within this sector.

**Dataset Features:**

- Savanna fires: Emissions from fires in savanna ecosystems.
- Forest fires: Emissions from fires in forested areas.
- Crop Residues: Emissions from burning or decomposing leftover plant material after crop harvesting.
- Rice Cultivation: Emissions from methane released during rice cultivation.
- Drained organic soils (CO2): Emissions from carbon dioxide released when draining organic soils.
- Pesticides Manufacturing: Emissions from the production of pesticides.
- Food Transport: Emissions from transporting food products.
- Forestland: Land covered by forests.
- Net Forest conversion: Change in forest area due to deforestation and afforestation.
- Food Household Consumption: Emissions from food consumption at the household level.
- Food Retail: Emissions from the operation of retail establishments selling food.
- On-farm Electricity Use: Electricity consumption on farms.
- Food Packaging: Emissions from the production and disposal of food packaging materials.
- Agrifood Systems Waste Disposal: Emissions from waste disposal in the agrifood system.
- Food Processing: Emissions from processing food products.
- Fertilizers Manufacturing: Emissions from the production of fertilizers.
- IPPU: Emissions from industrial processes and product use.
- Manure applied to Soils: Emissions from applying animal manure to agricultural soils.
- Manure left on Pasture: Emissions from animal manure on pasture or grazing land.
- Manure Management: Emissions from managing and treating animal manure.
- Fires in organic soils: Emissions from fires in organic soils.
- Fires in humid tropical forests: Emissions from fires in humid tropical forests.
- On-farm energy use: Energy consumption on farms.
- Rural population: Number of people living in rural areas.
- Urban population: Number of people living in urban areas.
- Total Population - Male: Total number of male individuals in the population.
- Total Population - Female: Total number of female individuals in the population.
- total_emission: Total greenhouse gas emissions from various sources.
- Average Temperature °C: The average increasing of temperature (by year) in degrees Celsius,

CO2 is recorded in kilotonnes (kt): 1 kt represents 1000 kg of CO2.

The feature "Average Temperature C°", represents the average yearly temperature increase. For example, if it is 0.12, it means that the temperature in that specific location increased by 0.12 degrees Celsius.

Forestland is the only feature that exhibits negative emissions due to its role as a carbon sink. Through photosynthesis, forests absorb and store carbon dioxide, effectively removing it from the atmosphere. Sustainable forest management, along with afforestation and reforestation efforts, further contribute to negative emissions by increasing carbon sequestration capacity.

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:

- `Pandas 2.2.2` and `Numpy 1.26`
- `Matplotlib 3.8.4`

## 4. Environment <a class="anchor" id="environment"></a>

For this project the conda environment management system will be required. Below are instructions on how to set it up.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```

## 5. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                | Email                            |
| ------------------------------------------------------------------- | -------------------------------- |
| [Nombulelo Perfidia Tracy Nyoni](https://github.com/nombulelotracy) | nombulelotracy@gmail.com         |
| [Nthabiseng Amanda Mokhachane](https://github.com/NthabisengM95)    | nthabisengmokhachane95@gmail.com |
| [Melokuhle Zekhethelo Makhwasa](https://github.com/melokuhle17)     | melokuhlezek17@gmail.com         |
| [Boikokobetso Nkoko Ramashija](https://github.com/Boikoko)          | boikoko.programs@gmail.com       |
| [Khumbelo Shaun Dowelani](https://github.com/dowelani)              | dowelanikhumbelo@gmail.com       |
