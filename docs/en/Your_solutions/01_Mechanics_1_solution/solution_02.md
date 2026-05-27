# Range Optimization

## Given

The range of a projectile is given by:

\[
R(\theta)=\frac{v_0^2\sin(2\theta)}{g}
\]

where:

- \(v_0\) is the initial velocity,
- \(g\) is the acceleration due to gravity,
- \(\theta\) is the launch angle.

We want to determine the angle that gives the maximum range.

---

# Mathematical Analysis

The expression:

\[
R(\theta)=\frac{v_0^2}{g}\sin(2\theta)
\]

contains two parts:

1. The constant:

\[
\frac{v_0^2}{g}
\]

2. The variable term:

\[
\sin(2\theta)
\]

Since:

\[
\frac{v_0^2}{g}
\]

is constant for a fixed launch speed, the range depends entirely on maximizing:

\[
\sin(2\theta)
\]

---

# Maximum Value of Sine Function

The sine function has a maximum value of:

\[
\sin(x)=1
\]

Therefore:

\[
\sin(2\theta)=1
\]

This occurs when:

\[
2\theta = 90^\circ
\]

Hence:

\[
\theta = 45^\circ
\]

---

# Verification Using Calculus

Differentiate the range function with respect to \(\theta\):

\[
R(\theta)=\frac{v_0^2}{g}\sin(2\theta)
\]

\[
\frac{dR}{d\theta}
=
\frac{v_0^2}{g}\cdot2\cos(2\theta)
\]

Set derivative equal to zero:

\[
\frac{dR}{d\theta}=0
\]

Therefore:

\[
2\cos(2\theta)=0
\]

\[
\cos(2\theta)=0
\]

This occurs when:

\[
2\theta=90^\circ
\]

Thus:

\[
\theta=45^\circ
\]

---

# Second Derivative Test

Differentiate again:

\[
\frac{d^2R}{d\theta^2}
=
-\frac{4v_0^2}{g}\sin(2\theta)
\]

Substitute:

\[
\theta=45^\circ
\]

\[
\sin(90^\circ)=1
\]

Therefore:

\[
\frac{d^2R}{d\theta^2}<0
\]

Since the second derivative is negative, the function has a maximum at:

\[
\theta=45^\circ
\]

---

# Conclusion

For a projectile launched with a fixed initial velocity and no air resistance, the maximum horizontal range occurs when the launch angle is:

\[
\boxed{45^\circ}
\]

This result follows because the sine function reaches its maximum value when:

\[
\sin(2\theta)=1
\]