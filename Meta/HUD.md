![[Pasted image 20260604220017.png]]

After picking up [[Meta Tiles]], the part of my [[HUD]] is gone, and my [[Magic Rod]] has a "?" in it.
![[Pasted image 20260604005725.png]]

# Tech
- I can take [[Meta Floor Tens Tile]], replace the [[Meta Locust Value Tile]] with it, and then die to increase my [[Locusts Idol]]s
	- More interestingly, this allows me to rewind back to whatever level I actually want down to the lowest hundreds place
	- **REMEMBER TO GIVE MYSELF THE [[Meta Locust Value Tile]] FIRST!!!

# Behavior

After a level transition, the [[HUD]] will reset each tile accordingly.
1. Left most tile is set to either blank or [[Meta Gem Tile]]
2. [[HP Tile]] is set
3. [[HP Value Tile]] defaults to `00` if missing, otherwise stays the same
4. Blank tile
5. [[Meta Locust Idol Tile]] is set
6. [[Meta Locust Value Tile]] defaults to `00` if missing, otherwise stays the same
7. [[Meta Rod Tile]] is set if I have it
8. Blank tile
9. [[Meta Memory Tile]] is set if I have it
10. [[Meta Wings Tile]] is set if I have it
11. [[Meta Sword Tile]] is set if I have it
12. Blank tile
13. [[Meta Floor Hundreds Tile]]
14. [[Meta Floor Tens Tile]] (if missing, crash)

After a death in level, the [[HUD]] will reset each tile accordingly.
1. Left most tile is set to either blank or [[Meta Gem Tile]]
2. [[HP Tile]] is set
3. [[HP Value Tile]] defaults to `07`
4. Blank tile
5. [[Meta Locust Idol Tile]] is set
6. [[Meta Locust Value Tile]] takes one away from previous value
7. [[Meta Rod Tile]] is set if I have it
8. Blank tile
9. [[Meta Memory Tile]] is set if I have it
10. [[Meta Wings Tile]] is set if I have it
11. [[Meta Sword Tile]] is set if I have it
12. Blank tile
13. [[Meta Floor Hundreds Tile]] set to previous value
14. [[Meta Floor Tens Tile]] set to previous value