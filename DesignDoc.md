# Hawaii COmmunity Search Engine and Archive

## culture

A large part of this project will depend on community uptake.  We need to establish this as a valuable service and need to discuss it with media makers and community members from the outset.  

## Phase One

### Scalar

HCH: I am thinking, since [scalar](https://github.com/anvc/scalar) does such a nice job snarfing metadata from web sites it might be a great platform for the site;  Curating would involve ingesting the video/audio/pic/doc/media metadata.

Advantage: We know how it works.  THe fields are already set up.  We could provide scholars/students/community members with scalar training and they could pretty quickly tell stories using annotation and paths.

Disadvantage: Dead links.  we will have this anyway, but worse with scalar, since since there is not a search index crawling and checking for live.  Wander of there is an auto-link check function?

### dedicated search

For the dedicated search  there are three options I can think of if we do not go with scalar.  I am sure there are others too. 

1. custom google search, as in this one (maintained in some time: but still seems to work): [Jesuit Relations](https://cse.google.com/cse/publicurl?hl=en&cx=001809558985265777363:c-vjziibyi4).  We would need to curate the links one by one for this.  that would be a fairly time consuming thing that I think we have to do no matter what.  I wonder how we could think about the sustainability of this?  Trade off for ease of use:ads unless using paid version (latter not in budget) commitment to google ecosystem.  probably not as easy to snarf metadata and such.

2. [Xapian](http://xapian.org/) back end.  Open source search.  I use this for my desktop (i.e. on the box) search in linux through a program called [recoll](http://www.lesbonscomptes.com/recoll/).  You can install both on our DAHI desktop interface easily.  they are both in the regular repo I think.

3. [Lucene and Solr](https://en.wikipedia.org/wiki/Lucene), possibly other Lucene subprojects (need research):  Apache license (open source) probably in our repo, if not easy to get.  written in java, so probably runs as tomcat instance, which we already have set up.  This is pretty much the roll-your-own search engine of choice for open internetz, but I have not installed or used it.  It is incorporated in many of the larger archival/library/document management systems I have been researching, like hydra fedora and islandora.  Most work/best payoff of search only solutions

## Phase Two

Federated server that hosts the media independent of UH

## Exhibits

Scholars can create stories using annotations of media.  Scalar looks like a good solution for this.
