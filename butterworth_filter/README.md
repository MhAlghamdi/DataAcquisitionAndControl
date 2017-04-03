This VI updates the position and velocity of a particle by calculating the Lennard Jones acceleration. Porsche button wraps the particle it goes out of the box [0, L] and updates the position. Inputs: 
xo = old position,
x2 = pther position,
pr = repulsive power,
pa = attractive power,
A = acceleration amplitude,
vo = old velocity,
b = drag coefficient,
dt = time step,
a = acceleration,
L = system size.
Outputs:
xn = xo + vo*dt,
vn = vo +(a - b*vo)*dt.
