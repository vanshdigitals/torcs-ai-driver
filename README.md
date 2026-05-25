# TORCS AI Driver — IBM SkillsBuild May Challenge

## Problem
How can rule-based AI control logic be tuned to drive a car 
autonomously around a racing track without going off-track?

## Approach
Modified the baseline Python AI driver in TORCS simulator. 
Tuned parameters: TARGET_SPEED, BRAKE_THRESHOLD, STEER_GAIN 
to balance speed and stability.

## IBM AI Technology Used
IBM SkillsBuild Learning Lab — TORCS autonomous AI driver framework

## Results
- High speed (200 km/h) caused wall collisions
- Balanced config (speed 100, brake threshold 0.6) gave stable laps
- Key insight: speed alone doesn't improve lap time — braking matters

## Files
- `gym_torcs/torcs_jm_par.py` — modified AI driver
- `RESULTS.md` — experiment log
