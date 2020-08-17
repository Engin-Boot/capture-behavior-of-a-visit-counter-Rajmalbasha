# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given "entryid" as sensor input and details are stored in database.
  
  When patient arrives an fresh "entryid" is issued in his name.
  
  On entering "entryid" is swiped at entry point.
  
  Count increases by 1.
  
  Then count will show the number of patients.

Scenario: Compute parking slots to reserve for visiting specialists

  Given
  When
  Then
