# End-to-End Data Analytics Project: Energy, Cost and Emissions Analysis of an Open-Pit Copper Mine

## Executive Summary

This project used synthetic data for an open-pit copper mine, generated using generative artificial intelligence. SQL was used to extract, clean and transform data from multiple relational tables of the copper mine. This was followed by analysing the energy consumption, cost, and greenhouse gas emissions data. The processed data was imported into Power BI to create visualisations, and compare energy consumption, energy costs, and greenhouse gas emissions across the copper mine’s operations and sub-operations.

Mineral Processing and Materials Handling operations were identified as the main contributors to the copper mine’s energy consumption and energy costs, with Mineral Processing also producing the largest amount of greenhouse gas emissions.

**Increasing solar energy PPA (power purchase agreement)** supply to **20% of total electricity usage**, and **reducing haulage diesel consumption by 20% through improved haul-road conditions**, could collectively reduce energy costs by **8.6%** and emissions intensity by **13.1%**. These measures could deliver **energy cost savings of approximately AUD 554,000** and **reduce greenhouse gas emissions by around 27,000 tonnes CO₂e**.

## Business Problem

An open-pit copper mine operates across multiple energy-intensive activities, e.g. drilling, hauling, crushing, grinding and flotation. These operations are dependent on a combination of grid electricity, diesel, natural gas and renewable energy, resulting in significant energy consumption and greenhouse gas emissions.

This projects analyses where energy consumption, energy costs, and emissions are concentrated across the mine’s operations and sub-operations.

The aim of this project is to highlight areas for further investigation and recommend opportunities to reduced energy consumption, energy costs, and greenhouse gas emissions.

## Methodology

1. Used SQL to extract, clean, and transform data from multiple relational tables.
2. Imported transformed SQL query results into Power BI to develop interactive visualisations of energy consumption, energy costs, and greenhouse gas emissions across the mine’s main operations and sub-operations, helping identify major contributors and areas for further investigation.
3. Developed Power BI visualisations based on selected recommendations, to illustrate their potential impact on energy cost savings and greenhouse gas emissions reductions.

## Skills

**SQL:** Create Tables, CTEs, Joins, Subqueries, CASE Statements, Aggregate Functions, Date Parsing, Date Functions, String Functions, Regular Expressions, Type Casting, NULL Handling

**Power BI:** Data visualisation

## Results

*Figure 1* presents the energy intensity, defined as the energy consumed per tonne of copper concentrate produced (bar graph), together with the corresponding energy cost per tonne concentrate (line graph) across the different operations within the copper mine investigated.

Based on *Figure 1*, mineral processing and materials handling are identified as the major contributors to both energy intensity and energy cost within the copper mine. These operations were therefore investigated in greater detail by analysing their respective sub-operations, as shown in *Figure 2* and *Figure 3*.

For the materials handling operation, haulage of the extracted ore and waste is the largest contributor to both energy consumption and cost, accounting for 72% of the operation’s total energy intensity and total energy cost respectively.

For the mineral processing operation, the crushing and grinding of the mined ore are made up of primary crushing, secondary crushing, SAG milling and ball milling. Together, these activities account for approximately 73% of the operation’s total energy intensity and 75% of its total energy cost.
<br><br>

<img width="600" alt="image" src="https://github.com/user-attachments/assets/ca29d57b-972d-4e38-a097-986a0bcf2c5f" />

*Figure 1. Energy intensity and energy cost of main operations in the copper mine.*
<br><br>
<img width="600" alt="image" src="https://github.com/user-attachments/assets/61f7af23-c533-434f-8cd3-d153b35cef36" />

*Figure 2. Energy intensity and energy cost of Materials Handling operation in the copper mine.*

![Figure 3 - Energy intensity and energy cost of Mineral Processing operation in the copper mine](images/figure-3.png)

*Figure 3. Energy intensity and energy cost of Mineral Processing operation in the copper mine.*

For both the materials handling and mineral processing operations, it was important to identify the energy sources responsible for the significant energy intensity and energy costs observed in *Figure 2* and *Figure 3*. *Figure 4* and *Figure 5* present the energy sources used within the materials handling and mineral processing operations, respectively.

Within the materials handling operation, the haulage of mined ore and waste is solely dependent on diesel consumption. In contrast, the mineral processing operation relies primarily on grid electricity, particularly in the crushing and grinding of the mined ore. Solar energy contributes only a small proportion of the electricity used for crushing and grinding, accounting for approximately 6% of total electricity consumption. This solar electricity is obtained through a power purchase agreement (PPA) with a solar energy provider.

