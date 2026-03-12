---
title: 'LaTeX Test: Understanding the Boltzmann Constant'
description: 'A short note on what the Boltzmann constant means, with LaTeX equations.'
tags: ['latex', 'physics', 'thermodynamics']
pubDate: 'Mar 12 2026'
---

The Boltzmann constant, written as $k_B$, links temperature to energy at the particle scale.

In SI units, it is:

$$
k_B = 1.380649 \times 10^{-23}\ \mathrm{J\,K^{-1}}
$$

A useful interpretation is that thermal energy per particle is on the order of:

$$
E \sim k_B T
$$

where $T$ is the absolute temperature in kelvin.

For example, at room temperature ($T \approx 300\,\mathrm{K}$):

$$
k_B T \approx 4.14 \times 10^{-21}\ \mathrm{J}
$$

In statistical mechanics, the same constant appears in the Boltzmann factor:

$$
P(E) \propto e^{-E/(k_B T)}
$$

This tells us that higher-energy states are exponentially less likely, with the scale set by $k_B T$.
