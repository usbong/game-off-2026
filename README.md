# GitHub x ITCH.IO 

This is the GitHub repository of our entry for Game Off 2026 with the theme SHIFT.

### ITCH.IO: PROTOTYPES

#### 1) 20261102; https://masarapmabuhay.itch.io/game-off-2026-prototype1

#### 2) 20261103-20261105; https://masarapmabuhay.itch.io/game-off-2026-prototype2

20261103: P1 auto-faces opponent   

20261104: 
1) Opponent auto-faces P1 at very close-range; faces downward if too close; 
2) HP gauges for both fighters; HP deductions for P1 move from left to right, while for Opponent, it's from right to left; 

<img src="https://github.com/usbong/game-off-2026/blob/main/notes/gameOff2026HpGauge20261104.jpg" width="30%" height="30%">

20261105: 
1) Boundaries to prevent the P1 from wandering away;
2) Functional level up upon defeating the Opponent;


#### 3) 20261105-20261110; https://masarapmabuhay.itch.io/game-off-2026-prototype3

20261105: key input "J" to attack instead of P1 auto-attacking when near the Opponent

20261106-20261107: Fixed clunky controls related to how long P1 held "J", etc; simple control mechanism with choices; Coins come out upon hitting the Opponent.

20261108: Coins jump out from the Opponent and are affected by gravity. P1 or Opponent gives out the sound of squeezed bicycle horn when hit.

20261109: Mouse left-click now also does exactly what pressing "J" on the keyboard does. P2 could also make use of the "Enter" key on the numberpad to do the same thing for his character. I've added "Skel" (a "Drudge Skeleton") as one of the characters in the roster. Updating the faces, which were ruined after scaling to `96x96px` from `64x64px`, took as long as `1.5 hrs`. Meanwhile, the coin's image sprite is still undergoing testing. The marking inside is supposed to be an hourglass, only it currently looks like Spider-man's face.

20261110: Sound now comes out whenever P1 collects a coin. I've also disabled the default behavior of the arrow keys and the numpad keys, because I noticed that on itch.io, these keys also scroll the page or move out of full screen mode. I then updated the image sprites for our new character, "Einstein;" however, getting only the animation sprites for movement without the attacks or when getting hit already took me an afternoon totaling to `2hrs`.


#### 4) 20261111; https://masarapmabuhay.itch.io/game-off-2026-prototype4

20261111: The first BGM recording now plays once P1 hits the Opponent. The next two BGM recordings play upon hitting the Opponent two more times. When P1's life bar is reduced to `<=` half his total life points upon getting hit, then only the first BGM recording is played. The rest are again played following the rules stated previously. I've also added the title screen, how-to screen and the story screen, things that are commonly used in any game. Finally, I've updated Einstein's image sprite sheet, though even after another `1.5hrs`, I haven't yet finished all the necessary animation frames.

## Related link

1) https://philnits.org/

## Open Source Software License

Copyright 2026 USBONG

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0
  
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

@company: USBONG<br/>
@author: SYSON, MICHAEL B., et al.<br/>
@website address: http://www.usbong.ph<br/>
