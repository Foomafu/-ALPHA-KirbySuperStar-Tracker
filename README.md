# -ALPHA-KirbySuperStar-Tracker
A tracker for the Kirby Super Star Randomizer

I made this during a fit of hyperfixation where I decided to learn how to make an emotracker pack on a whim.
Does not currently have implemented logic.

I will probably not maintain this tracker, but if you would like to, feel free.

-------------------------------------------------------------------------------------------------------------------------------------

Release Notes:

--V 0.0.2--

- Added treasureacquired objects overlaying the lower-right corner of every item in the Great Cave Offensive item grid. The intention
  is for this to be used to track the actual checks in The Great Cave Offensive subgames. E.g. when you collect the first treasure the
  game will tell you "Collected Gold Medal!", while you actually get a randomized check. You can use the treasureacquired object to
  track that you got the gold medal check, so if you miss one you don't have to guess and check every single treasure to find which.

  The actual treasure items in the grid are for when you actually receive that item from a random check. The dream is to eventually 
  give every Great Cave Offensive treasure a hidden "value" that matches their real in-game value, and when you toggle on that item
  in the tracker it adds that value to a visible "G Counter" that tracks your money for you. This is so you don't have to quit 
  whatever game you're currently in to see how much money you have.

- Removed Loop functionality of Great Cave Offensive Treasure items. With the addition of the above treasureacquired objects, I thought
  it would be prudent to attempt to minimize trouble from mis-clicks turning on/off items or checks that you haven't actually acquired
  yet. To "un-get" a treasure or treasureacquired, the item must be right-clicked.
