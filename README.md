# Numerisk-Matematikk
My projects from TMA4215 - Numerical Mathematics

## Project 1
This was a solo project about underdetermined linear systems accounting for 10% of the grade in this course.

First we were asked to find the minimum norm solution using the Lagrange function, and then reformulate our initial solution using QR decomposition, comparing the two methods.
Then, using Tikhonov regularization, we found the least squares solution of a underdetermined system with a small norm. The solution we obtain from this method is a tradeoff between a minimizer of the least squares problem and a smallest norm vector. Lastly, we were asked to apply our solutions to a single-channel source separation problem, wanting to separate a combined image of a 0 and a 1, using handed out bases for the images of 0 and 1. I chose to find the minimal norm solution expanding on techniques from the first part of the project.

## Project 2
This was a group project about the Fourier transform and signal processing, accounting for 20% of the grade.

The project was separated into four parts. First, we were working on establishing the foundations for the Fourier transform by showing basic results about orthonormal systems and function norms, examining some properties about the Fourier transform.
In the second part we moved on to the discrete Fourier transform (DFT), deriving the matrix expression for and using the DFT of a function to interpolate it, creating basic functions to interpolate a function given by its DFT coefficients by orthogonal shifts of a basis function.
Then, in part three, we show that the space of Dirichlet kernel shifts satisfies the properties needed to nicely interpolate a function. We further show that we with this technique have a nice way of enhancing the resolution of a signal from calculating its DFT.
We use the techniques from part three in the final part to analyze some images, treating them as signals like before, but in 2D. First we find some qualitative results, and then build on our previous work to remove dithering artefacts from images.
