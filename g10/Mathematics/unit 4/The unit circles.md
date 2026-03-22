## The unit circles

### Activity 4.3

Based on the right-angled triangle labeled A and B as shown in Figure 4.15.
a. Find cosine of angle A
b. Compute sine of angle A

```
      B
     /|
    / | 3
   /  |
  5   |
 /    |
A-----C
   4

Figure 4.15
```

The unit circle is in the xy-plane. It is a circle with a radius of 1 and centered at the origin.

Now let us draw a right-angled triangle with the same acute angles, a hypotenuse of 1 unit long. We find that the side opposite to angle A is $\frac{3}{5} = 0.6$ long and the side adjacent to angle A is $\frac{4}{5} = 0.8$ long.

```
      B
     /|
    / | 0.6
   /  |
  1   |
 /    |
A-----C
   0.8

Figure 4.16
```

$\cos A = \frac{0.8}{1} = 0.8$ and $\sin A = \frac{0.6}{1} = 0.6$. Thus, the length of the side adjacent is numerically equal to the cosine of the angle, and the length of the side opposite is numerically equal to the sine of the angle. Because of this result, we can use a circle whose center is the origin and whose radius is 1 unit long to help us visualize the values of the cosine and sine of the central angle.

*   Plot the points (1, 0), (0, 1), (-1, 0), and (0, -1) on the xy-coordinate system.

Let P (a, b) be any point on the circle with angle $AOP = x$ radian, i.e., length of arc AP = x as shown in Figure 4.17.

We define $\cos x = \frac{a}{1} = a$ and $\sin x = \frac{b}{1} = b$.
So, the point $(a, b) = (\cos x, \sin x)$.

Since $\triangle OMP$ is a right-angled triangle, we have $(OM)^2 + (MP)^2 = (OP)^2$ or $a^2 + b^2 = 1$.
Thus, for any point on the unit circle, we have $a^2 + b^2 = 1$, or $\cos^2 x + \sin^2 x = 1$.

```
y
B(0,1)
|      P(a,b)
|     /|
|    / | b
|   /  |
C(-1,0)---O--a--M--A(1,0)---x
|   \  |
|    \ |
|     \|
D(0,-1) Q(a,-b)

Figure 4.17
```

Since one complete revolution subtends an angle of $2\pi$ radian at the center of the circle,
$m(\angle AOB) = \frac{\pi}{2}$, $m(\angle AOC) = \pi$ and $m(\angle AOD) = \frac{3\pi}{2}$.

All angles which are integral multiples of $\frac{\pi}{2}$ are called **quadrantal angles**. The coordinates of the points A, B, C and D are respectively (1,0), (0, 1), $(-1,0)$ and (0, -1).

Therefore, for quadrantal angles, we have
$\cos 0 = 1$
$\sin 0 = 0$
$\cos \frac{\pi}{2} = 0$
$\sin \frac{\pi}{2} = 1$
$\cos \frac{3\pi}{2} = 0$
$\sin \frac{3\pi}{2} = -1$
$\cos 2\pi = 1$
$\sin 2\pi = 0$

Now, if we take one complete revolution from the point P, we again come back to the same point P. Thus, we also observe that if x increases (or decreases) by any integral multiple of $2\pi$, the values of sine and cosine functions do not change.

Thus,
$\sin (2n\pi + x) = \sin x, n \in \mathbb{Z}$
$\cos (2n\pi + x) = \cos x, n \in \mathbb{Z}$.

Furthermore, $\sin x = 0$, if $x = 0, \pm \pi, \pm 2\pi, \pm 3\pi, \dots$ i.e., when $x$ is an integral multiple of $\pi$.
$\cos x = 0$, if $x = \pm \frac{\pi}{2}, \pm \frac{3\pi}{2}, \pm \frac{5\pi}{2}, \dots$ i.e., when $x$ is an odd integral multiple of $\frac{\pi}{2}$.

Thus
$\sin x = 0$, implies $x = n\pi$, where $n$ is any integer,
$\cos x = 0$, implies $x = (2n + 1)\frac{\pi}{2}$, where $n$ is any integer.

