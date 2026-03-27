## Introduction 

This project is a web-playable game. I made the doodle jump game with HTML, CSS and JavaScript. This game used to rage-bait me when I was little, so I just try to build it.
I mainly focused on keeping it as simple as I could so that it was easy to play. 


## Technologies 

I kept it simple. I used :
                         - JavaScript 
                         - CSS
                         - HTML
                         - VS Code


## Features 

No special features. Definitely gonna add in the future.


## KeyBoard Shortcuts 

Playing it is really simple :
                            - Move Right	ArrowRight or D
                            - Move Left	ArrowLeft or A
                            - Restart after game over	Space


## The process 

              **Set up the canvas**  
                   - Created an HTML `<canvas>` element and defined its width and height in JavaScript.  
                   - Got the 2D drawing context to render game elements.

              **Add the player (Doodler)**  
                   - Defined Doodler’s properties: `x`, `y`, `width`, `height`.  
                   - Loaded images for facing left and right.  
                   - Drew the initial Doodler on the canvas.

              **Implement movement and controls**  
                   - Added keyboard event listeners (`keydown`) for left, right, and restart.  
                   - Made the Doodler move horizontally with arrow keys or `A`/`D`.  
                   - Handled screen wrapping so the Doodler appears on the opposite side when going off-screen.

              **Add gravity and jumping**  
                  - Set up a vertical velocity and gravity constant.  
                  - Updated Doodler’s vertical position each frame.  
                  - Implemented jump logic on collision with platforms.

              **Create platforms**  
                   - Defined platform properties: `x`, `y`, `width`, `height`.  
                   - Generated initial platforms at different heights.  
                   - Loaded platform images and drew them on the canvas.

              **Platform scrolling**  
                   - Made platforms move downward as Doodler climbs.  
                   - Removed platforms that moved off-screen and generated new ones above.

              **Collision detection**  
                   - Wrote a function to check if Doodler collides with a platform.  
                   - Triggered a jump when landing on a platform while falling.

              **Score system**  
                   - Added variables for `score` and `maxScore`.  
                   - Updated the score as Doodler moves upward.  
                   - Displayed the score on the canvas.

              **Game over and restart**  
                  - Checked if Doodler falls below the screen → game over.  
                  - Allowed restarting the game with the **Space** key.  
                  - Reset Doodler position, velocity, platforms, and score on restart.

               **Animation loop**  
                   - Used `requestAnimationFrame` for smooth gameplay.  
                   - Updated positions, checked collisions and drew everything each frame.


## What I learned 
I learned many things:
                     - How to use the HTML `<canvas>` element to render graphics in the browser  
                     - Working with the Canvas 2D context to draw images and text  
                     - Implementing a game loop using `requestAnimationFrame.`  
                     - Understanding basic game physics like gravity and velocity  
                     - Handling keyboard input for player movement  
                     - Creating collision detection between objects  
                     - Generating objects dynamically (platforms) for endless gameplay  
                     - Managing game state (score, game over, restart)  
                     - Debugging and fixing logic errors in JavaScript  
                     - Structuring a complete mini game using HTML, CSS, and JavaScript  



## Preview 

https://github.com/user-attachments/assets/0f4011b7-7a07-4652-8f99-42873460e293



