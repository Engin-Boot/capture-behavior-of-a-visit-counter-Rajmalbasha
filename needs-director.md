# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given "entry id" as sensor input and details are stored in database.
  
  When patient arrives an fresh "entry id" is issued in his name.
  
  On entering "entry id" is swiped at entry point.
  
  Count increases by 1.
  
  Then count will show the number of patients.

Scenario: Compute parking slots to reserve for visiting specialists

  Given
  When
  Then
