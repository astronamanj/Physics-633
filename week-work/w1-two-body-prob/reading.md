1. What are the constants of motion for two-bodies in orbit around each other?
    - The two body problem has 4 constants of motion - the energy integral C and the three components of the angular momentum integral, h.
    - These can be expressed in different forms such as the orbital elements, or quantities such as the eccentricity vector.
2. What is meant by the term "mean motion"?
    - Mean motion (n) is a constant in two-body problem that refers to the "average angular velocity," i.e., average radians traversed per unit time during the orbit. Note the angular velocity of the secondary body itself is not constant but over every complete orbit 2 pi radians are covered in T (time period) time.
3. Sketch an elliptical orbit and label it
    - Figure 2.5 in the chapter
4. What is the difference between mean anomaly, true anomaly, and eccentric anomaly?
    - The true anomaly (f) is the actual physical angle that describes the orbiting body's position relative to the periapsis, as seen from the central body (which is at the focus). 
    - Mean anamoly (M) is a non-physical term, i.e. no direct geometric interpretation, defined with units of time. It represents where a fictitious body would be if it were moving in a perfect circular orbit at a constant speed, with the same orbital period as the actual elliptical orbit. It increases linearly with time, which makes it easy to calculate how much time has passed since the body last passed periapsis.
    - The eccentric anomaly is a geometric angle used as a mathematical convenience to relate the true anomaly and the mean anomaly.
    - In a perfect circular orbit (e=0), all three anomalies are equal (M=E=f). 
5. What is Kepler's equation?
    - Kepler's equation (2.52) defines a relationship between the mean and ecccentric anomalies. 
    - Since the eccentric anomaly (E) uniquely defines orbital radius (r) and true anomaly (f), we can use this relationship to find r and f at any time t over the period.
6. If you want to set up an orbit with semi-major axis a and eccentrity e, how do you choose the initial location and velocity?
    - If we know the eccentricity and the semi-major axis of the orbit, we can usethe true anomaly to calculate the orbital radius and velocity of the body.
    - See Equations 2.20 and 2.34. 
7. Explain why, even though the Moon is tidally-locked, it appears to wobble (librate) to an observer on Earth. 
    - A consequence of the guiding centre approximation (which I dont fully understand) is that the line joining the orbiting mass to the empty focus must rotate at the same rate as the mean motion of the orbiting mass.
    - A synchronously rotating satellite, like the Moon, has a spin period equal to its average orbital period. 
    - While the rotation of the Moon is constant, it's position relative to the central body is not. if we apply Kepler's second law to this system, we realise that the Moon spins faster when it is closer to Earth (at perigee) and slower when it is farther away (at apogee).
    - Hence,at perigee we effectively peek around the Moon's eastern limb, and at the apogee, we then peek around its western limb.
    - This apparent side-to-side wobble allows us to see slightly more than 50% of the Moon's surface over time.
8. Underneath each of eqs (2.157) and (2.162), the text gives a brief physical explanation. Explain how the physical explanation gives rise to the equation in each case.
    - We can do dimensional analysis here.
    - I is the angle of inclination. The rate of change in I has units of rate. The normal torque gives the magnitude and direction of the force acting on the system. The factor of 1/h is a scaling factor to the toruqe, and a measure of sensitivity to the effect of the torque. Systems with high angular momentum would be less sensitive to perturbations. This factor also balances out the units. 
    - Omega is the angular displacement. Same as above but the sinI factor is needed to make the geometry work, such that only normal the components of the external torque affect the rate of change of omega.  