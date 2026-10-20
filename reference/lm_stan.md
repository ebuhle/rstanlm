# Bayesian linear regression with Stan

Bayesian linear regression with Stan

## Usage

``` r
lm_stan(x, y, ...)
```

## Arguments

- x:

  Numeric vector of input values.

- y:

  Numeric vector of output values.

- ...:

  Arguments passed to
  [`rstan::sampling`](https://mc-stan.org/rstan/reference/stanmodel-method-sampling.html)
  (e.g. iter, chains).

## Value

An object of class `stanfit` returned by
[`rstan::sampling`](https://mc-stan.org/rstan/reference/stanmodel-method-sampling.html)
