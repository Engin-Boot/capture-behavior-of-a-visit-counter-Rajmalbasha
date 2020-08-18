# visit-counter technical needs

Scenario: Recover across restarts of the server that runs the visit-counter.
Given entry card is sensor input and data stored on server.
When the server goes down and restarts
Then restore the data from backups or shared disk and push the
local data on sensor to the server.

Scenario: Reconcile count if the sensor is offline for a while

Given an active sensor for counting visitor and server

stores the data

When sensor is offline for a while

Then manually enter the details on server and reconcile

when sensor is back online
