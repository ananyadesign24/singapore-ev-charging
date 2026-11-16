# Public EV Charging in Singapore: Where Is It Provided, and What Explains It?

Singapore aims for 60,000 EV charging points by 2030. This project asks whether public chargers go where people live, and what is left over once housing is accounted for.

**📄 [Read the 5-page summary](EV_Charging_Singapore_Summary.pdf)**

## Data
- LTA EV charging registry (June 2026), collapsed to 2,815 public sites
- URA Master Plan 2019 subzones
- SingStat residents by dwelling type (June 2026)
- EMA household electricity consumption

## Methods
- Inhomogeneous Poisson point-process models
- G, K and L functions with global envelopes; cross-type tests between operators
- R: `spatstat`, `sf`

## Key findings
- Charger intensity rises about 5.8% per extra 1,000 residents per km², and about 3.8% per 10-point rise in condo share
- It falls about 17.9% per 10-point rise in landed housing share, consistent with public charging filling the gap where residents cannot charge at home
- Chargers still cluster beyond about 1.5 km after controlling for housing, mostly around the CBD, suggesting missing workplace demand
- The major operators split the island geographically rather than locating side by side

These are associations, not causal effects.

## Team
Ananya Joshi, Trixia, Logam and Shamini. ECON6027 Spatial Econometrics, Singapore Management University, 2026.
