# TORCS Lab Results



## Parameters Changed


### Change 1

- Parameter: target\_speed

- Original value: 160

- New value: 200

- Observation: Car moved faster (Top Speed 203 km/h) but hit walls more frequently. Laptime invalidated due to wall collision.



### Change 2

- Parameter: target\_speed

- New value: 100

- Parameter: BRAKE\_THRESHOLD

- New value: 0.6

- Observation: Car braked earlier before corners. Less wall collisions. More stable driving.



## What surprised me

Increasing speed alone does not improve lap time. The car needs balanced braking and speed to stay on track.



\## What I would try next

Adjust STEER\_GAIN to improve cornering while maintaining higher speed.

