# orbit_propagator
Space systems homework

## Assignment

Write a program/script that does the following.

1. Fetches the most recent TLE for **FORESAIL-1 PRIME** or **ESTCUBE-1** from Celestrak NORAD:  
   <https://www.celestrak.com/NORAD/elements/cubesat.txt>
2. Saves the downloaded file to disk and reuses it on later runs (do not fetch every time; Celestrak rate-limits requests).
3. Extracts and prints these parameters from the selected satellite TLE:
   - Epoch in a readable date-time format
   - Inclination in radians
   - Right Ascension of the Ascending Node (RAAN) in radians
   - Eccentricity
   - Argument of periapsis in radians
   - Mean anomaly in radians
   - Mean motion
4. Propagates the orbit to **2026-04-24 17:00:00**.
5. Calculates and prints these propagated parameters:
   - Epoch in a readable date-time format
   - Mean anomaly in radians
   - Eccentric anomaly in radians
   - True anomaly in radians
   - Semi-major axis in km
   - Perigee distance in km
   - Orbital period in minutes

### Optional (extra)

You can also calculate and output:

- Specific angular momentum
- Cartesian coordinates and velocities
- A plot of the orbital trajectory around a sphere
