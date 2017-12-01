# Conditional Wasserstein GANs

This is an implementation of conditional GANS using the Improved Wasserstein (WGAN-GP) method.
Currently I'm trying it out on multiple datasets, though Celeba has been the main target.

### Results
These are some results generated by taking random attribute values from the Celeba test set.

| Image         | Attributes    |
|:-------------:|:-------------:|
| ![g1](https://i.imgur.com/lGnnXzq.png) | Male, Smiling  |
| ![g2](https://i.imgur.com/zfAfNI8.png) | Female, Blonde |
| ![g3](https://i.imgur.com/51rzV8s.png) | Female, Heavy Makeup |
| ![g4](https://i.imgur.com/rCYeDw2.png) | Female, Heavy Makeup, Smiling |

### Interpolation results
These results are obtained by choosing two values for z, (the same) random values for y, then
interpolating between the two z values. The images on the far left and far right sides are
the two initial values for z.


These are interpolating between two different z vectors but using the same y (same attributes).
![i1](https://i.imgur.com/Ca6nRZt.png)

![i2](https://i.imgur.com/7sxwx1a.png)

![i3](https://i.imgur.com/PaDw1RV.png)

This shows interpolation between four faces (four corners)
![i4](https://i.imgur.com/q13bJL3.png)