The significant dependence on grid electricity for crushing and grinding also contributes to the significant greenhouse gas emissions produced within the mineral processing operation, as shown in *Figure 6*. Based on *Figure 6*, mineral processing generates approximately 530 kg CO₂e/tonne of copper concentrate produced, accounting for around 58% of the mine’s total greenhouse gas emissions.

![Figure 4 - Energy sources of Materials Handling operation in the copper mine](images/figure-4.png)

*Figure 4. Energy sources of Materials Handling operation in the copper mine.*

![Figure 5 - Energy sources of Mineral Processing operation in the copper mine](images/figure-5.png)

*Figure 5. Energy sources of Mineral Processing operation in the copper mine.*

![Figure 6 - Greenhouse gas emissions intensity of main operations in the copper mine](images/figure-6.png)

*Figure 6. Greenhouse gas emissions intensity of main operations in the copper mine.*

## Business Recommendation

In order to reduce energy costs and greenhouse gas emissions, two potential improvement scenarios are recommended for further evaluation.

The first recommendation involves improving the quality of the haul road surface. According to a study by Bodziony and Patyk (2024), improvements to haul road conditions can reduce the diesel fuel consumption of haul trucks by up to 20%.

The second recommendation is to increase the contribution of solar energy to the mine site’s electricity supply, thereby reducing its dependence on grid electricity. A reasonable target of 20% of the mine’s total electricity requirements being supplied by solar energy is recommended.

*Table 0.1* presents the overall energy cost per tonne of copper concentrate produced and the overall greenhouse gas emissions intensity (greenhouse gas emissions per tonne copper concentrate) for the entire mine site under the following scenarios:

1. **Current Energy Mix**
2. **Scenario A** – Solar PPA Supplying 20% of Total Electricity Requirements
3. **Scenario B** – Modification of Haul Road Conditions (Haulage Diesel Consumption Reduced by 20%)

Based on *Table 0.1*, Scenario A reduces the energy cost per tonne of copper concentrate by 3.9% compared to the mine site’s current energy mix. It also results in a 10.8% reduction in greenhouse gas emissions intensity.

Scenario B, on the other hand, reduces the overall energy cost per tonne of copper concentrate by 4.7% compared to the mine site’s current energy mix. It also results in a 2.3% reduction in greenhouse gas emissions intensity.

The combined Scenario A and Scenario B results in an 8.6% reduction in energy cost per tonne of copper concentrate and a 13.1% reduction in greenhouse gas emissions intensity compared to the mine site’s current energy mix.

*Figure 7* presents the total energy cost and total greenhouse gas emissions for the entire mine site under the current energy mix, as well as the combined Scenario A and Scenario B. The total energy costs are represented by the bar graph, while the total greenhouse gas emissions are represented by the line graph.

Based on the figure, the combined Scenario A and Scenario B can achieve total energy cost savings of approximately $554,000 compared to the current energy mix. The combined scenarios can also reduce total greenhouse gas emissions by approximately 27,000 tonnes CO₂e.

### Table 0.1. Overall Energy Cost and Greenhouse Gas Emissions Intensity for Different Energy Scenarios

| Scenario | Energy Mix | Overall Energy Cost per Tonne Conc. (AUD/t conc.) | Overall CO₂e Emissions Intensity (kg CO₂e/t conc.) |
|---|---|---:|---:|
| **Current Energy Mix** | Current Energy Mix | 28.77 | 915.34 |
| **Scenario A** | Solar PPA Supplying 20% of Total Electricity Requirements | 27.64 | 816.33 |
| **Scenario B** | Modification of Haul Road Surface (Haulage Diesel Consumption Reduced by 20%) | 27.42 | 894.67 |
| **Scenario A + B** | Solar PPA Supplying 20% of Total Electricity Requirements + Modification of Haul Road Surface | 26.29 | 795.67 |

![Figure 7 - Comparison of total energy cost and greenhouse gas emissions for the current energy mix and combined scenarios A + B](images/figure-7.png)

*Figure 7. Comparison of total energy cost and greenhouse gas emissions for the current energy mix and combined scenarios A + B.*

## Future Recommendations

1. Investigate the feasibility of adopting electrified haulage trucks and trolley assist systems to further reduce diesel fuel consumption in haulage operations.
2. Investigate the feasibility of increasing the contribution of solar power to the mine site’s electricity supply. This should also include an investigation of the costs and practicality of battery storage systems to store excess solar energy generated during the day.

## References

Bodziony, P. and Patyk, M. (2024) ‘The Influence of the Mining Operation Environment on the Energy Consumption and Technical Availability of Truck Haulage Operations in Surface Mines’, *Energies*, 17(11).
