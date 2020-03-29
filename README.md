# DBMS-UF-UK_Accidents

<h3> The Schema \m/</h3>

➢ Vehicles (v-id: integer, d-id: integer, driven_by: integer, point of impact: integer, type of vehicle: string, engine type: string, type of axle: string, ownership: string, no of wheels: integer)

➢ Driver (d-id: integer, age: integer, sex: string, age band: integer)

➢ Accidents (c-id: integer, idx: integer, l-id: integer, condition: integer, loc: integer, day of week: integer, severity: integer, a_time: time, a_date: date, no of vehicles: integer)

➢ Conditions (c-id: integer, light: string, weather: string, road: string)
➢ Casualties (idx: integer, accidents: integer, type: string, class: string, sex: string, age: integer, age band: integer, severity: integer)

➢ Location (l-id: integer, road: string, link length: double, road type: string, speed limit: integer, latitude: double, longitude: double, easting: double, northing: double, junction start: string, junction end: string, junction length: double)

➢ Region (l-id: integer, local authority: string, type of region: string)

➢ Involves (d-id: integer, v-id: integer, c-id: integer, idx: integer, l-id: integer)

➢ Occur In (c-id: integer, l-id: integer)



To-Do List:

1. Create Primary Key for each table using the Schema.
2. Create individual CSV files for each entity.
3. Complete the list
