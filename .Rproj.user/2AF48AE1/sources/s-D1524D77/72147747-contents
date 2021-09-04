# C. difficile FMT data

This data was taken from 

Weingarden, A., González, A., Vázquez-Baeza, Y. et al.<br
*Dynamic changes in short- and long-term bacterial composition following fecal microbiota transplantation for recurrent Clostridium difficile infection.* <br> 
Microbiome 3, 10 (2015). https://doi.org/10.1186/s40168-015-0070-0

The data includes time series for 4 individuals with recurrent C. diff infection post FMT, as well
as data from various donors and an additional set of recurrent C. diff patient that did not receive
an FMT.
I also added in 10 random samples from skin sequenced under similar conditions as the data in the project.

The data was processed with DADA2 and you can find the prepared tables in cdiff_fmt.xlsx.

## Included Tables

**Phyla percentages**<br>
The relative abundances for the 9 major phyla in the data set. The values denote relative abundances
so they will add up to approximately 1 in each sample. 

**Bray-Curtis Ordination**<br>
The Principal Components of the distances for each sample. This was generated from the genus-level data. 
The first axis explains about 30% of the total variance and the second about 20%, so both together capture about 50% of the total variance
which is pretty good.

## Figures

**time_courses_*.png**<br>
Show the relative abundances for each phylum and subject in the study over time. There is a
version with time courses for only the 4 individuals and one with data for all sample types.
The days after FMT for the skin samples have no meaning, I put in negative numbers to make clear
that those indiviuals were not part of the FMT study.

**pcoa.png**<br>
Visualization of the data from the Principal Coordinate analysis. The small numbers denote
the days since the FMT. One can see that untreated patients are close to skin samples, probably due
to highly aerobic intestine. Post-FMT samples quickly move towards the donor data. 

