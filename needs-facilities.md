# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation
Given visitor count per day stored in database with date
count resets daily early morning and sensor is working
When the start date of a week is given
Then the visitor count of a week with the start date displayed
