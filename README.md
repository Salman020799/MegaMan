# MegaMan Game Clone in Python
This project is a 2D platformer game inspired by the classic MegaMan series, developed using Python and the Pygame library. It recreates essential gameplay mechanics such as player movement, jumping, shooting, enemy behavior, item collection, and level navigation within a tile-based world.

The game world is built on a 16×16 grid map system, where each tile represents terrain, obstacles, or hazards. The player can move horizontally, jump vertically, and shoot energy bullets to defeat enemies. A basic physics system is implemented to simulate gravity, jumping arcs, and collisions with terrain, spikes, and platforms.

Enemy types such as Metalls and Bladers introduce dynamic challenges: some patrol fixed areas, while others actively pursue the player. Upon defeat, enemies may drop items (health, energy, or score balls), introducing an element of randomness and resource management.

The project also incorporates game states such as running, invincibility, and game over, demonstrating the use of finite state machines in real-time gameplay. The rendering pipeline uses sprite transformations, scaling, and flipping to animate characters and enemies.

From a computational perspective, this project showcases several problem-solving techniques:
- Physics simulation: gravity, velocity, and jump mechanics.
- Collision detection: between player, enemies, bullets, and tiles.
- Event-driven programming: handling keyboard inputs and game events.
- Finite state machines: managing player states (idle, jumping, shooting, invincible).
- AI movement: enemy pathfinding and pursuit behaviors.
- Grid-based representation: level design through a tile map system.
- Probability-based resource allocation: random item drops upon enemy defeat.
<img width="1366" height="768" alt="Screenshot (264)" src="https://github.com/user-attachments/assets/4a390951-2568-4dd9-a2ea-7ab83d307081" />
<img width="1366" height="768" alt="Screenshot (265)" src="https://github.com/user-attachments/assets/14502504-8083-4d0b-839d-5a2ea5131d8a" />
<img width="1366" height="768" alt="Screenshot (266)" src="https://github.com/user-attachments/assets/f419fe70-efe1-4312-90ca-34accdcfb7d1" />
Overall, the MegaMan clone demonstrates how Python can be used not only for educational and computational problem-solving but also for creating engaging interactive entertainment systems. It blends game design principles with core computational concepts, making it both a learning tool and a fun project.

