# visit-counter technical needs 

Scenario: Recover across restarts of the serverthat runs the visit-counter.

Given entry card is sensor input and data is stored on server.
When the server goes down and restarts
Then restore the data from backups or shared disk.
