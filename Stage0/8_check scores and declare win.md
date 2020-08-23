# Check scores and Declare win

## Feature

This module checks scores when updated and declare winner

## Acceptance Criteria

### Scenario: Anyone player reached maximum/target score

  Given the game is running and mark updated

  When anyone player reached maximum/target score
  
  Then that player is declared and displayed as winner and
  calls **REPLAY/QUIT** module
  
### Scenario: Any player didn't reach maximum/target score

  Given the game is running and mark updated

  When both scores are less than maximum/target score
  
  Then call **START FROM** module
