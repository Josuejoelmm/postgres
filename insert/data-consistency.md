# Data consistency
When an `INSERT` occurs there are 3 different possibilities that need to consider.

1. When we INSERT a record that is tied to a reference of a remote row that actually exist. `Everything works OK`

2. When we INSERT a record that refers to a remote row id that NOT exist. `An error!`

2. When we INSERT a record that isn't tied to any remote row_id. `Put in a value of 'NULL'`