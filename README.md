# PYTHON GAMES:  Using Pygame module to create some games
<br>

### 1.References
  1. Pygame Page: http://pygame.org
  2. documentation: http://pygame.org/docs/ref/
  3. ~~XXXXX had forgotten~~  
  
<br>

------  

<br>

### 2.What is Pygame 
  * Pygame provides Display, Sound, Image, Text, Event to create games.  
  * Pygame can make 2-D games. 
  * Pygame detects users using Keyboard, joystick, mouse to control games. 
  * Pygame provides many built-in game objects to make games.  
  
<br> 

------  

<br>

### 3.Pygame basic codes
| Code | Decription |
|:----:|:----------:|
|_1.py_| Create my game surface, game loop and drawing. |
|_2.py_| Create text, font, sound and image objects. |
|_3.py_| Gettting user keyboard and collision dection. |

<br>

------  

<br>

### 4.Code snippet
```python
pygame.init() #啟動
WINDOW_WIDTH, WINDOW_HEIGHT = 800,600
displayscreen = pygame.display.set_mode((WINDOW_WIDTH, WINDOW_HEIGHT)) #產生畫布
pygame.display.set_caption("My first pygame")
```
```python
running = True
while running:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False
```

<br>

------  

<br>

### 5.Game assets
  * **[Icon Archive](https://iconarchive.com/):** download game characters
  * **[Leshy SFmaker](https://www.leshylabs.com/apps/sfMaker/):** download game effect, and also make your own sound effect
  
  
<img src="https://github.com/CindyFu1226/Pygame_basic/blob/main/2.png" width="400" height="300" alt="2.py program screenshot"><br>
