# Path Intersection

## Given

Alice's position:

\[
A(t)=(2+t,\;8-3t)
\]

Bob's position:

\[
B(t)=(2t-1,\;2t+2)
\]

We want to determine whether their paths intersect and whether they collide at the same time.

---

# Step 1 — Equate Coordinates

For a collision to occur, both the \(x\)-coordinates and \(y\)-coordinates must be equal at the same time.

Therefore:

\[
2+t = 2t-1
\]

and

\[
8-3t = 2t+2
\]

---

# Step 2 — Solve the \(x\)-coordinate equation

\[
2+t=2t-1
\]

Move terms:

\[
2+1=2t-t
\]

\[
3=t
\]

---

# Step 3 — Solve the \(y\)-coordinate equation

\[
8-3t=2t+2
\]

Move terms:

\[
8-2=2t+3t
\]

\[
6=5t
\]

\[
t=\frac65
\]

---

# Step 4 — Compare the Times

From the \(x\)-equation:

\[
t=3
\]

From the \(y\)-equation:

\[
t=\frac65
\]

Since the values of \(t\) are different, there is no single time at which both coordinates are equal simultaneously.

Therefore, Alice and Bob do not collide.

---

# Step 5 — Minimum Distance Between Them

The distance between two points is:

\[
d(t)=\sqrt{(x_A-x_B)^2+(y_A-y_B)^2}
\]

Compute coordinate differences:

\[
x_A-x_B=(2+t)-(2t-1)
\]

\[
x_A-x_B=3-t
\]

For the vertical coordinates:

\[
y_A-y_B=(8-3t)-(2t+2)
\]

\[
y_A-y_B=6-5t
\]

Therefore:

\[
d(t)=\sqrt{(3-t)^2+(6-5t)^2}
\]

To simplify minimization, minimize:

\[
d^2(t)=(3-t)^2+(6-5t)^2
\]

Expand:

\[
d^2(t)=9-6t+t^2+36-60t+25t^2
\]

\[
d^2(t)=26t^2-66t+45
\]

---

# Step 6 — Find the Minimum Distance

Differentiate:

\[
\frac{d}{dt}(d^2(t))=52t-66
\]

Set equal to zero:

\[
52t-66=0
\]

\[
52t=66
\]

\[
t=\frac{66}{52}
\]

\[
t=\frac{33}{26}
\]

\[
t\approx1.27
\]

---

# Step 7 — Calculate the Minimum Distance

Substitute into:

\[
d^2(t)=26t^2-66t+45
\]

Using:

\[
t=\frac{33}{26}
\]

gives:

\[
d^2_{\min}\approx3.12
\]

Therefore:

\[
d_{\min}\approx1.77
\]

---

# Final Answers

The paths do not intersect at the same time, so Alice and Bob do not collide.

The minimum distance between them is:

\[
\boxed{1.77}
\]

and it occurs at:

\[
\boxed{t\approx1.27}
\]