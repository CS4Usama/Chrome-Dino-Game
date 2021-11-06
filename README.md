## Chrome Dino Game (T-Rex Dinosaur Game)
### JavaScript Codes – [Dino Game Hacks](https://youtu.be/ATuFgKvgzJ0 "YouTube Video") <br><br>

- #### Hurdles don't affect Dino (Immortal):
_Change Logic => Do Nothing When Game is Over._ <br>
Runner.instance_.gameOver = () => {} <br>
Runner.prototype.gameOver = () => {} &nbsp; &nbsp; OR &nbsp; &nbsp; Runner.prototype.gameOver = function() {}
- #### Increase Dino and Score's Speed:
Runner.instance_.setSpeed(x)
- #### Higher Jump:
Runner.instance_.tRex.setJumpVelocity(10)
- #### Gravity Cheat:
Runner.instance_.tRex.config.GRAVITY = 0.0001
- #### Intro Cheat:
Runner.instance_.playingIntro = true <br>
Runner.instance_.playingIntro = false
- #### Height Cheat:
Runner.instance_.tRex.config.HEIGHT = 100000000000000000000000000000000000000000000000000

</br><br>

>💻 &ldquo;PROGRAMMING is Just a Game of L0GIC.&rdquo; 🧐 <br>If You can Create a L0GIC, then You can Convert Your Imaginations into Reality.
