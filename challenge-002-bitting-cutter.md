# Challenge 002 - Bitting Cutter / Bitting Keyhole (Get Access to the Steam Tunnels)

## Inside dormitory, last room down hallway

#### Objectives
* [x] Unlock minty's closet

#### Steps
1. Clicking in the middle of the screen provides this [png file](https://key.elfu.org/000000.png)
  - Picture of a key, transparent background
2. Stenography?
  - `stegsolver` was helpful in seeing the markings more clearly by separating the alpha channels, but this is not a "stenography challenge"
3. Solution
  - Found keys on krampus belt (the elf that keeps avoiding you in the room)
  - Used DevTools in Firefox to capture the image (go to networking tab, filter list with `krampus`). Saved as krampus_key.png.
  - Used `gimp` to crop and rotate krampus_key.png
  - Noticed six cut markings on the blank key (000000.png from step 1)
  - Several tries later, finally solved with `122520` setting on the key cutter, then upload in the closet

  #### Achievements
  `Congratulations! You have completed the Get Access To The Steam Tunnels challenge!`
