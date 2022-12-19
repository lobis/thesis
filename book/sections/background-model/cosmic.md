# Cosmic background

## Cosmic muons

Cosmic muons from {cite}`Guan`.

This is the muon flux formula from {cite}`gaisser_engel_resconi_2016`:

$$
\frac{dI_{\mu}}{dE_{\mu}}
=
\frac{0.14}{\text{GeV} \text{ cm}^2 \text{ s} \text{ sr}}
\left( \frac{E_{\mu}}{\text{GeV}} \right)^{-2.7}
\left(
\frac{1}{1 + \frac{1.1 E_{\mu} \cos{\theta}}{115 \text{ GeV}}}
+
\frac{0.054}{1 + \frac{1.1 E_{\mu} \cos{\theta}}{850 \text{ GeV}}}
\right)

$$ (Gaisser-muons-formula)

```{glue:} muons_energy_varying_theta
```

```{glue:} muons_theta_varying_energy
```


## Cosmic neutrons