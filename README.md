# Finding cobalt deposits
The objective here is to create a heat map representing the likelihood of finding a given ore deposit in a region. The heat map should be stored such that we could easily view the numeric value for the likelihood of finding the ore at every location.

To determine where cobalt is likely to occur, it can be assumed that cobalt is found in the presence of two types of rock: serpentinite and granodiorite. We are interested in locations where these rock types are in contact with each other, or in close proximity to one another. Here, we assume that regions where the rock types are further than 10km from each other have 0 likelihood of cobalt occuring. Serpentinite is a subtype of “ultramafic” rock; so for now, assume that all ultramafic rocks are also serpentinite.

The data set is found at: https://www2.gov.bc.ca/gov/content/industry/mineral-exploration-mining/british-columbia-geological-survey/geology/bcdigitalgeology.
