# References

- [Machinery's handbook](https://www.worldcat.org/title/machinerys-handbook/oclc/954734887) from [Industrial Press](https://books.industrialpress.com/machineryhandbook)
- [NASA Standard 5020, Requirements for Threaded Fastening Systems in Spaceflight Hardware](https://standards.nasa.gov/standard/nasa/nasa-std-5020)
- E. F. Bruhn. (1949). Analysis And Design Of Airplane Structures. Retrieved from http://archive.org/details/in.ernet.dli.2015.166811
- Chambers, J. A. (1995). Preloaded joint analysis methodology for space flight systems. Retrieved from https://ntrs.nasa.gov/search.jsp?R=19960012183
- Hemminger, E., Posey, A., & Dube, M. (2014). Torque Tension Testing of Fasteners used for NASA Flight Hardware Applications (p. 13). Presented at the Proceedings of the 42nd Aerospace Mechanisms Symposium, NASA Goddard Space Flight Center.


# Material Selection

18-8 stainless steel is low-cost and corrosion resistant.
A-286 Alloy is comparable strength to non-stainless bolts, but at a relatively higher cost.

When a single bolt can't fail, a certified A286 alloy bolt is often called for. When there is redundancy and margin, more widely  available 18-8 is often more convenient and cost effective.

# Lubricant

Lubricants that are vacuum safe and low-outgassing (see outgassing.nasa.gov), such as Braycote 601 EF can decrease the risk of galling.

# Torque

For detailed calculations and requirements see NASA Standard 5020. NASA [Tech Memo 19960012183](19960012183.pdf) introduces preloaded joints and also has a table of suggested torque values.

The Look up fastener clamping load and recommended torque on a table like the [Spaenaur Suggested Tightening](spaenaur%20-%20Suggested%20Tightening%20Torque1%20Values%20To%20Produce%20Cor.pdf) chart, taking care to use the lubricated column if applicable.

The clamping load of the part should exceed the expected load on the joint being supported by a safety factor. e.g. a kilogram part expecting to see 30 g loads should and a minimum safety factor of three should be held with at least `1 [kg]*3*(30*9.8) m/s/s = 882 Newtons` (e.g. >198 lbs-force). 

## Torque wrenches

- torque values typically don't include the running torque and this will need to be estimated for the most accurate value.

# Inserts

 Nitronic 60 locking helical inserts are suggested for threading into aluminum. Inserts, such as locking helical inserts "helicoils", provide a locking mechanism to prevent screws from backing out, can increase strength, and the tolerable number of cycles of a joint.
