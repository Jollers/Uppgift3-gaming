The database is ignored in .gitignore (App_Data/Umbraco.sdf)
Because it changes all the time.
To commit a copy of the database, make a copy of App_Data/Umbraco.sdf and call it db-dump.sdf.

Note: The reverse is true. If someone has made an important db-change then cope d-dump.sdf to Umbraco.sdf...