In grade 9, we discussed the values of the trigonometric ratios for $0^\circ, 30^\circ, 45^\circ, 60^\circ$ and $90^\circ$.
The values of trigonometric functions for these angles are the same as those of trigonometric ratios in Table 4.2.

#### Table 4.2

| degree | $0^\circ$ | $30^\circ$ | $45^\circ$ | $60^\circ$ | $90^\circ$ | $180^\circ$ | $270^\circ$ | $360^\circ$ |
|--------|-----------|------------|------------|------------|------------|-------------|-------------|-------------|
| radian | $0$ | $\frac{\pi}{6}$ | $\frac{\pi}{4}$ | $\frac{\pi}{3}$ | $\frac{\pi}{2}$ | $\pi$ | $\frac{3\pi}{2}$ | $2\pi$ |
| $\sin x$ | $0$ | $\frac{1}{2}$ | $\frac{1}{\sqrt{2}}$ | $\frac{\sqrt{3}}{2}$ | $1$ | $0$ | $-1$ | $0$ |
| $\cos x$ | $1$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{2}}$ | $\frac{1}{2}$ | $0$ | $-1$ | $0$ | $1$ |
| $\tan x$ | $0$ | $\frac{1}{\sqrt{3}}$ | $1$ | $\sqrt{3}$ | Not Defined | $0$ | Not Defined | $0$ |

### Exercise 4.6

1.  Using the unit circle, find the values of the sine, cosine and tangent functions of the following quadrantal angles:
    a. $0^\circ$
    b. $450^\circ$
    c. $540^\circ$
    d. $630^\circ$
2.  Fill in the blank with numbers.

| degree | $-360^\circ$ | $-450^\circ$ | $-270^\circ$ | $-180^\circ$ | $-90^\circ$ | $90^\circ$ | $180^\circ$ | $720^\circ$ |
|--------|--------------|--------------|--------------|--------------|-------------|------------|-------------|-------------|
| $\sin x$ |              |              |              |              |             |            |             |             |
| $\cos x$ |              |              |              |              |             |            |             |             |
| $\tan x$ |              |              |              |              |             |            |             |             |

## Sign of trigonometric functions

Let $P(a, b)$ be a point on the unit circle with center at the origin such that $m(\angle AOP) = x$. If $m(\angle AOQ) = -x$, the coordinate of the point $Q(a, -b)$ (see Figure 4.18).
Therefore, $\cos(-x) = \cos x$ and $\sin(-x) = -\sin x$.

Since for every point $P(a, b)$ on the unit circle where $-1 \le a \le 1$ and $-1 \le b \le 1$, we have $-1 \le \cos x \le 1$ and $-1 \le \sin x \le 1$, for all $x$.

```
y
B(0,1)
|      P(a,b)
|     /|
|    / | b
|   /  |
C(-1,0)---O--a--M--A(1,0)---x
|   \  |
|    \ |
|     \|
D(0,-1) Q(a,-b)

Figure 4.18
```

We have learnt that in the first quadrant ($0 < x < \frac{\pi}{2}$), $a$ and $b$ are both positive; in the second quadrant ($\frac{\pi}{2} < x < \pi$), $a$ is negative and $b$ positive; in the third quadrant ($\pi < x < \frac{3\pi}{2}$), $a$ and $b$ are both negative and in the fourth quadrant ($\frac{3\pi}{2} < x < 2\pi$), $a$ is positive and $b$ is negative.

Therefore, $\sin x$ is positive for $0 < x < \pi$ and negative for $\pi < x < 2\pi$. Similarly, $\cos x$ is positive for $0 < x < \frac{\pi}{2}$, and negative for $\frac{\pi}{2} < x < \frac{3\pi}{2}$ and also positive for $\frac{3\pi}{2} < x < 2\pi$. Likewise, we can find the signs of other trigonometric functions in different quadrants.

In fact, we have the following table.

#### Table 4.3: Quadrants

| $y=$ | I | II | III | IV |
|------|---|----|-----|----|
| $\sin x$ | + | + | - | - |
| $\cos x$ | + | - | - | + |
| $\tan x$ | + | - | + | - |

