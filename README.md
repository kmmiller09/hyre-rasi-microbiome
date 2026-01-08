# hyre-rasi-microbiome
Bd infection data, skin bacterial diversity data, and associated metadata for Pseudacris regilla and Rana sierrae in California's Sierra Nevada. Location data are not provided for Rana sierrae as this is a sensitive species.

# 16S Sequencing Data
Raw 16S sequencing data was submitted to the NCBI SRA database: accession number PRJNA1398947.
https://www.ncbi.nlm.nih.gov/sra/PRJNA1398947.

# metadata definitions
id = microbiome swab identifier  
bd_swab_id = Bd swab identifier (number usually matches id)  
basin = basin/watershed where frog was sampled  
site_id = lake site identifier; these are Knapp lake IDs  
bd_established = whether or not Bd is (or was) present at the site  
 * naïve = Bd was not detected, and was previously not detected
 * present = Bd was detected; these were all ‘enzootic’, persisting sites  
visit_date = date of visit and sampling  
species = frog species sampled  
 * ramu = Rana sierrae or Rana muscosa  
 * hyre = Hyla regilla (Pseudacris regilla)  
capture_life_stage = estimated life stage of sampled animal (adult, subadult, tadpole) based on measurement cutoffs  
sex_swabbing = sex of sampled animal  
 *	m = male  
 *	f = female  
 *	NA = likely subadult or tadpole, too young to determine  
length = snout to vent length of frog, in millimeters  
weight = weight of frog, in grams  
bd_load = number of Bd ITS1 gene copies present in sample (NA indicates Bd was not detected)  
log_bd_its = log10 of bd_load  
bd_status = positive/negative detection of Bd  
location = location of frog capture at the site  
 *	lake  
 *	fringing = habitat adjacent to the main lake body (e.g. connected channels, meadow next to lake)  
 *	outlet (of the lake)  
 *	inlet (of the lake)  
frog_utme = utm easting of frog capture  
frog_utmn = utm northing of frog capture  
jurisdiction* = forest/park where the site is located  
wilderness* = wilderness area where the site is located  
area* = surface area of lake site  
depth* = maximum depth of lake site (meters)  
elevation* = elevation of lake site (meters)  
lake_utme* = utm easting of site location  
lake_utmn* = utm northing of site location 
co_occurrence = whether one or both frog species occurred at a site  
 *	single = single occupancy site (only ramu or only hyre)  
 *	cooccurring = both species occupied the site (both ramu and hyre)  
observed_features = bacterial community richness; number of different bacterial sequences in a sample  
shannon_entropy = Shannon diversity of bacteriome community; no units, higher numbers indicate greater diversity  
faith_pd = Faith’s phylogenetic diversity; value describes bacterial diversity based on phylogeny  
pielou_evenness = bacterial species evenness  
  
*denotes data pulled from Sierra Nevada Knapp et al. 2020 database
