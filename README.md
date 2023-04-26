# Thermoenergetic Performance of a Building with Phase Change Materials Under Climate Change Projections

## Context
Work completion of graduation in Energy Engineering. The code in this repository was developed using VSCode and Jupyter, using Anaconda's virtual environment v4.12; the main objectives are data manipulation and analisys. The data is generated by thermoenergetic simulations using EnergyPlus. There are a few cells, in the end of the file, that were created to assess, visually, a few climate variables from different climate files. There is a lot of room for improvement, especially refactoring the plot generator, whose structure is repeated within several functions and even to automate all the simulations, but a lot of the functions were made and remade separately. The plot generation, for example, had to be redone a few times, due to the data structures and the way the plots are presented and added to the paper. Since the work is complete and already graded (A), I did not advance in these improvements.

## Abstract
The paper's abstract, for those interested is:
This paper investigates the thermal and energy performance of a building with different envelope compositions and its response to future climate scenarios, considering climate change projections. Through computer simulations using EnergyPlus, the building envelope is altered by applying resistive thermal insulation, phase change material, or no insulating material at all, and simulated in bioclimatic zones 1 and 8, according to the Brazilian Association of Technical Standards (ABNT); the building, of the light framing type, is built according to American Society of Heating, Refrigeration and Air-Conditioning Engineers (ASHRAE) guidelines. The phase change material used, SP24E, has operating temperatures consistent with the setpoints of the modeled HVAC system. Employing the Climate Change World Weather File Generator (CCWorldWeatherGen) tool, climate change behaviors for the representative years 2050 and 2080 are incorporated into the climate files through the statistical downscaling technique morphing, considering the A2 emissions scenario (medium-high) of the Intergovernmental Panel on Climate Change (IPCC). The results show that in mild climates, such as in Curitiba, the phase change material proves to be more efficient than the resistive thermal insulator under climate change scenarios, reducing the annual Energy Use Intensity (EUI) projected for 2050 by 8.2% and, for 2080, by 10%. For Rio de Janeiro, in the climate projections, the envelope with phase change material results in higher EUI, registering 12.1% in 2050 and 20.7% more in 2080 than the envelope with resistive thermal insulators.
