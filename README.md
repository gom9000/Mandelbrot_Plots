# Mandelbrot Plots
Archive of plots of Mandelbrot Set and Julia Sets generated with [Mandelbrot](https://github.com/gom9000/Mandelbrot/) software.

![overview](preview.png)

The mandelbrot set is the set of complex numbers $z$ for which the series $z_{n+1} = z_{n}^{2} + c$ does not diverge to infinity. When $c$ is held constant at a specific value, the set corresponds to a Julia set.


## [Mandelbrot set plots ad previews](mandelbrot.md)


## [Julia sets plots and previews](julia.md)


## File naming format

*set_x_y_x0_y0_thik_c_iterations_colourset.png*

- *set* : julia or mandelbrot set
- *x*, *y* : number of horizontal and vertical pixels of the image
- *x0*, *y0* : coordinates of the center of the image
- *thik* : (step) distance between two near points on the complex plane
- *c* : the value of the complex constant *c* on the formula
- *colourset* :
    - 0 - highlights the edges and florescences. Set and "outher" are black, tonescale is proportional to iterations
    - 1 - highlights the set. Set is black and "outher" is white, grayscale is proportional to iterations
    - 2 - highlights the veils and bands. Set and "outher" are black, tonescale is proportional to iterations


## About
Author : Alessandro Fraschetti (mail: [gos95@gommagomma.net](mailto:gos95@gommagomma.net))


