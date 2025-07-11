# Football-Line-Detection
AI model that clusters football formation in the 3 essential lines (attacking, midfield, defense) based on position for football analysis

Project to automatically label football passes based on the dynamic positioning of players and tactical formations. Unlike traditional static models, this system detects defensive, midfield, and attacking lines (which can be extended to real-time) using clustering techniques (K-Means, GMM, ACDC), even as formations shift fluidly during gameplay.

Key Features:
- Converts raw positional XY data (5Hz) into labeled football intelligence: pass origin/destination by zone and line.
- Uses weighted clustering and a voting system across multiple algorithms to handle tactical ambiguity and improve accuracy.
- Designed with real-world match data in collaboration with Forward Football B.V.

Why It Matters
- Required to meet FIFA data standards for positional labeling.
- Enables deeper tactical insights: line-breaking passes, transition play, and player role shifts.
- Scalable for scouting, match analysis, training design, and broadcast enhancements.
