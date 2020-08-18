# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation
Given visitor count per day stored in database with date
count resets daily and sensor is working
When the manager press visitor trends provided start date
Then the visitor count of a week with the start date displayed

Scenario: Alert when seating capacity is full

Given an active seating capacity monitoring system

When the available seats go below threshold

Then raise an alert to facilities manager  
