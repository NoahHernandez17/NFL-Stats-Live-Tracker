# NFL-Stats-Live-Tracker
Live pro football player stats (QB/RB/WR/TE) - Using Python and Tableau dashboard.
Live pro football player stats (QB/RB/WR/TE) - streamed from ESPN box scores into a Tableau-ready CSV. Run the Python writer during games; connect Tableau to data/player_stats.csv for a real-time dashboard.

Features

Regular/Postseason only (ESPN JSON APIs)

Position-filtered leaders: QB, RB, WR, TE

Stable CSV schema for Tableau (no broken fields)

Atomic writes to avoid partial-file reads

Configurable refresh interval (default 15–60s)
