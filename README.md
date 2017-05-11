# hudhead-metro

---

### description

hudhead metro is a project to create a browser based train signalling and timetable system based on a region built in the game openttd

---

### setting

hudhead is the principle settlement on walney island in the county of cumbria in england (formally lancashire), extending out from lower furness. the concept is borrowed from the island of sodor in thomas the tank engine. like barrow-in-furness, hudhead was a centre of steel production and shipbuilding, due to rich ore deposits in the hilly centre of walney island, as well as a large port like liverpool.

the heightmap used is derived from the island of menorca in spain, then rotated and merged into a heightmap of the north west region of england to a geographically accurate scale.

---

### scope and aims



---

# list of properties

#### measurement

* world size: 1024x512 cells
* cell size: 40x40 metres
* illustrator/svg artboard size: 4096x2048px (1px = 10 metres)
* time: 1 hour = 60 seconds
* speed: 1km/h = 25 cells/60 seconds

#### track

* topography: track/station
* track type: passenger/freight/mixed
* line: name of line
* cardinal direction: up/down
* length: xx cells
* signal block: line code (ABC) + signal id (123)
* speed limit: xx km/h
* operator: operator name

#### station

* name: station name
* station block (acts as signal block): station code (ABC) + signal id (123)
* length: xx cells

#### train

* train class: e.g. 377 electrostar
* train id: operator code (ABC) + train number (123)
* train type: passenger/freight
* operator: operator name
* number of carriages: xx
* weight: number of carriage x carriage weight
* length: number of carriage x carriage length
* commercial operating speed: xx km/h
* breaking distance: a special formula composed of speed, weight, length

#### carriage

* weight: xx tonnes
* length: x cells
* capacity: xx persons (may control carriage weight at some point)
