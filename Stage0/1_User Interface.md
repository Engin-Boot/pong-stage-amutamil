# USER INTERFACE

## Feature

This module delivers PLAYING AREA, MOVABLE PAD, MOVABLE BALL,
SCORE DISPLAY, BACKGROUND DESIGN

## Acceptance Criteria

### Scenario: Creating playing area

  Given the x-y dimensions

  When game launched

  Then create the playing area

### Scenario: Designing Back ground

  Given the back ground specifications

  When game launched

  Then the back ground is setup for playing area by this module

### Scenario: Designing the Pad

  Given the pad specifications

  When game launched

  Then two 1D floating pad designed for given specification
  
  ----------------------------------------------------------------
  
  When **MOVE PAD** calls
  
  Then pad moves up and down
  
### Scenario: Designing Ball

  Given the Ball specifications
  
  When game launched

  Then one 2D movable ball designed for given specification
  
  ----------------------------------------------------------------
  
  When **BALL MOVER** calls
  
  Then ball positions changes within playing area
  
### Scenario: Score Display

  Given the dimension for score display
  
  When game launched
  
  Then score display for two players designed
  
  ----------------------------------------------------------------
  
  When **MARK UPDATER** call
  
  Then score changes for any of the player
