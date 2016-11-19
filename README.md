2D-Procedural-Planets
============

A 2D procedural planet texture generator.

Language: C++

Libraries: SFML, libnoise

---

Generates a 2D height map via **Perlin Noise**,
and colours the terrain based on height thresholds.

It then resamples the 2D height map using a spherical
projection to generate the planets final texture. Finally,
it renders a seperate *mountain texture* behind the planet
texture which is generated by sampling the height map along the
circumference of the spherical projection.

https://www.youtube.com/watch?v=Gt8ZMe2_iQs

![example](https://github.com/orglofch/2D-Produceral-Planets/blob/master/images/example.png)
