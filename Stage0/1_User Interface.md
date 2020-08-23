# USER INTERFACE

## Feature

This module delivers PLAYING AREA, MOVABLE PAD, MOVABLE BALL,
SCORE DISPLAY, BACKGROUND DESIGN

## Acceptance Criteria

### Scenario: Playing area size

  Given the x-y dimensions

  When game launched

  Then the playing area with given dimension is setup by this module

### Scenario: Background

  Given the background type(i.e., colour,image, video), dimensions

  When game launched

  Then the background is setup for playing area by this module

### Scenario: Pad

  Given the pad specifications

  When game launched

  Then two 1 dimensional floating pad is setup within playing area
  by this module
  
  ----------------------------------------------------------------
  
  When **MOVE PAD** calls
  
  Then pad moves up and down
  
### Scenario: Ball

  Given the Ball specifications
  
  When game launched

  Then one 2 dimensional movable ball is setup within playing area
  by this module
  
  ----------------------------------------------------------------
  
  When **BALL MOVER** calls
  
  Then ball moves within playing area  
  
### Scenario: Score Display

  Given the dimension for score display
  
  When game launched
  
  Then score display for two players is setup within given area
  by this module
  
  ----------------------------------------------------------------
  
  When **MARK UPDATER** call
  
  Then score incremented for anyone of the player
  as mentioned by **MARK UPDATER**
