# streamlit_euros_2024

View web app here: https://appeuros2024.streamlit.app

This interactive dashboard visualizes shot locations for the Euro 2024 tournament using Streamlit and mplsoccer. You can filter by **team** and **player** to explore where shots were taken, their outcomes, and their xG values.

## Features

- Select team and player to filter shots
- Bubble size reflects expected goals (`xG`)
- Goals shown in green, other shots in white
- Half-pitch view using StatsBomb layout (via mplsoccer)

## 🛠️ Built With

- Streamlit
- mplsoccer
- Pandas

## Dataset

The `euros_2024_shot_map.csv` file includes:
- `team`: Team name
- `player`: Player name
- `location`: Shot coordinates (x, y) as JSON
- `shot_outcome`: Goal, Missed, etc.
- `shot_statsbomb_xg`: Expected goal metric
- `type`: Filter to only 'Shot' rows


## How to Run

1. Clone the repository  
   `git clone https://github.com/yourusername/euro2024-shot-map.git`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Run the Streamlit app  
   `streamlit run streamlit.py`

> Make sure the `euros_2024_shot_map.csv` file is in the same directory.

# Acknowlegement

The dataset used for this analysis project was provided by Statsbomb:

![SB - Icon Lockup - Colour positive](https://github.com/user-attachments/assets/489c613c-9e9f-492c-84c8-ac0c8d804263)
