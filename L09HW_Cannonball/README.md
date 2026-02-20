# L09HW_Cannonball
# Cannonball Trajectory Simulator

A Streamlit web app that simulates and visualizes cannonball trajectories using projectile motion physics.

## Features

- Simulate a standard **Cannonball** trajectory
- ~not added yet~ Simulate a **Crazyball** — a cannonball with random horizontal acceleration
- Interactive controls for launch angle and initial velocity
- Altair chart displaying the trajectory

## Usage

```
python3 -m streamlit run L09HW_Cannonball/main_cli.py
or
python3 -m streamlit run main_cli.py
```

## Controls

| Control | Description |
|---|---|
| Starting angle (degrees) | Launch angle from 0° to 90° |
| Initial velocity | Choose from 15, 25, or 40 m/s |
| Simulate | Run a standard cannonball simulation |
| ~not added yet~ Crazy Simulate | Run a Crazyball simulation with random velocity changes |

## Classes

### `Cannonball`
Models a projectile using basic kinematics. Tracks x/y position and velocity components.

- `shoot(angle, velocity, user_grav, step)` — launches the ball and returns lists of x and y positions sampled at each time step until the ball returns to ground level.


## Requirements

- Python 3.x
- `streamlit`
- `altair`
- `pandas`

