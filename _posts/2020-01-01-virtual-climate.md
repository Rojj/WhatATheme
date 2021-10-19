---
title: MCTools @ Virtual Climate
layout: post
post-image: /assets/images/projects/virtual-climate-00.png
description: Virtual Climate's MCTools helps small and medium design firms deliver complex outdoor comfort analyses via a simple SketchUp interface. Access virtually unlimited resources on the cloud for CFD analysis without ever leaving SketchUp
tags:
- Computational Fluid Dynamic
- Outdoor Thermal Comfort
- Software Development
- Digital Twins
- IoT
---

# MCTools
At the early stages of design microclimate analysis is usually performed based on simple weather data, and it often ignores the effect of the local urban morphology. Typical example is the use of meteorological wind speed at 10 m near the airport as opposed to the actual local air speed. The latter is what actually counts for pedestrian comfort.
Actual comfort is rarely considered and proxies such temperature or Predicted Mean Vote are used. Pedestrian outdoor comfort depends on a combination of local air velocity, solar radiation, humidity and temperature. State-of-the-art comfort indexes such Physiological Equivalent Temperature (PET) or Universal Thermal Comfort Index (UTCI) take these dependencies into account and are more suitable to represent actual comfort conditions.

**The Universal Thermal Comfort Index**<br>
![UTCI](/assets/images/projects/virtual-climate-UTCI.png)

Furthermore, microclimate analysis are based on snapshots of the complex and dynamic reality of outdoor spaces; calculations are usually performed at a fixed moment in time and provide very little information on the overall performance of the spaces. Typical examples are radiation calculations performed at the equinox or solstice or wind analysis performed only for one or two prevailing wind directions. This is like estimating the performance of a building by using data only on the peak day.
Usually this kind of analysis requires several tools and quite a bit of post-processing of data generated in different formats.

[MCTools](https://www.virtual-climate.com) solve this problem. The analysis is set up in SketchUp and run on the cloud by using best in class tools such [OpenFOAM](https://openfoam.org/) and [Radiance](https://www.radiance-online.org/)

**MCTools SketchUp interface**<br>
![MCTools SketchUp Interface](/assets/images/projects/virtual-climate-01.png)

**Run complex Computational Fluid Dynamic from the comfort of the cloud**<br>
![CFD analysis](/assets/images/projects/virtual-climate-02.png)

**Hourly Wind Analysis (OpenFOAM CFD) around buildings imported from OpenStreetMap**<br>
<iframe width="1280" height="720" src="https://www.youtube.com/embed/jXbAPUIa5g0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>