```
y
II (-x,y) | I (x,y)
----------+----------
III (-x,-y)| IV (x,-y)

Figure 4.19 (Signs of coordinates in quadrants)
```

#### Example 1

Find the quadrant where angle $x$ makes $\sin x > 0$ and $\cos x < 0$.

**Solution:**
Here, $\sin x > 0$ in the first and second quadrants, and $\cos x < 0$ in the second and third quadrants. Thus, when $\sin x > 0$ and $\cos x < 0$ are both satisfied, $x$ is the angle of the second quadrant.

### Exercise 4.7

1.  Find the quadrant where angle $x$ is located for the following conditions.
    a. $\sin x < 0$ and $\cos x > 0$
    b. $\sin x > 0$ and $\tan x < 0$
    c. $\cos x > 0$ and $\tan x < 0$
2.  Fill in the blank with numbers.

| Degree | $0^\circ$ | $120^\circ$ | $135^\circ$ | $150^\circ$ | $210^\circ$ | $240^\circ$ | $330^\circ$ |
|--------|-----------|-------------|-------------|-------------|-------------|-------------|-------------|
| Radian | $0$ | $\frac{2\pi}{3}$ | $\frac{3\pi}{4}$ | $\frac{5\pi}{6}$ | $\frac{7\pi}{6}$ | $\frac{4\pi}{3}$ | $\frac{11\pi}{6}$ |
| $\sin x$ |           |             |             |             |             |             |             |
| $\cos x$ |           |             |             |             |             |             |             |
| $\tan x$ |           |             |             |             |             |             |             |

## Reciprocal trigonometric functions

### Note

We can define other trigonometric functions in terms of sine and cosine:
It is convenient to have a name for the reciprocal of the sine, cosine, and tangent of a given angle $\theta$. We call these reciprocal functions the secant (sec), cosecant (csc), and cotangent (cot) and define them as follows:
$$ \csc\theta = \frac{1}{\sin\theta} $$
$$ \sec\theta = \frac{1}{\cos\theta} $$
$$ \cot\theta = \frac{1}{\tan\theta} $$

#### Example 1

Evaluate $\sec30^\circ$.

**Solution:**
We know $\sec30^\circ$ is the reciprocal of $\cos30^\circ$. Therefore, we have
$\cos30^\circ = \frac{\sqrt{3}}{2}$.
So, $\sec30^\circ = \frac{1}{\cos30^\circ} = \frac{1}{\sqrt{3}/2} = \frac{2}{\sqrt{3}}$.

#### Example 2

Evaluate $\sec60^\circ + \csc30^\circ$.

**Solution:**
Since $\cos60^\circ = \frac{1}{2}$ and $\sec60^\circ$ is the reciprocal of $\cos60^\circ$, we obtain
$\sec60^\circ = \frac{1}{\cos60^\circ} = \frac{1}{1/2} = 2$.
Since $\sin30^\circ = \frac{1}{2}$ and $\csc30^\circ$ is the reciprocal of $\sin30^\circ$, we have
$\csc30^\circ = \frac{1}{\sin30^\circ} = \frac{1}{1/2} = 2$.
Thus, $\sec60^\circ + \csc30^\circ = 2 + 2 = 4$.

### Exercise 4.8

1.  Evaluate the following
    a. $\sec 45^\circ$
    b. $\sec \left(\frac{2\pi}{3}\right)$
    c. $\sec \left(-\frac{\pi}{6}\right)$
    d. $\csc 30^\circ$
    e. $\csc \left(-\frac{3\pi}{4}\right)$
    f. $\csc(-300^\circ)$
    g. $\cot 60^\circ$
    h. $\cot \left(\frac{5\pi}{6}\right)$
    i. $\cot \left(-\frac{5\pi}{4}\right)$
2.  Evaluate the following trigonometric expressions.
    a) $\sec \left(\frac{10\pi}{3}\right) + \csc \left(-\frac{7\pi}{2}\right)$
    b) $\sec330^\circ + \cot480^\circ$
