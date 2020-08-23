# Mark Updater

## Feature

This module update scores for players

## Acceptance Criteria

### Scenario: Incrementing score for 'Player 2'

  Given the game is running and ball is moving

  When the **COLLISION DETECTOR** detects ball collision on left boundary
  
  Then **MARK UPDATER** increment score for
  'player 2'(player on right side)
  
  ### Scenario: Incrementing score for 'Player 1'

  Given the game is running and ball is moving

  When the **COLLISION DETECTOR** detect ball collision on right boundary
  
  Then **MARK UPDATER** increment score for
  'player 1'(player on left side)
