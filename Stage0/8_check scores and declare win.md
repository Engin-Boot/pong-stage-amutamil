# Check scores and Declare win

## Feature

  Check scores when updated and declare winner
  or continue game if not target score reached

## Acceptance Criteria

### Scenario: Quit when one reaches maximum/target score

  Given the game is running and mark updated

  When anyone player reached maximum/target score
  
  Then that player is  displayed as winner and
  calls **REPLAY/QUIT** module
  
### Scenario: Continue after score updated

  Given the game is running and mark updated

  When both player's scores are less than maximum/target score
  
  Then call **START FROM** module
