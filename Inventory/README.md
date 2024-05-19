# README

The inventory directory includes the raw and processed data from the seven study sites.   

## Each file is named after the main site name:

**LONGLEAT.xlsx** includes the data for Longleat1 (L1), which is included in Chapter 3, and Longleat2 (L2), which is a study site of Chapter 4.  
**STOURHEAD.xlsx** includes the data for Stourhead1 (S1), which is included in Chapter 3, and Stourhead2 (S2), which is a study site of Chapter 3 and Chapter 4.  
**BAGLEY WOOD.xlsx** includes the data for Bagley Wood (BW), which is included in Chapter 3.  
**MORTIMER.xlsx** includes the data for Mortimer (M), which is included in Chapter 4.  
**RINGWOOD.xlsx** includes the data for Ringwood (R), which is included in Chapter 4.  

## Each file contains seven tabs:  

**TREE PLOT**: 
Raw inventory data collected from the trees found in the tree plots.  
Includes the following columns:  
*STAND*: stand name, *ID*: individual name, *Plot*: plot number, *Species*: individual species, *Dbh_cm*: diameter at breast height in cm and *Ht_m*: height measured in metres. 

**REGEN PLOT**: 
Raw inventory data collected from the seedlings and saplings found within the natural regeneration plots.  
Includes the following columns:  
*STAND*: stand name, *Plot*: plot number, *Species*: individual species, *Dbh_cm*: diameter at breast height in cm and *Ht_m*: height measured in metres. 

**SHRUB PLOT**: 
Raw inventory data collected from the shrubs found within the natural regeneration plots.  
Includes the following columns:  
*STAND*: stand name, *Plot*: plot number, *Species*: individual species, *%_Cover	avg*: Proportion of ground covered by the shrub species and *Ht_m*: average height measured in metres. 

**PLOT**
Summary of each plot characteristics and raw data collected per plot (canopy density and basal area).  
Includes the following columns:  
*STAND*: stand name, *DATE*: when the inventory took place,	*PLOT ID*: plot number,	*WP*: waypoint of the center of each plot, *tree_radious_m*: size of the tree plot in metres,	*regen_shrub_radious_m*: size of the natural regeneration and shrub plot in metres,	*num_Snag*: number of dead trees standing, *num_Downed_Log*: number of dead trees on the ground, *BFA used (n)*: Biterlich relascope scale used to estimate the basal area,	*trees counted (z)*: number of trees counted under the BFA scale,	*G (m2/ha)*: basal area estimated, *CDn*: number of points counted with the densiometre, *CD not occupied*: percentage of not cover sky, *CD occupied*: percentage of sky covered by tree canopy.  

**Species diversity**  
Estimation of species diversity indexes:  
Includes the following columns:  
*Stand*: stand name, *Species*: species name,	*number*: number of individuals per species, *Pi*: species relative abundance, *ln(Pi)*: logarithm to the base e of Pi,	*Pi x ln(Pi)*: parameter needed to estimate the Shannon index (H'),	*(D) SUM(Pi^2)*: parameter needed to estimate Reciprocal Simpson Index (1/D)	and the Gini-Simpson Index (1-D),	*1-D*: Gini-Simpson Index (1-D), *1/D*: Reciprocal Simpson Index (1/D).

**STAND**  
Summary of each stand basal area, canopy density and species diversity indexes results.  
Includes the following columns:  
*Stand*: stand name, *Basal area G(m2/h)*: average basal area estimated in each plot, *Canopy density (%)*: average canopy density estimated from each plot, *Species richness (S)*: number of actual species per site, *Shannon entropy index (H)*: 𝐻' estimated as described in page 71 CHapter 3, *Species evenness (E)*: E=H'/ln(S), *Effective number of species*: EXP(H'), *Reciprocal Simpson Index (1/D)*: average 1/D, *Gini-Simpson Index (1-D)*: average 1-D.


