# Projectile Motion

## Given

Initial velocity:

\[
v_0 = 100 \text{ m/s}
\]

Launch angle:

\[
\theta = 37^\circ
\]

Acceleration due to gravity:

\[
g = 9.81 \text{ m/s}^2
\]

Assume no air resistance.

---

# Resolving the Initial Velocity

The initial velocity is divided into horizontal and vertical components.

Horizontal component:

\[
v_{0x} = v_0 \cos\theta
\]

Vertical component:

\[
v_{0y} = v_0 \sin\theta
\]

Substituting values:

\[
v_{0x} = 100\cos(37^\circ)
\]

\[
v_{0y} = 100\sin(37^\circ)
\]

Using:

\[
\cos(37^\circ)\approx0.799
\]

\[
\sin(37^\circ)\approx0.602
\]

Therefore:

\[
v_{0x}\approx79.9\text{ m/s}
\]

\[
v_{0y}\approx60.2\text{ m/s}
\]

---

# Differential Equations of Motion

## Horizontal Motion

There is no horizontal acceleration.

\[
a_x = 0
\]

Therefore:

\[
\frac{d^2x}{dt^2}=0
\]

Integrating once:

\[
\frac{dx}{dt}=v_x=v_{0x}
\]

Integrating again:

\[
x(t)=v_{0x}t
\]

Substituting values:

\[
x(t)=79.9t
\]

---

## Vertical Motion

Gravity acts downward.

\[
a_y=-g
\]

Therefore:

\[
\frac{d^2y}{dt^2}=-g
\]

Integrating once:

\[
\frac{dy}{dt}=v_y=v_{0y}-gt
\]

Integrating again:

\[
y(t)=v_{0y}t-\frac12gt^2
\]

Substituting values:

\[
y(t)=60.2t-4.905t^2
\]

---

# Time of Flight

The projectile returns to the ground when:

\[
y=0
\]

Therefore:

\[
0=60.2t-4.905t^2
\]

Factorising:

\[
t(60.2-4.905t)=0
\]

Hence:

\[
t=0
\]

or

\[
t=\frac{60.2}{4.905}
\]

Therefore the total time of flight is:

\[
t\approx12.27\text{ s}
\]

---

# Maximum Height

At maximum height:

\[
v_y=0
\]

Using:

\[
v_y=v_{0y}-gt
\]

\[
0=60.2-9.81t
\]

\[
t=\frac{60.2}{9.81}
\]

\[
t\approx6.14\text{ s}
\]

Substitute into the vertical displacement equation:

\[
y=60.2(6.14)-4.905(6.14)^2
\]

\[
y\approx184.7\text{ m}
\]

---

# Range

The horizontal range is:

\[
R=v_{0x}t
\]

Substitute values:

\[
R=79.9\times12.27
\]

\[
R\approx980.4\text{ m}
\]

---

# Final Answers

### Differential Equations

Horizontal:

\[
\frac{d^2x}{dt^2}=0
\]

Vertical:

\[
\frac{d^2y}{dt^2}=-g
\]

---

### Time of Flight

\[
12.27\text{ s}
\]

---

### Maximum Height

\[
184.7\text{ m}
\]

---

### Range

\[
980.4\text{ m}
\]
