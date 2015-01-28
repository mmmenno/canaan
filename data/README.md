#Data

##463 matches in [am-x-ec.csv](am-x-ec.csv)

In [am-x-ec.csv](am-x-ec.csv) you'll find the identifiers of 463 persons that exist in both the Amsterdam Museum and Ecartico datasets.

###fields:
- id: internally used id
- am_priref: the priref (id) for persons used in the Amsterdam Museum collection database
- ec_id: the id for persons used in Ecartico
- am_uri: a persons uri at the Amsterdam Museum (not yet available)
- ec_uri: a persons uri at Ecartico
- name_exact, name_fuzzy, rkd_uri, bd_years, bd_dates: these fields show where a match was found - 'bd_years' meaning years of birth and death, 'bd_dates' the exact dates of birth and death.
- matched: _true_ if we considered it an actual match (all persons in this csv file are considered a match)

##4194 urls in [am-personen-urls.csv](am-personen-urls.csv)

In [am-personen-urls.csv](am-personen-urls.csv) you'll find all the urls with persons from the Amsterdam Museum collection database. 

- 1233 records marked 'am' allready existed in the collection database. Some of these were 'cleaned' - links to RKDartists where changed to their nowadays permalinks, in many cases 'http://' was prepended to the url.
- 2108 records marked 'rkd opensearch' were found when we held artist names against the RKD opensearch
- 463 records marked 'matched' are the matches mentioned above and link to Ecartico uri's.
- 47 records marked 'ecartico' are links with matched persones from Ecartico
- 342 records marked 'htn', almost exclusively to biografischportaal.nl, were added by Harm

###fields:

- id: only used internally
- priref_persoon: the priref (id) for persons used in the Amsterdam Museum collection database
- url: the url to information about a person elsewhere
- herkomst: the marks mentioned above