# Folders-Gambit

## Core Elements

* Step Time Strategy / Simultaneous Turn-based Strategy game (STS)
    * Neither consecutively turn based nor an RTS
    * Both players select moves within a time frame
    * At the end of the time frame the selected moves are played
    * The game steps to the next time frame, starting the next turn, and the game loop continues
* Points are accrued every time step
* Points are spent to take action on the board 
* Board is a hex grid (different sizes available)
* Varying time between moves available
* Visible vs. Fog map (or hybrid)
* Actions are broadly categorized as following
    * Move units
    * Attack and defense
    * Production

## The simplified version of Folder's Gambit

* Board is appropriately sized for fitting on a phone screen
* Units cannot be individually upgraded
* Units can be joined into a single unit
* Basic units have 1 attack and 3 defense
* There is no attack cool down
* Rate of point accruement cannot increase via production upgrades 

## The resource collection version of Folder's Gambit

* Individual units can be upgraded
    * Attack power damage per turn (dpt)
    * Defense
    * Range
    * Precision
    * Heal
    * Decrease cool down times
        * A cool down is expressed in turn based units
        * A 1 turn cool down means a unit can only attack every other turn
        * Default units can attack every turn (0 turn cool down)
        * Upgrade a unit's attack will increase the cool down time
* Production of point accruement can be upgraded raising the default points per turn

## Both versions have...

* Locations on the board that give an increased amount of points per turn if you have a piece in those locations
* If there are enough points for a piece to take two actions, those actions are completed by the order of selection
* A fatal attack gives the attacker bonus points (there is friendly fire)