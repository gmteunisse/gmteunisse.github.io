# Software
Below I list the software packages that I develop and maintain. Feel free to use, alter and contribute to the packages in any way you seem fit. Suggestions for how to improve the software are appreciated.

## [ggnested](https://github.com/gmteunisse/ggnested)
`ggnested` is a wrapper function around `ggplot2` that enables users to
display data with a two-level nested or clustered structure. It uses
colours or fills to label the main group or cluster, and a gradient of
shades and tints of each colour to label subgroups within each main
group. It is particularly useful for data with a hierarchy, such as
taxonomic annotations or geographic locations.

This is one of the core functions of the `fantaxtic` package, which
visualizes taxonomic ranks of amplicon sequencing / microbiome data as
stored in `phyloseq` objects. However, as it has utility beyond
displaying taxonomic annotations, it has been implemented as a separate
package.

**Keywords: R, ggplot2, nested data, clustered data, multiple levels,
shades, tints, gradient**

![ggnested barplot](https://github.com/gmteunisse/ggnested/blob/main/man/figures/README-barplot-1.png?raw=true)<!-- -->

## [fantaxtic](https://github.com/gmteunisse/fantaxtic)
`fantaxtic` contains a set of functions to identify and visualize the most abundant taxa in phyloseq objects. It allows users to identify top taxa using any metric and any grouping, and plot the (relative) abundances of the top taxa using a nested bar plot visualisation. In the nested bar plot, colours or fills signify a top taxonomic rank (e.g. Phylum), and a gradient of shades and tints signifies levels at a nested taxonomic rank (e.g. Species). It is particularly useful to present an overview of microbiome sequencing, amplicon sequencing or metabarcoding data.

**Keywords: R, ggplot2, nested bar plot, phyloseq, taxonomy, most abundant taxa, multiple levels, shades, tins, gradient, 16S, ITS ,18S, microbiome, amplicon sequencing, metabarcoding**

