# Thesis repository
Working repository for my thesis writing process

## Data

### Generated data:
- **ts_funs.csv & ts_funs_noise.csv (N=1000, normalized)**

| c0 | c1 | c2 | c3 | c4 | c5 | c6 | c7 | c8 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| $y_0 = 0.5$  | $y_1 = x$  | $y_2 = x^2$ | $y_3 = x^3 $ | $y_{sqrt} = \sqrt{x}$ | $y_{sin} = \sin (x/20)$ | $\sin (x/15) + 0.3 \sin (x/5) - 0.1 \sin (x/100)$ | $y_{exp} = e^x$ | $y_{log} = \log (x)$ |

- **ts_phys.csv (N=1000, normalized)**
Damped harmonic oscillator

- **ts_chaos.csv (N=10000, not normalized)**
| c0 | c1 | c2 | c3 | c4 | c5 |
| --- | --- | --- | --- | --- | --- |
| logistic | double pendulum ($x_2$) | double pendulum ($y_2$) | Lorenz$_x$ | Lorenz$_y$ | Lorenz$_z$ |
