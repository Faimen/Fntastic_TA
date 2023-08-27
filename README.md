# Fntastic_TA

## TODO:

- [x]  HP Attribute
- [x]  AI Activation trigger
- [x]  Take damage
    - [x]  If damage is received, begin “Pursuit”.
    - [x]  Die
- [x]  Character
    - [x]  Action Sounds
        - [x]  Shoots
        - [x]  Steps
    - [x]  Dealing damage
- [x]  AI
    - [x]  FOV
        - [x]  Cone radius: 3000
    - [x]  Hear sounds
        - [x]  Circle radius: 5000
    - [x]  States
        - [x]  Patrol
            - [x]  Initial point
            - [x]  Circle radius: 2000
        - [x]  Exploring
            - [x]  Start exploring the heard sound in the range of 1000
            - [x]  If no player, go to Patrol state
        - [x]  Pursuit
            - [x]  Move to target pos
            - [x]  If target_pos > FOV+500, move to the last target. If there is no target, return to the "Patrol" state.
