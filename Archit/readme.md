# Archit's Training Data
## Overview
- **Levels Played:** Episode 1, Maps 1 through 5 (E1M1 - E1M5)
- **Difficulty:** Hard (Skill 4)
- **Data Formats:** Includes both `.csv` (raw feature/action logs) and `.lmp` (visual demo replays for debugging).
**How I played to help train the bot:**
When recording this data, I tried to keep the AI in mind and play in a way that gives it good examples to learn from:
- **Different routes (E1M1):** Since we are focusing on E1M1, I did 3 separate runs of it. I made sure to take a slightly different path to the exit each time so the bot doesn't just memorize one single route.
- **Getting unstuck:** I intentionally walked really close to the walls and then smoothly steered away. Hopefully, this teaches the bot how to correct itself if it gets snagged on a corner.
- **Mixed combat:** I tried to mix up how I fight. In one run I ran up close to the monsters with the shotgun, and in another run, I tried to shoot them from further away. 
- **Smooth movement:** I made a point to keep my keyboard and turning inputs as smooth as possible. I figured erratic, jerky movements would just make the training data noisy.
