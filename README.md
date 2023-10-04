# Amplitude Modulation of Audio Signals
This program performs an amplitude modulation on a signal to acheive AM radio frequencies for transmission. The demonstration walks through the process and theory and then performs an example on an audio snippet of Morgan Freedman.

## Theory
Let the carrier signal be a sinusoid with amplitude $A$ and carrier frequency $f_c$:
$$c(t) = A \sin(2 \pi f_c t)$$

Let the message signal be $m(t)$.

The output signal is $y(t)$ is defined as:
$$y(t) = \left(1 + \frac{m(t)}{A}\right) c(t)$$

Let's demonstrate AM with an example sinusoid message signal with with amplitude $A_m$ and message frequency $f_m$:
$$m(t) = A_m \cos(2 \pi f_m t)$$