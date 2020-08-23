# Move in direction

## Feature

This module moves the ball in different directions(2D) within playing area

## Acceptance Criteria

### Scenario: Determine direction of ball movement

  Given the UI is setup and game is running

  When the ball start to move from one of the player
  
  Then the direction is set as '180 degree and' or
  horizontal
  
  --------------------------------------
  
  When **COLLISION DETECTOR** calls **DETERTMINE DIRECTION**
  
  Then direction/angle is changed according to previous direction
  or angle of collision

### Scenario: Move ball in specific direction

  Given the direction from **DETERMINE DIRECTION** module and ball and playing area
  
  When game is running
  
  Then ball moves in direction/angle specified by **DETERMINE DIRECTION**
