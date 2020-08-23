# Start from

## Feature

This module decide the side from which the ball has to start

## Acceptance Criteria

### Scenario: Setting the ball position to start to move

  Given the UI is setup

  When the **START BUTTON** is clicked
  
  Then the ball starts from 'Player one'
  
  --------------------------------------
  
  When **MARK CHECKER** calls this module
  
  Then ball starts from player whose score gets incremented last
