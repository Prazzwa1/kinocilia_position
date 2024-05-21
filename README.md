Mouse inner ear during embryonic development starts from Embryonic day 10.5 and continues to develop till postnatal day 11.
Ogranogenesis of inner ear is complex and employ variety of developmental mechanisms.
One such mechanism is developing polarity in hair cells of inner ear which act as sensory cells to detect sound waves.
Hair cells break their apical surface symmetry by polarising their primary cilium (also called as kinocilium) to the lateral side of the tissue.
Understanding the dynamics of this polarisation is crucial to understand the underlaying mechanisms. 
Thus to visualize the kinocilium position at various developmental stages, five point method was created by Anubhav Prakash to find the coordinates of kinocilium with respect to the cell boundaries.
This script uses Pandas to access the raw csv files containing the coordinates of five points and process them to get the cartesian as well as polar coordinates.
Also this script plots those polar coordinates into a scatter plot and a kdeplot (density distribution)
Example file contains a fluoroscence confocal image of a small part of inner ear from base region (40x oil objective) with three channels marking actin (red), kinocilia (green) and beta-spectrin (blue) as a hair cell marker.
IHC.csv, OHC1.csv, OHC2.csv, OHC3.csv are all raw coordinate files read by the script and kinocilia.csv is the output file containing  combined polar coordinates.
Example graphs are shown as well in .svg format
