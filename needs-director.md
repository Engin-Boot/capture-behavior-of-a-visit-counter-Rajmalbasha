# Visit-counter for a director

Scenario: Show patient visits during working days and holidays

Given calendar synced entry card issuer issues card in patient name and

contains accompanied by count as well, database stores data

When director enters date/day and press patient-count button

provided entry card issuer and database working

Then display count on particular day

Scenario: Compute parking slots to reserve for visiting specialists

Given an active sensor senses the available parking slots

When the available parking slots falls below a threshold limit(<5 slots)

Then the remaining parking slots should be freezed. 
