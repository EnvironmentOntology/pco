# Introduction #

The first rule of PURLs is: You do not delete a PURL.

The second rule of PURLs: You do not delete a PURL.

Seriously. Once you delete (or "tombstone" in PURL parlance) a PURL, we cannot get it back, no matter how nicely you ask, so please do not delete them.

Current PCO PURL maintainer is Ramona Walls.

# Help #

[OBO Foundry PURL Guide](http://code.google.com/p/obo-foundry-operations-committee/wiki/PURLGuide?ts=1381185021&updated=PURLGuide)

[PURL.org Help](http://purl.org/docs/help.html)

# PCO PURLS #

|**PURL**|**Redirects to**|
|:-------|:---------------|
|http://purl.obolibrary.org/obo/pco.owl|most current release: http://popcomm-ontology.googlecode.com/svn/releases/YYYY-MM-DD/pco.owl|
|http://purl.obolibrary.org/obo/PCO_0000001 (for any non-deprecated term)|http://www.ontobee.org/browser/rdf.php?o=PCO&iri=http://purl.obolibrary.org/obo/PCO_0000001|
|http://purl.obolibrary.org/obo/pco/|http://popcomm-ontology.googlecode.com/svn/ (partial redirect to the PCO Google Code repository)|



Because of the partial redirect, a URI such as http://purl.obolibrary.org/obo/pco/releases/2013-10-03/pco.owl will automatically redirect to http://popcomm-ontology.googlecode.com/svn/releases/2013-10-03/pco.owl, so we don't need to create new PURLS for each file at each release. **However**, the simple PURLs (http://purl.obolibrary.org/obo/pco.owl and any others we might create in the future) do need to be updated with each release.