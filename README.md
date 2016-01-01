# DZ_JSON
Utilities for the creation of JSON and GeoJSON from Oracle data types and structures.
For the most up-to-date documentation see the auto-build  [dz_json_deploy.pdf](https://github.com/pauldzy/DZ_JSON/blob/master/dz_json_deploy.pdf).

Note these packages were created in the Oracle 10g days to transform Oracle and Oracle Spatial objects into JSON with GeoJSON as CLOBs to then drive REST-like sevices via mod_plsql.  They do not in any way utilize the new JSON handling options of Oracle 12c.   

## Installation
Simply execute the deployment script into the schema of your choice.  Then execute the code using either the same or a different schema.  All procedures and functions are publically executable and utilize AUTHID CURRENT_USER for permissions handling.
