# Lunar-Lander-MATLAB
A simple game written in MATLAB using plot. This was a project to test the limits of the MATLAB plot function to see if it can replicate a simple game I made previously. The goal of the game is to use thrusters (keyboard) to slow the descent of the lander to prevent a crash.

## Usage
Open the .mlx file in MATLAB (R2025+) and run.

## Controls
- W (up arrow) - Fire bottom thruster.
- A (left arrow) - Fire right thruster.
- D (right arrow) - Fire left thruster.
- R - Reset game.
- Esc - Exit game.

This control scheme is a bit confusing at first, but essentailly, the direction you hold is the direction you will go. 

## Gameplay
having a thruster active will push the lander by applying an acceleration. If the lander collides with the ground too fast, it will turn red and prevent any further input. If the lander touches the ground with a small enough speed, it will turn green. The win/loss counter will be updated when the game detects a sucessful landing or crash respectively.

## License
This project is licensed under the MIT License — see the LICENSE file for details.
