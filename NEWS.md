# paleoDiv 0.3.0 (Release date: 2024-05-02)
* added two new functions, tree.ages.spp() and tree.age.combine() to facilitate building matrices for time calibration of phylogenies

# paleoDiv 0.2.6 (Release date: 2024-04-05)
* improved automatic dimension settings for ts.periods() and ts.stages()

# paleoDiv 0.2.5 (Release date: 2024-03-24)
* added parameter 'italicize' to phylo.spindles, allowing automatic italicization of taxa given as indices or taxon names
* improved color vector handling by phylo.spindles (colour vectors that are too short or long are now cycled or abridged automatically)

# paleoDiv 0.2.4 (Release date: 2024-03-23)
* added better customizability for phylo.spindles
    Two new parameters for controlling y locations for plotting and text x alignment
* standard value 0 for pos parameter of viol
* fixed bug in setting of cutoff values if no ages are provided
* fixed abdistr_() function; previous version erraneously failed to take into account the ab.val data in the calculation of abundance because of a forgotten # sign
* improved handling of spindle limits in phylo.spindles (cutoff variable) if no age data are provided

# paleoDiv 0.2.3 (Release date: 2024-03-08)
==============
* fixed vignette

# paleoDiv 0.2.2 (Release date: 2024-03-07)
==============
* Fixed behaviour when paleobioDB is unavailable; all datasets for examples and vignette are now included in package data, so this code should run error-free even if website is unavailable.

# paleoDiv 0.2.1 (Release date: 2024-03-06)
==============
* changed row numbering of output of synonymize()

# paleoDiv 0.2.0 (Release date: 2024-03-05)
==============
* changed description and documentation
* fixed message output
* improved behavior of phylo.spindles; now allows plotting without any phylogeny

# paleoDiv 0.1.1 (Release date: 2024-03-02)
==============

* improvement to tree.ages() (if data is not found) and added option for occ.cleanup() to return whole data.frame instead of mere collumn

# paleoDiv v0.1.0 (Release date: 2024-03-01)
==============

* Additional function synonymize() that helps with manual editing of taxon-range tables to remove taxonomic errors

# paleoDiv v0.0.7 (Release date: 2024-03-01)
==============

* Improved error-handling behaviour of pdb() function and others based on it

# paleoDiv v0.0.6 (Release date: 2024-03-01)
==============

* txt.y argument of phylo.spindles() now accepts vectorized input

# paleoDiv v0.0.5 (Release date: 2024-02-29)
==============

* First version of this package
 



