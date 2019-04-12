# lswebmap
A webmap made to visualise loadshedding in South Africa by shifting the symbology of point features based on whether or not they are scheduled to be loadshedding given a particular time, date and loadshedding stage. This information is automatically collected upon visiting the site, but can be manually set.

Additionally it allows the user to view an animation of how loadshedding progresses through timeframes.

The project currently has the following limitations:
- It is limited to Eskom loadshedding schedules, hence it would not nescesarily be accurate for areas in municipalities with their own schedules, such as City of Cape Town.
- It does not make provision for overlap of time slots.
- It is based on point, rather than area data, which works well for visualisation, but greatly limits utility.
