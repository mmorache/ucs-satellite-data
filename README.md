# UCS Satellite Data

This repository contains a Jupyter notebook that cleans, normalizes, and enriches the UCS Satellite Database (current as of May 1, 2023) to make it easier to explore and analyze. The primary focus is on the launch data, not the orbital data.

While the accuracy of the cleanup isn't 100%, it turns a very messy real-world dataset into something that’s consistent, readable, and ready to go for BI tools like QuickSight or Tableau.
analysis-ready

Along the way, it documents the reasoning behind each cleanup step (what was changed, why, and what was intentionally left alone), rather than just applying opaque transformations.

Along with the usual cleanup, some of the big wins are are normalized
* organizations (contractors and operators)
* launch vehicles
* orbit classifications
* launch locations with extrapolated geospatial data
* derived metrics like years in orbit and distance from the equator