# sail_race_timer
Sequencer to sound horn at defined times at start of sailboat races
User selectable sequence from pre-defined set of sequences

System consists of
  1. Remote: Arduino based sequencer, display (LED 7 segx4 and/or LCD16x2), menu button, relay; custom PCB
  2. three wire connection between remote and horn base
  3. Horn base: electric horn 12 volt, 40 amp relay to activate motor, whcih is activated by the relay in the remote
  4. two wire connection between horn base and 12 volt car/marine battery
