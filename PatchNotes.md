

Fixes

bfs - now returns -1 if queue becomes empty (exists the loop)

Replay and Bugs

I wanted skippy to go down and not the food, not sure why safety_protocol was not working (needs implementing) https://play.battlesnake.com/g/6703ff00-9268-4c71-803f-febaed464385/#

Still getting trapped! https://play.battlesnake.com/g/44cee6c5-35bb-4443-968c-3dc832d417f0/#

Enemy Snake grew by 1 and I went for their tail https://play.battlesnake.com/g/9ed71d45-d54e-4b12-90e4-efcd9eeaaa3c/#

kill_snakes - skippy will keep on hunting enenmy head until he starves or until they grow bigger than him and skippy will proceed to eat to match them.

Should have gone for the green tail https://play.battlesnake.com/g/c00d8640-432a-41a4-a4c2-5ed594af1967/#

Coding Issue

Everytime I want to access the value of the tile, I need to check if it is a list, something better should replace this

End of Patch Notes
