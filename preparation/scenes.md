# Scenes and scripts

## Scripts

Some global autoloads that i can think of rn:
	- sound effects in transitions
	- background music
	- input manager
	- game state
	- game save manager
	- dialogue manager
	- globals, helper functions, math

## Recurring scenes:

- Scene 3.x: bare-bones static staircase scene
- Scene 3.3x: main staircase scene (only spawns enemies of 3.3x)
- Scene 4.1/4.2/...: dungeon floor hallways
- Scene 5.1/5.2/...: dungeon room
- Scene 9.x: bare-bones image + text

## Chronological scenes:

- Scene 0: main menu
- Scene 1: bedroom including house
- Scene 2: house (not interactive anymore), door opens to outside
- Scene 3: main staircase scene, no enemies
- Scenes: 4.x, 5.x
- repeat multiple times: 3 -> 4.x -> (5.x -> 4.x, repeat y times) -> 3

- Scene 3.1 (inherited): same staircase scene
	- resting area, nyx comes from behind and knocks player out
- Scene 3.2: same staircase, dialog before being dropped
	- falling monologue

- Scene 6: lands on bottom floor, cornered
- Scene 7: wakes up, campfire & ember introduction
- Scene 3.31

 After floor 4 clear:
- Scene 4.a
- look for mats (repeat): 4.a -> (5.a -> 4.a, repeat y times)
- break 1, campfire + conversation 1 (still in 4.a)
- Scene 3.32

After floor 8 clear:
- Scene 4.b
- look for mats (repeat): 4.b -> (5.b -> 4.b, repeat y times)
- break 2, another area + conversation 2  (still in 4.b)
- Scene 3.33.0: inherited staircase
	- only triggers argument after clearing floor 12
	- everything else stays the same as 3.3x

After floor 14 clear:
- Scene 4.c
- look for mats (repeat): 4.c -> (5.c -> 4.c, repeat y times)
- player doesn't spot ember, goes back to main staircase

- Scene 3.4: cutscene of ember being attacked
- Scene 3.5: final battle
- Scene 3.6: cutscenes of killing nyx & moments before death
- Scene 8: narrate "In the span... [...] ...was ever one."

- Scene 9.1: image + "His eyes... [...] ...'s magic."
- Scene 9.2: image + "L... [...] ... at an academy."
- Scene 9.3.0: image + "Nora and Ember... [...] ... enough."
	- credits, thanks, assets sources
