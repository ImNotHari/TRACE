# TRACE
This project, developed for the NASA Space Apps Hackathon at Mar Athanasius College of Engineering (MACE), Kothamangalam, aims to revolutionize how we predict and manage satellite decay in Low Earth Orbit (LEO).
Our tool estimates the lifetime and re-entry time of satellites using physics-based orbital models, empirical atmospheric data, and space-weather inputs — without relying on TLE data.

What It Does

1. Simulates orbital decay from 120–450 km altitude.
2. Allows customisation by satellite mass, area, and drag coefficient.
3. Provides clear lifetime estimates and decay visualisation.

Why It Matters

LEO is becoming increasingly crowded. Understanding how long satellites stay in orbit helps prevent space debris, improve mission design, and promote sustainable space operations.
This project empowers researchers and students to model orbital lifetimes more accurately, inspiring innovation in space sustainability.

The Prototype 
The prototype is an HTML file that uses JavaScript to implement the logic as specified within the plan. A major limitation with this implementation is the approximation done during calculation; as such, after a set height, the drag force becomes too negligible to calculate meaningful differences along the gradient above 470 km altitude.

