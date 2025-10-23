# AC Cycling Control Simulation

## Description
Simulates dynamic sequencing of air conditioner units based on runtime, inspired by a real-world building automation project using Metasys.

## Problem
Multiple AC units must respond to heating/cooling commands. For cooling, the units cycle in order of least runtime to ensure balanced wear.

## Solution
- Tracks runtime for each unit
- Sorts units dynamically for cooling commands
- Simulates heating and cooling sequences

## Skills Demonstrated
- Control logic and sequencing
- Runtime tracking algorithm
- Python programming
- Embedded/control system thinking

## Usage
Run `ac_cycling.py` with Python 3 to see the heating and cooling sequences printed to the console.
