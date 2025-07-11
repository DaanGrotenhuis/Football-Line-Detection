# Football-Line-Detection

Project to automatically label football passes based on the dynamic positioning of players and tactical formations. Unlike traditional static models, this system detects defensive, midfield, and attacking lines (which can be extended to real-time) using clustering techniques (K-Means, GMM, ACDC), even as formations shift fluidly during gameplay.

Key Features:
- Converts raw positional XY data (5Hz) into labeled football intelligence: pass origin/destination by zone and line.
- Uses weighted clustering and a voting system across multiple algorithms to handle tactical ambiguity and improve accuracy.
- Designed with real-world match data in collaboration with Forward Football B.V.

Why It Matters
- Required to meet FIFA data standards for positional labeling.
- Enables deeper tactical insights: line-breaking passes, transition play, and player role shifts.
- Scalable for scouting, match analysis, training design, and broadcast enhancements.

The output can also be visualized, shown in this basic visualization 
+----------------+------------------+
|     Label      |      Value       |
+----------------+------------------+
| Starting Zone  | Defensive Zone   |
| Ending Zone    | Defensive Zone   |
| Starting Line  | Defensive Line   |
| Ending Line    | Defensive Line   |
+----------------+------------------+
<img width="966" height="591" alt="image" src="https://github.com/user-attachments/assets/aef81f89-d4dc-4d25-ad38-79b0377ca31a" />
