# Interaction Sequences

## Startup Sequence

* All modules under **UI** is setup
  
* **start button** clicked
  
* **Input fetch** module activated

## Movement Initiation

* **Input fetch** module moves pad
  
* **Determine direction** module determines direction
  of ball movement
  
* **Ball mover** module moves ball as specified by
  **Determine direction** module

* when ball hit up/left wall or pad, direction changed
  
## One score

* **Collision detector** module checks for collision

* When ball hit left/right wall, then mark updated
  by **Mark Updater** module
   
* **Winner declare** module displays winner

* **Replay or Quit** module navigate to start or exit game play

![alt text](https://github.com/Engin-Boot/pong-stage-amutamil/blob/master/Stage0/sequence%20-start.png?raw=true)
