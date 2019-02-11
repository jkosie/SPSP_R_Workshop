# SPSP_R_Workshop
Reproducible Data Analysis and Paper Writing in R Workshop at SPSP 2019

# Acknowledgements

+ Adapted from: [ICIS 2018: Open Science Tutorial](https://github.com/jkosie/openscience_tutorial) and [University of Oregon R Bootcamp](https://github.com/jkosie/uoregon_r_bootcamp)

+ Original content created by Jessica E. Kosie and [Michael C. Frank](https://web.stanford.edu/~mcfrank/)

+ Some additional content adapted from [R for Data Science](https://r4ds.had.co.nz/)

# Dataset

## `mental_abacus_data.csv`

These are data from [Barner et al. (2017), JNC](https://jnc.psychopen.eu/article/view/106), a classroom-randomized controlled trial of an elementary math intervention. The design was a simple pre-post assessment at the beginning and end of the school year. The primary question was whether assignment to group (control vs. mental abacus) produced differences in any of the outcomes (`ravens`:`woodcockTotal`). A secondary question was about the role of grade level and baseline math knowledge in the success of the intervention. 

Variables:
* `subid` - subject identifier
* `class_num` - class number
* `grade`	- school grade
* `group`	- condition: mental abacus vs. control
* `year` - Test year (pre vs. post)
* `ravens` - Raven's progressive matrices (actually a knock-off version)
* `gonogo` - Go/no-go average
* `swm`	- Spatial working memory
* `pvAvg`	- place value average performance
* `arithmeticTotal`	- total arithmetic problems correct
* `arithmeticAverage`	- average arithmetic performance
* `woodcockTotal`- Woodcock Johnson III math concepts
