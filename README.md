# Volsung Toy Models

Simple finite element, heat- and mass-transfer models designed to teach geothermal reservoir physics. 

Models developed by Irene Wallis, Cubic Earth https://www.cubicearth.nz/

Flow State Solutions sponsored a licence of Volsung (v 1.14.0) for this project https://www.flowstatesolutions.co.nz/

## Model Descriptions

### 1) Conduction

Illustrates a conductive thermal gradient of 40 degC/km, with two models that show the impact of rock thermal conductivity (watts per metre-kelvin, W/mK):
- One with consistent and moderately low conductivity (2 W/mK)
- Another where conductivity is moderately low (2 W/mK) in one half of the model and high (9 W/mK) in the other half.

List of rock thermal conductivities:
https://pubs.usgs.gov/of/1988/0441/report.pdf

All rock types have permeability of 0.001 mD (i.e., below the limit for convection).

A 10/10 km model with with 500 m Voronoi grid elements in the horizontal with 250 m thick blocks to 8 km depth. 

### 2) Single Fault

A single fault with high vertical permeability within a relatively low permeability host rock. A conductive thermal gradient of XXX degC/km is implemented without additional upflow elements (i.e., there is no additional injection of heat and mass into the fault zone). Subsequently, the convection cell, both upward and downward components, form inside the fault. 



### 6) Cap



## Licence

Apache 2.0

https://choosealicense.com/licenses/apache-2.0/

## Development

Models and associated teaching materials were developed by Irene Wallis. Peter Franz (Flow State Solutions) is acknowledged for providing technical support for the Volsung package. Bill Cumming (Cumming Geoscience) is acknowledged for conceptual discussions that contributed to the refinement of this teaching resource. 