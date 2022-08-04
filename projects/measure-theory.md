---
usemathjax: true
---

# Measure Theory in Geophysical Inverse Problems

### What are Inference Problems and why are they so common?
A lot of problems in physics & geophysics can be boiled down to *parameter inference* problems.
Examples include estimating the mass of ore in an orebody, the distance to a far-away galaxy, and the temperatures of arctic sea ice.
In these problems we have two things: (1) measurements, or data, and (2) a quantity that we infer from the measurements.
If the measurement is exactly what we wanted to infer, i.e. inferring temperature by direct measurement, then that's easy. 
Where it gets hard is when you want to know temperature, but only have data from, for example, a radar backscatter measurement.
This is broadly how weather forecasts work, how oil & mineral deposits are found, and how sea level rise projections are made.

### Two approaches to inference problems: data-driven and process modeling
We call these types of problems *inference problems*. 
To make these inferences, there are broadly two approaches: (1) the data-driven approach, and (2) the modeling approach.
The data-driven approach generally uses supervised learning. 
Therefore, it works best when you have a lot of historical data. 
For example, if you have lots of pairs of simultaneous temperature and radar data, then you can directly learn the relationship between the two from historical data alone.
Then, you can make new predictions of temperature by simply feeding in the radar data.
There are many great papers on this approach [CITE].
However, the data-driven approach falls apart when you apply it to data that are not represented in the historical data, or when you apply it somewhere with different processes that are not represented in the historical data.
This is why, for example, the "100-year flood" has been occurring more and more. 
The historical data used to estimate the frequency of flood events do not include the effects of a changing climate.


The modeling approach to inference problems is necessary when there is a lack of historical data. 
This problem occurs in Earth science all the time because every part of the Earth is unique.


### Bayes' Rule for Inference Problems
$$ \textrm{P}(\mathbf{m}|\mathbf{d}) = \frac{\textrm{P}(\mathbf{d}|\mathbf{m})}{\textrm{P}(\mathbf{d})} \textrm{P}(\mathbf{m})$$

### Where Bayes' Rule falls short

### Measure Theory as an alternative to Bayes
$$ \textrm{P}_\textrm{post} = \frac{\textrm{P}_\textrm{obs}(g(\mathbf{m}))}{\textrm{P}_\textrm{push}(g(\mathbf{m}))} \textrm{P}_\textrm{prior}(\mathbf{m}) $$

### Applying Measure Theory in practice

### References
