# SwiftStats

Statistics for Swift

This package is a fork of [r0fls/swiftstats](https://github.com/r0fls/swiftstats) simply restructured in so that it can be installed as a Swift Package via [Swift Package Manager](https://www.swift.org/package-manager)

For full documentation see the [original README](https://github.com/r0fls/swiftstats/README.md) and [source docs](http://r0fls.github.io/swiftstats/).

## The following distributions are included:

* Normal
* Log-normal
* Bernoulli
* Laplace
* Poisson
* Uniform
* Geometric
* Exponential
* Binomial


## And each distribution has these methods:

* pmf or pdf
* cdf
* quantile
* random (takes an optional int and returns an array of that length, or otherwise a single value)
* Common Functions
* median
* mean
* variance
* standard deviation
* erf-1 (implemented as erfinv, whereas erf is implemented as part of Foundation)
* least squares regression; lsr ([[Double]]) -> [Double, Double]
* kernel density estimation (KDE) using a Gaussian kernel and automatic bandwidth selection via Silverman's rule-of-thumb
