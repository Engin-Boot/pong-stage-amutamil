# Collision Detector

## Feature

This module detects collision of ball

## Acceptance Criteria

### Scenario: Collision with pad or Up/down boundary

  Given the game is running and ball is moving

  When the ball touches up/down boundary or any of the two pads
  
  Then this module detect that as collision and calls **DETERMINE DIRECTION**
  
### Scenario: Collision with left boundary

  Given the game is running and ball is moving

  When the ball touches left boundary
  
  Then this module detect that as collision and calls **MARK UPDATER**
  and increase score for player one(one who is in right side)
  
  ### Scenario: Collision with right boundary

  Given the game is running and ball is moving

  When the ball touches right boundary
  
  Then this module detect that as collision and calls **MARK UPDATER**
  and increase score for player two(one who is in left side)
