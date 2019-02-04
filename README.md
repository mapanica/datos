# datos.mapanica.net

Here can you find the data and the website used by [datos.mapanica.net](https://datos.mapanica.net).

## GTFS files

This is the official source for the updated GTFS files for the urban buses of [Estelí](ni-esteli-gtfs.zip) and [Managua](ni-managua-gtfs.zip) and for the national buses and ferries of whole [Nicaragua](ni-gtfs.zip).

Here's a little list with all the GTFS consumers using these files:

### transit.land

_Updated automatically_

* [Estelí](https://transit.land/feed-registry/operators/o-d46d6-nicaragua~estel%C3%AD)
* [Managua](https://transit.land/feed-registry/operators/o-d44t-nicaragua~institutoreguladordeltransportedelmunicipiodemanagua)
* Nicaragua _(submitted, but not integrated yet)_

### transitfeeds.com

_Submitted, but not integrated yet_

* Estelí
* Managua

### navitia.io

_Updated automatically once a week_

__Caution: Up to now, Navitia only supports validation periods up to twelve months, so there is a need to deploy updated GTFS files at least once a year!__

The three GTFS files are loaded into the same `coverage`: [Nicaragua](http://api.navitia.io/v1/coverage/ni)

This backend is integrated into [public-transport-enabler](/schildbach/public-transport-enabler/) and used in production by [Transportr](https://transportr.app/) and [Öffi](https://oeffi.schildbach.de/).

### TransitApp

_Updated automatically every night, at 1AM in Montréal timezone_

Managua and Estelí GTFS files have been loaded into it's backend: [Nicaragua](https://transitapp.com/region/managua)

