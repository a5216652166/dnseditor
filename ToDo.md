  * Add SPF generator to TXT records editor.
  * dd a verification function, to verify either a specific zone, or all zones in your DB, and generate a report (similar to dnsreports.com).
  * Add authentication, on a per zone, and possibly fine grained control of which records in a zone are allowed to be updated. Would most likely require seperate permissions table.
  * Add a database abstration layer for both different RDBMS and different table layout – I would love some suggestions on this. (MAJOR)