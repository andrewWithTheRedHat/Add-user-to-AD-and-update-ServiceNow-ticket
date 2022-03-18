# Using AD And ServiceNow to add or remove users and update a ticket

A quick and dirty playbook for updating user objects for active directory through ServiceNow (SNOW).  This will add or remove a user and then update the ticket in SNOW.  A couple of things:
  - this is started in SNOW
  - most of the variables are going to be from SNOW
  - you will need winRM in your connection type
