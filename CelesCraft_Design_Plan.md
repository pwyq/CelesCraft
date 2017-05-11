********************************
		BASIC INFO
********************************
- Start Date: May 9, 2017
- Game Name: CelesCraft
- Game Developers: Dawn Cheng, Yanqing (Peter) Wu
- Game Language: English / Chinese (2 versions maybe)
- Game Platform: PC (Windows)
- Purpose of making this Game: Lian Shou, ~~Zhuan Qian~~, Lian Shou
- Programming Language: C++ (mainly)

********************************
		NEED TO BE DONE
********************************

**_everthing_**

********************************
		NEED TO LEARN
********************************
Following is for 3D Render
> 1. [learning how to write a 3D soft engine from scratch in C#, TypeScript or JavaScript](https://www.davrous.com/2013/06/13/tutorial-series-learning-how-to-write-a-3d-soft-engine-from-scratch-in-c-typescript-or-javascript/)
> 2. [Let's Build a 3D Graphics Engine: Points, Vectors, and Basic Concepts](https://gamedevelopment.tutsplus.com/tutorials/lets-build-a-3d-graphics-engine-points-vectors-and-basic-concepts--gamedev-8143)
> 3. [Advice - Create a 3D engine from Scratch](https://www.reddit.com/r/cpp/comments/3g1pvf/i_want_to_create_a_3d_engine_from_scratch_where/)
********************************
		GAME STORY
********************************

do it later

********************************
	Game MECHANICS/CONCEPT
********************************
Number of Game player: Single

Game Difficulty: easy / normal / hard / hell mode, etc (by changing the required amount of resources and the frequency of attack of enemies)

Game Enemy:	+ Unknown Living Creatures
			+ Environmental Activities

Game Goal: Expand player's territory to reach a certain rate

Game Manipulation:	+ Directoin controls (keyboard inputs)
					+ Function controls (keyboard inputs)
					+ Mouse inputs

Game Performance: 2D / 2.5D / 3D (depends, but we want 3D Sandbox Game)

Game Possible Endings:	+ Winning
							- reaching a certain goal
						+ Losing
							- run out of resources
							- spaceships crashes

Game Resource: (Better restrict to 2-3 resources, such as minearls, money, gas)

Game UI: do it later

Game UX: do it later

Game System:+ Enhancement of Spaceships
			+ Exploration of Planets
			+ Management of Planets

********************************
	 BASIC INFO OF PLANETS
********************************
Notes:
1. May add a self-created secret planet
2. Need to find fun facts of these planets

**Earth** - *Our Home*
- Equatorial Radius: 6.3710 x 10^3 km
- Volume: 1.08321 x 10^12 km3
- Mass: 5.9722 x 10^24 kg 
- Density: 5.513 g/cm^3
- Surface Area: 5.1006 x 10^8 km^2
- Surface Gravity: 9.80665 m/s^2
- Surface Temperature: -88/58 (min/max) celsius

**Mercury** - *our solar system's smallest planet*
- Volume: 0.056 x Earth's
- Mass: 0.055 x Earth's 
- Density: 0.984 x Earth
- Surface Area: 0.147 x Earth
- Surface Gravity: 0.38 x Earth
- Surface Temperature: -173/427 celsius
- 88 days in Mercury equals 1 Earth year.

**Venus** - *our solar system's hottest planet*
- Volume: 0.857 x Earth's
- Mass: 0.815 x Earth's 
- Density:  Comparable to the average density of the Earth.
- Surface Area: 0.902 x Earth
- Surface Gravity: 0.91 x Earth
- Surface Temperature: 462 celsius
- 243 days in Venus equals 1 Earth year.

**Mars** - *The Red Planet*
- Volume: 0.151 x Earth's
- Mass: 0.107 x Earth's 
- Density: 0.714 x Earth
- Surface Area: 0.283 x Earth
- Surface Gravity: 0.38 x Earth
- Surface Temperature: -153 to +20 celsius
- 1.026 days in Mars equals 1 Earth day.

**Juipter** - *King of the Planet*
- Volume: 1321.337 x Earth's
- Mass: 317.828 x Earth's 
- Density: 0.241 x Earth
- Surface Area: 120.414 x Earth
- Surface Gravity: 2.53 x Earth
- Surface Temperature: -173/427 celsius
- 0.41 days in Juipter equals 1 Earth day.

**Saturn** - *Jewel of Our Solar System*
- Volume: 763.594 x Earth's
- Mass: 95.161 x Earth's 
- Density: 0.125 x Earth
- Surface Area: 83.543 x Earth
- Surface Gravity: 1.07 x Earth
- Surface Temperature: -178 celsius
- 0.444 days in Saturn equals 1 Earth day.

**Uranus** - *The Sideways Planet*
- Volume: 63.085 x Earth's
- Mass: 14.536 x Earth's 
- Density: 0.230 x Earth
- Surface Area: 15.847 x Earth
- Surface Gravity: 0.91 x Earth
- Surface Temperature: -216 celsius
- 0.72 days in Saturn equals 1 Earth day.

**Neptune** - *The Windiest Planet*
- Volume: 57.723 x Earth's
- Mass: 17.148 x Earth's 
- Density: 0.297 x Earth
- Surface Area: 14.980 x Earth
- Surface Gravity: 1.14 x Earth
- Surface Temperature: -214 celsius
- 0.671 days in Saturn equals 1 Earth day.

**Pluto** - *The smallest planet in the solar system tand the ninth planet from the sun*
- Volume: 0.006 x Earth's
- Mass: 0.002 x Earth's 
- Density: 0.372 x Earth
- Surface Area: 0.033 x Earth
- Surface Gravity: 0.07 x Earth
- Surface Temperature: -233 to -223 celsius
- 6.387 days in Saturn equals 1 Earth day.

**Earth's Moon** - *Our natural Satellite*
- Volume: 0.020 x Earth's
- Mass: 0.0123 x Earth's 
- Density: 0.607 x Earth
- Surface Area: 0.074 x Earth
- Surface Gravity: 0.166 x Earth
- Surface Temperature: -233 to 123 celsius

**Sun** - *Our Star*
- Volume: 1,301,018.805 x Earth's
- Mass: 333,060.042 x Earth's 
- Density: 0.256 x Earth
- Surface Area: 11,917.067 x Earth
- Surface Gravity: 27.96 x Earth
- Surface Temperature: 5500 celsius

********************************
		EXTRA NOTE
********************************

1. How to label game/app version?
[Major build number].[Minor build number].[Revision].[Package]

....i.e. Version: 1.0.15.2

- Major build number: This indicates a major milestone in the game, increment this when going from beta to release, from release to major updates.
- Minor build number: Used for feature updates, large bug fixes etc.
- Revision: Minor alterations on existing features, small bug fixes, etc.
- Package: Your code stays the same, external library changes or asset file update.

2. Some notation
- `<!test>` 		<== becomes red in Sublime
- `<!-- test -->` 	<== becomes green in Sublime