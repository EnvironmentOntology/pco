# Qualities of groups of organisms #

PCO will have a number of terms for population qualities (e.g., growth rate, age structure), community qualities (e.g., species richness, number of trophic levels), and qualities of other collections of organisms.

The question is whether these terms should have PCO ids or PATO ids.

PATO is the [Phenotypic Quality Ontology](http://bioportal.bioontology.org/ontologies/1107).

Ideally, PATO would have the general terms, and PCO would combine them with specific PCO entities.

For example:
  * population fecundity would be a cross product if PCO:population and PATO:fecundity
  * species richness of a community would be a combination of PCO:community, PCO:species and PATO:count.
  * population growth rate: PATO says "PATO:growth rate" will be obsoleted, and to use GO:growth and PATO:rate, but GO:growth only applies to organism. Need to define population growth rate using PCO terms (coupled with GO terms for birth and death) and PATO:rate.

Many qualities can inhere in many different types of entities, just as traits can be meausured at different levels (e.g., flower color as a trait of an individual, a population, or a species).

# Phenotypic Quality Ontology (PATO) terms #
The following terms are already in PATO. See comments for each term.
## Population qualities ##
**population quality** (PATO:0002003) =def. A quality that inheres in an entire population or part of a population.

_I think saying that it inheres in part of a population is problematic, because it is too inclusive. A leaf is a part of one tree, which is part of a population. Population qualities should be confined to populations. If there is a need to define qualities of groups of organisms that are parts of populations, we can make classes for those groups, and define qualities specifically for them_

-Has two subclasses: mixed sex (PATO:0001338) and morbidity (PATO:0001415).

_Suggest that PATO redefine organismal quality (see below) and make these organismal qualities. Then ontologies like PCO and combine them with the entities in which they inhere._

## Organismal qualities ##
**organismal quality** (PATO:0001995) =def. A quality that inheres in an entire organism or part of an organism.

_The definition suggests that it should not apply to groups of organism, but some of the subclasses (e.g., brood quality, fecundity) are defined for multiple organisms._

_Propose a revised definition that will cover inidividual organism and collections of organism. No need to say "part of organism", because if it inheres in a part of an organism, it inheres in an organism._

_proposed def.: A quality that inheres in an entire CARO:organism or a PCO:collection of organisms._

### Behavior qualities ###
**behavioral quality** (PATO:0000186) =def. An organismal quality inhering in a bearer by virtue of the bearer's behavior aggregate of the responses or reactions or movements in a given situation.

_Some of these subclasses may be needed for PCO._

_What about behavioral qualities that involve more than one organism?_

### Reproductive qualities ###

**reproductive quality** (PATO:0001434) =def. An organismal quality inhering in a bearer by virtue of the bearer's ability to produce new life or offspring.

_Some of the subclasses (e.g., brood quality, fecundity) are defined for multiple organisms._

For example, **fecundity** (PATO:0000273) =def. A reproductive quality inhering in an _organism or population_ by virtue of the bearer's potential reproductive capacity ad measured by the number of gametes.