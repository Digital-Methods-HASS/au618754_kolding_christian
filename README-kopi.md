Clarification of column names for metadata set "Africa_19_20.csv":

FILTERED OUT - ISO: Unclear.
FILTERED OUT - EVENT_ID_CNTY:	An	individual	event	identifier	by	number	and	country	acronym.
FILTERED OUT - EVENT_ID_NO_CNTY:	An	individual	event	numeric	identifier.
EVENT_DATE:	Recorded	as	Day	/	Month	/	Year.
YEAR:	The	year	in	which	an	event	took	place.
FILTERED OUT - TIME_PRECISION:	A	numeric	code	indicating	the	level	of	certainty	of	the	date	coded	for the	event	(1-3).
EVENT_TYPE:	The	type	of	event.
SUB_EVENT_TYPE:	The	type	of	sub-event.
ACTOR1:	A named	actor	involved	in the	event.
ASSOC_ACTOR_1: The	 named	actor	associated with	 or	identifying with ACTOR1	in	 one	specific	event.
FILTERED OUT - INTER1:	A	numeric	code	indicating	the	type	of	ACTOR1.
ACTOR2:	The	named	actor	involved	in	the	event.	If	a	dyadic	event,	there	will	also	be	an	“Actor	1”.
ASSOC_ACTOR_2:	The	 named	actor	associated with	 or	identifying	with	ACTOR2	in	 one specific	event.
FILTERED OUT - INTER2:	A	numeric	code	indicating	the	type	of	ACTOR2.
FILTERED OUT - INTERACTION:	A	numeric	code	indicating	the	interaction	between	types	of	ACTOR1	and	
ACTOR2.	 Coded	 as	 an	 interaction	 between	 actor	 types,	 and	 recorded	 as	 lowest	 joint number.
REGION: The region of the world where the event took place.
COUNTRY:	The	country	in	which	the	event	took	place.
ADMIN1:	The	largest	sub-national	administrative	region	in	which	the	event	took	place.
ADMIN2:	The	second	largest	sub-national	administrative	region	in	which	the	event	took	place.
ADMIN3:	The	 third	largest	sub-national	administrative	 region	in	which	 the	event	 took	place.
LOCATION:	The	location	in	which	the	event	took	place.
LATITUDE:	The	latitude	of	the	location.
LONGITUDE:	The	longitude	of	the	location.
FILTERED OUT - GEO_PRECISION:	A	numeric	code	indicating	 the	level	of	certainty	of	 the	location coded	for	the	event.
SOURCE:	The	source(s) used	to	code	the	event.
SOURCE	SCALE: The geographic	scale	of	the	sources	used	to	code	the	event.
NOTES:	A	short	description	of	the	event.
FATALITIES:	 Number	 or	 estimate	 of	 fatalities	 due	 to	 event.	 These	 are	 frequently	different	across	reports.
FILTERED OUT - TIMESTAMP: Unclear.
FILTERED OUT - ISO3: Unclear.

Taken from https://acleddata.com/download/35136/ 

Clarification of column names for data frame "countrydata":

COUNTRY:	The	country	in	which	the	event	took	place.
NUMBER_OF_EVENTS: The number of events reported in the country.
FATALITIES:	 Number	 or	 estimate	 of	 fatalities	 due	 to	 events for each country.	 These	 are	 frequently different	across	reports.
GDP-per-capita: GDP per capita in 2020 for each country.
political_stability_index: The stability in political and governmental issues in countries. 
HDI-value: Human Development index gives an estimate of how developed a country is based on several factors.
population: The population in the given country in 2020. 
event_index: Our own index made by dividing the number of events per country by their respective population in order to get a more representative figure for each country. 