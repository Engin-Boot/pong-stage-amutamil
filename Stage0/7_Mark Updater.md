# Mark Updater

## Feature

This module update scores for players

## Acceptance Criteria

### Scenario: Updating mark for 'Player 2'

  Given the game is running

  When the **COLLISION DETECTOR** detects collision on left boundary
  
  Then **MARK UPDATER** increase score for
  'player 2'(player on right side)
  
  ### Scenario: Updating mark for 'Player 1'

  Given the game is running

  When the **COLLISION DETECTOR** detect collision on right boundary
  
  Then **MARK UPDATER** increase score for
  'player 1'(player on left side)
