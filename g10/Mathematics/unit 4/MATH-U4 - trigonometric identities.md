## 4.3 Trigonometric Identities and Equations

<iframe width="560" height="315" src="https://www.youtube.com/embed/sU2pyMR8GZ4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

By considering a right-angled triangle, the trigonometric identities or equations are formed using trigonometry ratios for all the angles. Using trigonometry identities, we can express each trigonometric ratio in terms of other trigonometric ratios. If any of the trigonometry ratio value is known to us, then we can find the values of other trigonometric ratios. We can also solve trigonometric identities, using these identities as well.

### Trigonometric Identities

There are basically three trigonometric identities, which we learn in this topic. They are:
1.  $\cos^2 \theta + \sin^2 \theta = 1$
2.  $1 + \tan^2 \theta = \sec^2 \theta$
3.  $1 + \cot^2 \theta = \csc^2 \theta$

### Proof of Trigonometric Identities

Here, we will prove the above trigonometric identities. Take an example of a right-angled triangle $\triangle ABC$ as shown in Figure 4.33.

In a right-angled triangle, by the Pythagoras Theorem, we know
$(\text{Perpendicular side length})^2 + (\text{Base length})^2 = (\text{Hypotenuse length})^2$
Therefore, in $\triangle ABC$, we have;
$(AB)^2 + (BC)^2 = (AC)^2$ ...(1)

```
      A
     /|
    / | Perpendicular Side
   /  |
  /   | Hypotenuse
 /θ   |
B-----C
  Adjacent Side

Figure 4.33
```

Dividing equation (1) by $(AC)^2$ we get,
$\frac{(AB)^2}{(AC)^2} + \frac{(BC)^2}{(AC)^2} = \frac{(AC)^2}{(AC)^2}$
$\left(\frac{AB}{AC}\right)^2 + \left(\frac{BC}{AC}\right)^2 = 1$ (by rule of exponent)
$(\sin\theta)^2 + (\cos\theta)^2 = 1$ (Since $\sin\theta = \frac{AB}{AC}$ and $\cos\theta = \frac{BC}{AC}$)
$\sin^2\theta + \cos^2\theta = 1$ ...(2)

For all angles equation (2) is satisfied.

#### Example 1

$x$ is the angle of the third quadrant. When $\sin x = -\frac{3}{5}$, find the value of $\cos x$.

**Solution:**
$\sin^2 x + \cos^2 x = 1$ and $\cos^2 x = 1 - \sin^2 x = 1 - \left(-\frac{3}{5}\right)^2 = 1 - \frac{9}{25} = \frac{16}{25}$.
But $x$ is the angle of the third quadrant, so $\cos x < 0$.
Thus $\cos x = -\sqrt{\frac{16}{25}} = -\frac{4}{5}$.

### Exercise 4.16

1.  a. If $x$ is the angle in the second quadrant and $\cos x = -\frac{\sqrt{5}}{3}$, find the value of $\sin x$.
    b. If $x$ is the angle in the fourth quadrant and $\sin x = -\frac{1}{3}$, find the value of $\cos x$.

Again, when we divide equation (1) by $(AB)^2$, we get
$\frac{(AB)^2}{(AB)^2} + \frac{(BC)^2}{(AB)^2} = \frac{(AC)^2}{(AB)^2}$
$1 + \left(\frac{BC}{AB}\right)^2 = \left(\frac{AC}{AB}\right)^2$ (By rule of exponent)
$1 + (\cot\theta)^2 = (\csc\theta)^2$ (Since $\cot\theta = \frac{BC}{AB}$ and $\csc\theta = \frac{AC}{AB}$)
$1 + \cot^2\theta = \csc^2\theta$ ...(3)
Therefore, it proves that for all values of $\theta$, equation (3) is satisfied.

Let's see what we get if we divide equation (1) by $(BC)^2$, we get
$\frac{(AB)^2}{(BC)^2} + 1 = \frac{(AC)^2}{(BC)^2}$
$\left(\frac{AB}{BC}\right)^2 + 1 = \left(\frac{AC}{BC}\right)^2$ (by rule of exponent)
$(\tan\theta)^2 + 1 = (\sec\theta)^2$ (Since $\tan\theta = \frac{AB}{BC}$ and $\sec\theta = \frac{AC}{BC}$)
$1 + \tan^2\theta = \sec^2\theta$ ...(4)

#### Example 2

$x$ is the angle of the fourth quadrant. When $\tan x = -2$, find the values of $\sec x$ and $\cos x$.

**Solution:**
$\sec^2 x = 1 + \tan^2 x = 1 + (-2)^2 = 5$
$x$ is the angle of the fourth quadrant and $\sec x = \frac{1}{\cos x}$.
In the fourth quadrant $\cos x > 0$, so $\sec x > 0$.
Therefore $\sec x = \sqrt{5}$ and $\cos x = \frac{1}{\sec x} = \frac{1}{\sqrt{5}}$.

### Exercise 4.17

Answer the following questions.
a. $x$ is the angle of the third quadrant. If $\tan x = 3$, find the values of $\sec x$ and $\cos x$.
b. $x$ is the angle of the second quadrant. If $\tan x = 3$, find the values of $\sec x$ and $\cos x$.