# Modelling Workshops
Owing to recent conversation around formal modelling of the FIAF Cataloguing   Manual and EN15907, we intend on holding a series of workshops to explicitly   discuss these concepts. The goal of these workshops will be to provide both a   formal implementation of the Cataloguing Manual (as RDF/OWL), as well as a shared   model which could be used for the interoperability of film data between organisations.

These will take place weekly, starting Thursday 12th of January at 5pm CET and   will be short meetings of no longer than an hour each. 

Draft ontology: [ontology.ttl](ontology.ttl)   [[WebVOWL](http://vowl.visualdataweb.org/webvowl-old/webvowl-old.html#iri=https://raw.githubusercontent.com/FIAF/modelling-workshops/main/ontology.ttl)]

## **Classes**   
####  Analytic   
**iri** https://fiafcore.org/ontology/Analytic   
**label** Analytic   
**source** FIAF Cataloguing Manual D.1   
**type** [owl:Class](url)   
**subclass of** [fiaf:WorkVariant](url)   
####  Broadcast   
**iri** https://fiafcore.org/ontology/Broadcast   
**label** Broadcast   
**source** FIAF Cataloguing Manual D.5.7   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Collection   
**iri** https://fiafcore.org/ontology/Collection   
**label** Collection   
**source** FIAF Cataloguing Manual D.1   
**type** [owl:Class](url)   
**subclass of** [fiaf:WorkVariant](url)   
####  Home Viewing Publication   
**iri** https://fiafcore.org/ontology/HomeViewingPublication   
**label** Home Viewing Publication   
**source** FIAF Cataloguing Manual D.5.6   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Internet   
**iri** https://fiafcore.org/ontology/Internet   
**label** Internet   
**source** FIAF Cataloguing Manual D.5.8   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Monographic   
**iri** https://fiafcore.org/ontology/Monographic   
**label** Monographic   
**source** FIAF Cataloguing Manual D.1   
**type** [owl:Class](url)   
**subclass of** [fiaf:WorkVariant](url)   
####  Non-Theatrical Distribution   
**iri** https://fiafcore.org/ontology/NonTheatricalDistribution   
**label** Non-Theatrical Distribution   
**source** FIAF Cataloguing Manual D.5.3   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Not For Release   
**iri** https://fiafcore.org/ontology/NotForRelease   
**label** Not For Release   
**source** FIAF Cataloguing Manual D.5.4   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Pre-Release   
**iri** https://fiafcore.org/ontology/PreRelease   
**label** Pre-Release   
**source** FIAF Cataloguing Manual D.5.1   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Preservation/Restoration   
**iri** https://fiafcore.org/ontology/PreservationRestoration   
**label** Preservation/Restoration   
**source** FIAF Cataloguing Manual D.5.9   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Serial   
**iri** https://fiafcore.org/ontology/Serial   
**label** Serial   
**source** FIAF Cataloguing Manual D.1   
**type** [owl:Class](url)   
**subclass of** [fiaf:WorkVariant](url)   
####  Theatrical Distribution   
**iri** https://fiafcore.org/ontology/TheatricalDistribution   
**label** Theatrical Distribution   
**source** FIAF Cataloguing Manual D.5.2   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Unknown Manifestation   
**iri** https://fiafcore.org/ontology/UnknownManifestation   
**label** Unknown Manifestation   
**source** FIAF Cataloguing Manual D.5.10    
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Unreleased   
**iri** https://fiafcore.org/ontology/Unreleased   
**label** Unreleased   
**source** FIAF Cataloguing Manual D.5.5   
**type** [owl:Class](url)   
**subclass of** [fiaf:Manifestation](url)   
####  Work/Variant   
**iri** https://fiafcore.org/ontology/WorkVariant   
**label** Work/Variant   
**source** FIAF Cataloguing Manual 1.0   
**type** [owl:Class](url)   
####  Manifestation   
**iri** https://fiafcore.org/ontology/Manifestation   
**label** Manifestation   
**source** FIAF Cataloguing Manual 2.0   
**type** [owl:Class](url)   
## **Object Properties**   
####  Has Activity   
**iri** https://fiafcore.org/ontology/hasActivity   
**label** Has Activity   
**source** FIAF Cataloguing Manual 1.4.1.1, FIAF Cataloguing Manual 2.4.1.1   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:Manifestation](url), [fiaf:WorkVariant](url)   
**range** [fiaf:Activity](url)   
####  Has Country   
**iri** https://fiafcore.org/ontology/hasCountry   
**label** Has Country   
**source** FIAF Cataloguing Manual 1.3.3   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:WorkVariant](url)   
**range** [fiaf:Country](url)   
####  Has Event   
**iri** https://fiafcore.org/ontology/hasEvent   
**label** Has Event   
**source** FIAF Cataloguing Manual 1.4.2, FIAF Cataloguing Manual 2.4.2   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:Manifestation](url), [fiaf:WorkVariant](url)   
**range** [fiaf:Event](url)   
####  Has Form   
**iri** https://fiafcore.org/ontology/hasForm   
**label** Has Form   
**source** FIAF Cataloguing Manual 1.4.3   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:WorkVariant](url)   
**range** [fiaf:Form](url)   
####  Has Genre   
**iri** https://fiafcore.org/ontology/hasGenre   
**label** Has Genre   
**source** FIAF Cataloguing Manual 1.4.3   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:WorkVariant](url)   
**range** [fiaf:Genre](url)   
####  Has Identifier   
**iri** https://fiafcore.org/ontology/hasIdentifier   
**label** Has Identifier   
**source** FIAF Cataloguing Manual 1.3.1, FIAF Cataloguing Manual 2.3.1   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:Manifestation](url), [fiaf:WorkVariant](url)   
**range** [fiaf:Identifier](url)   
####  Has Item   
**iri** https://fiafcore.org/ontology/hasItem   
**label** Has Item   
**source** FIAF Cataloguing Manual 2.4.4   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:Manifestation](url)   
**range** [fiaf:Item](url)   
####  Has Language Usage   
**iri** https://fiafcore.org/ontology/hasLanguageUsage   
**label** Has Language Usage   
**source** FIAF Cataloguing Manual 2.3.3.2   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:Manifestation](url)   
**range** [fiaf:LanguageUsage](url)   
####  Has Manifestation   
**iri** https://fiafcore.org/ontology/hasManifestation   
**label** Has Manifestation   
**source** FIAF Cataloguing Manual 1.4.6   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:WorkVariant](url)   
**range** [fiaf:Manifestation](url)   
####  Has Subject   
**iri** https://fiafcore.org/ontology/hasSubject   
**label** Has Subject   
**source** FIAF Cataloguing Manual 1.4.3   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:WorkVariant](url)   
**range** [fiaf:Subject](url)   
####  Has Title   
**iri** https://fiafcore.org/ontology/hasTitle   
**label** Has Title   
**source** FIAF Cataloguing Manual 1.3.2, FIAF Cataloguing Manual 2.3.2.1   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:Manifestation](url), [fiaf:WorkVariant](url)   
**range** [fiaf:Title](url)   
####  Has Variant Type   
**iri** https://fiafcore.org/ontology/hasVariantType   
**label** Has Variant Type   
**source** FIAF Cataloguing Manual 1.2.2   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:WorkVariant](url)   
**range** [fiaf:VariantType](url)   
####  Has Work/Variant   
**iri** https://fiafcore.org/ontology/hasWorkVariant   
**label** Has Work/Variant   
**source** FIAF Cataloguing Manual 1.4.5   
**type** [owl:ObjectProperty](url)   
**domain** [fiaf:WorkVariant](url)   
**range** [fiaf:WorkVariant](url)   
