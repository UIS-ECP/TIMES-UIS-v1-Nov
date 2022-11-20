# TIMES-UIS-v1-Nov
This version is based on TIMES-UIS-V0. Presented to the University in November.

Basic assumptions:
- Year base is 2019.
- Main unit PJ.
- Time horizon to 2040.
- Time periods: 2019, 2020, 2023, 2025, 2027, 2030, 2033, 2035, 2037, 2040.
- There is a difference between heavy, medium and light oil. However, they have the same calorific value and emission factor.
- Same energetics considered in the PEN. AVGAS was not considered. 
- Prices fuels are variable over time.
- Prices and emissions factor of the SIN was constant over time.
- No time slices, just annual representation.


Supply section:
- Oilfields are grouped by departments. 
- Separation processes were grouped together with production processes.
- There are production potentials by 2030 according to a percentage.
- Addition of exploration reserves extrapolated according to ECP + current discoveries and their production potentials (alternative scenario).
- Addition of reserves by EOR processes according to the potential reported in the literature (alternative scenario).
- Addition of shale gas potential is considered (alternative scenario).
- Reinjection of natural gas and water is not endogenously represented.


Transport section:
- Oil, gas and producs pipelines were not represented.
- The production of each field is grouped into a national production for conversion and demand purposes.


Imports/Exports:
- No restrictions added.


Conversion section:
- Gas processing plants only have an electricity consumption parameter and 100% conversion into LPG and light oil.  
- Flaring is considered within the production process. Data extrapolated from the balance sheet of the ANH. In alternative proccess an investment is made, which allows taking advantage of natural gas to generate LPG.
- Data for installed autogeneration capacities is extrapolated from the gas balance sheet of the ANH.
- A refinery is modeled that has the complete capacity of ECP refineries. Production percentages were fixed in the base scenario, while in alternative scenarios were flexibles.
- The blending of gasoline and diesel with biofuelds was considered according to current standards. Biodiesel and ethanol were bought by the company (constant price over time).


Demand section:
- Demand sectors projections according PEN 2020-2025
- Updating scenario was used for the base escenario.
- Demand for natural gas by thermoelectrics plants was not considered (there is no projections in PEN).


Emissions section:
- Most modeled processed used the follow approach:
Emissions = fuel consumption * emission factor of fuel.
- Simplification of scope 3 emisions was added considered the previous approach.
- Some proccesses have an emission factor according to their activity (refinery).


Policites:
- Constant tax carbon over scope 1 and 2 was added.


Author: Julian Caicedo, LinkedIn: @engcaicedo


Se va a probar con dos usuarios