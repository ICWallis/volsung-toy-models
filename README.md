# Volsung Toy Models

Simple finite element, heat- and mass-transfer models designed to teach geothermal reservoir physics. 

Models developed by Irene Wallis, Cubic Earth https://www.cubicearth.nz/

Flow State Solutions sponsored a licence of Volsung (v 1.14.0) for this project https://www.flowstatesolutions.co.nz/

## Model Descriptions

### 1) Conduction

#### Concept

Illustrates a conductive thermal gradient of 40 degC/km at a given rock conductivity (watts per metre-kelvin W/mK )

There are two conduction models:
- One with consistent rock thermal conductivity (2 W/mK) 
- Another where rock thermal conductivity is varied (2 and 8 W/mK)

List of rock thermal conductivities:
https://pubs.usgs.gov/of/1988/0441/report.pdf

#### Paramaters

All rock types have permeability of XXX mD (i.e., below the limit for convection).

Rock A:

Rock B:

Rock C:

#### Grid

Tarten grid with XX elements

### 2) Single Fault

#### Concept
A single fault with high vertical permeability within a relatively low permeability host rock. A conductive thermal gradient of XXX degC/km is implemented without additional upflow elements (i.e., there is no additional injection of heat and mass into the fault zone). Subsequently, the convection cell, both upward and downward components, form inside the fault. 

#### Paramaters

#### Grid

### 6) Cap

#### Concept

#### Paramaters

#### Grid

## Licence

Apache 2.0

https://choosealicense.com/licenses/apache-2.0/

## Development

Models and associated teaching materials were developed by Irene Wallis. Peter Franz (Flow State Solutions) is acknowledged for providing technical support for the Volsung package. Bill Cumming (Cumming Geoscience) is acknowledged for conceptual discussions that contributed to the refinement of this teaching resource. 