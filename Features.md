### Must-have (core project)

| #   | Feature                    |                                                                                                    |
| --- | -------------------------- | -------------------------------------------------------------------------------------------------- |
| F1  | **Airspace map**           | Shows a protected zone (e.g., an airport) with a radar circle and a no-fly boundary                |
| F2  | **Drone simulation**       | Drones spawn, move and follow different behaviours: straight, loitering or heading toward the zone |
| F3  | **Sensor model**           | A simulated radar "sees" drones only within range and adds small noise, the way real sensors do    |
| F4  | **Scenario generator**     | Builds each training round: how many drones, which types, and the difficulty level                 |
| F5  | **AI threat classifier**   | An ML model labels each drone _Friendly / Suspicious / Hostile_ and gives a confidence %           |
| F6  | **Trainee response panel** | Buttons for _Monitor / Warn / Jam / Alert_, with a countdown timer                                 |
| F7  | **Scoring engine**         | Scores correct decisions, reaction time and false alarms                                           |
| F8  | **Debrief dashboard**      | Shows a performance summary, charts and improvement tips after each session                        |