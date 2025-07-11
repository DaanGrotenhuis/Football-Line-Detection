# Football-Line-Detection

Project using football tracking data to automatically label football passes based on the dynamic positioning of players and tactical formations. Unlike traditional static models, this system detects defensive, midfield, and attacking lines (which can be extended to real-time) using clustering techniques (K-Means, GMM, ACDC), even as formations shift fluidly during gameplay.

Key Features:
- Converts raw positional XY data (5Hz) into labeled football intelligence: pass origin/destination by zone and line.
- Uses weighted clustering and a voting system across multiple algorithms to handle tactical ambiguity and improve accuracy.
- Designed with real-world match data in collaboration with Forward Football B.V.

Why It Matters
- Required to meet FIFA data standards for positional labeling.
- Enables deeper tactical insights: line-breaking passes, transition play, and player role shifts.
- Scalable for scouting, match analysis, training design, and broadcast enhancements.
- Tested and used on different levels of football (youth to first team)

The output can also be visualized, shown in this basic visualization: 

<img width="688" height="420" alt="image" src="https://github.com/user-attachments/assets/e68fa633-4e7f-41a9-981f-3df2ab8caa9d" />
<img width="312" height="155" alt="image" src="https://github.com/user-attachments/assets/77ef8e6d-bc80-4500-a531-a46e6a59016e" />

