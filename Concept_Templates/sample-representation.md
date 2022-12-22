## Knowledge domain resources

### Related

https://goldbook.iupac.org/terms/view/S05451: definition of sample, discussion of sampling error, etc.

https://en.wikipedia.org/wiki/Sample_(material): definition and history of the term sample.

https://en.wikipedia.org/wiki/Experiment: discussion of how experiments are interpreted

https://plato.stanford.edu/entries/scientific-representation/: discussion of what representation in science means

### Comments

## General Concept Info

### IRI: TBA
### OWL type: TBA
### Concept elucidation
A sample representation refers to a specific interpretation of the underlying physical nature of a sample based on a set of outcomes from crystallographic experiments.

If more than one distinct actor performs or analyzes selections of experiments and/or apply their own interpretations to recorded experimental outcomes, what they are considering are different sample representations of the sample.
Multiple sample representations can exist in parallel with different relations to other crystallographic concepts, possibly representing *contradictory* interpretations of the same sample.

The concept "sample representation" may be generalizable outside the crystallography domain ontology to mean a representation of a material used for any experiments (EMMO:sample?).
### Preferred label
"sample representation"
### Alternate labels
"sample model", "materials representation"
### Discussion:
Sample representation is meant to be a useful concept for entities in databases of crystallographic experimental data as "the thing" to which one can assign crystallography ontology concepts by interpretation of sets of experiments and other input or circumstances, via manual or automated reasoning.

Ligusitically it makes sense to say that a sample representation "is" (has an "is-a" relationship to) a specific crystalographic model, e.g., a "periodic crystal".

This gives an entity which can be queried for in a natural way, e.g.: "Find all sample representations that have a NaCl structure and that contains Ni".
Expressing the same query in terms of samples and 'is-modelled-by' relations would lead to expressions like: "Find all samples that have been simultaneously modelled-by NaCl structure and Ni presence".
This both seems a less natural phrasing and less clear (does it need to be the same actor that assigns both models?)
