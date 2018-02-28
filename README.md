# datos.mapanica.net

Here can you find the data and the website used by [datos.mapanica.net](https://datos.mapanica.net).

## GTFS files

This is the official source for the updated GTFS files for the urban buses of [Estelí](ni-esteli-gtfs.zip) and [Managua](ni-managua-gtfs.zip) and for the national buses of whole [Nicaragua](ni-gtfs.zip).

Here's a little list with all the GTFS consumers using these files:

### transit.land

_Updated automatically_

* [Estelí](https://transit.land/feed-registry/operators/o-d46d6-nicaragua~estel%C3%AD)
* [Managua](https://transit.land/feed-registry/operators/o-d44t-nicaragua~institutoreguladordeltransportedelmunicipiodemanagua)

### transitfeeds.com

_Submitted, but not integrated yet_

* Estelí
* Managua

### navitia.io

_Updated automatically once a week_

Both GTFS files are loaded into the same `coverage`: [Nicaragua](http://api.navitia.io/v1/coverage/ni)

This backend is already used by Transportr and is currently being integrated into public-transport-enabler (see PR [#181](/schildbach/public-transport-enabler/pull/181))

### TransitApp

_Updated automatically every night, at 1AM in Montréal timezone_

Both GTFS files have been loaded into it's backend: [Nicaragua](https://transitapp.com/region/managua)

