# Fntastic_TA

## TODO:

- [ ]  HP Attribute
- [ ]  AI Activation trigger
- [ ]  Take damage
    - [ ]  If damage is received, begin “Pursuit”.
    - [ ]  Die
- [ ]  Character
    - [ ]  Action Sounds
        - [ ]  Shoots
        - [ ]  Steps
    - [ ]  Dealing damage
- [ ]  AI
    - [ ]  FOV
        - [ ]  Cone radius: 3000
    - [ ]  Hear sounds
        - [ ]  Circle radius: 5000
    - [ ]  States
        - [ ]  Patrol
            - [ ]  Initial point
            - [ ]  Circle radius: 2000
        - [ ]  Exploring
            - [ ]  Start exploring the heard sound in the range of 1000
            - [ ]  If no player, go to Patrol state
        - [ ]  Pursuit
            - [ ]  Move to target pos
            - [ ]  If target_pos > FOV+500, move to the last target. If there is no target, return to the "Patrol" state.
