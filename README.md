# Actinometry of Low Density Hydrogen Plasma
* Optical Emission Spectroscopy *. (OES) attains a crucial stance in the measurement of ground electronic state species concentrations and temperatures of plasma. It adheres to a principle of non-perturbation as scaled with other techniques of plasma diagnostics which makes it crucial to the field.

The following repository contains a baseline code for computation of data following optical emission spectroscopy for low density hydrogen plasmas using data assumptions for spectral lines of Hydrogen in $H-\alpha$ at $656.46$ nm and Argon used as actinometer at $811.50$ nm. It follows in multiple data points for whom due references have been added wherever required.

However, measurements made by OES have to be interpreted carefully. As a matter of fact, OES provides measurements of species in electronic excited states which participates only in a minor proportion to the plasma or plasma/surface chemistry and which are at a concentration levels of less than $10^{-4}$ with respect to species in the electronic ground state.

The actinometric method proceeds with trace amounts of the actinometer particles added to the gas under study. For the actinometer, a chemically inert element whose characteristics (emission spectrum, electron excitation cross sections, coefficients of collisional and radiative quenching of excited states, etc.) are well known is used.

For density measurements of hydrogen atoms via actinometry, an admixture of argon atoms is usually used.

### Formulas Involved:

> #### The emission intensity of $H-\alpha$ line is given by:

$$ I_{H-\alpha} = K(\nu_{H_{\alpha}}) A_{32} \nu_{H_{\alpha}} \nu_{emiss} \displaystyle \frac{ [H(n=1)] k^{H_{\alpha}}_{e} n_{e} + k_{diss} [H_{2}] n_{e} }{ [H] k_{Q H_{\alpha}/H} + [H_{2}] k_{Q H_{\alpha}/H_{2}} + k_{R} }$$

where,

$A_{ij}$ is the Einstein Coefficient (obtained from NIST database),

$k_{R} = (A_{32} + A_{31}) = 9.8 \times 10^{7} s^{-1}$,

$K(\nu_{H_{\alpha}})$ is the constant taking into account the optical device response,

$k_{Q H_{\alpha}/H}$, $k_{Q H_{\alpha}/H_{2}}$ represent the quenching rate constants of $H-\alpha$ by the $H_{2}$ molecules and the H atoms

> #### The emission intensity of $Ar$ line is given by:

$$ I_{Ar} = K(\nu_{Ar}) A_{44} \nu_{Ar} \nu_{emiss} \displaystyle \frac{ [Ar(3p)] k^{Ar}_{e} n_{e}}{ [H] k_{Q Ar/H} + [H_{2}] k_{Q Ar/H_{2}} + k_{R Ar} }$$

where,

$A_{44}$ is the Einstein Coefficient for spontaeneous transition,

$k_{R Ar} = A_{44}$,

$k_{Q Ar/H}$ , $k_{Q Ar/H_{2}}$ represent the quenching rate constants of $Ar$ by the $H_{2}$ molecules and the H atoms

> Thus, the ratio of emission intensities result in:

$$ \frac{ [H (n = 1)] }{ [Ar (3p)] } = F \frac{ k^{Ar}_{e} }{ k^{H\alpha}_{e} } Q_{T} \frac{I_{H\alpha}}{I_{Ar}}$$

> where $F$ is the optical device factor:

$$ F = \frac{ K( \nu_{Ar} ) \displaystyle \left( \frac{\nu_{Ar} A_{44}}{k_{R.Ar}} \right) }{ K( \nu_{H_{\alpha}} ) \displaystyle \left( \frac{\nu_{H_{\alpha}} A_{32}}{A_{32} + A_{31}} \right) } $$

here,

$\nu_{Ar} = \displaystyle \frac{c}{\lambda_{Ar}}$;

$\nu_{H_{\alpha}} = \displaystyle \frac{c}{\lambda_{H_{\alpha}}}$

> while $Q_{T}$ is the factor representing all quenching:

$$ Q_{T} = Q_{H_{2}} = \frac{ \left( 1 + 0.132 x_{H_{2}} \sigma_{H_{2}}^{H\alpha} PT^{-\frac{1}{2}} \right) } {\left( 1 + 0.162 x_{H_{2}} \sigma_{H_{2}}^{Ar} PT^{-\frac{1}{2}} \right) } $$

## References
1. <div class="csl-entry">Gicquel, A., Chenevier, M., Hassouni, K., Tserepi, A., &#38; Dubus, M. (1998). Validation of actinometry for estimating relative hydrogen atom densities and electron energy evolution in plasma assisted diamond deposition reactors. <i>Journal of Applied Physics</i>, <i>83</i>(12), 7504–7521. https://doi.org/10.1063/1.367514</div>
2. <div class="csl-entry">Rousseau, A., Granier, A., Gousset, G., &#38; Leprince, P. (1994). Microwave discharge in H2: Influence of h-atom density on the power balance. <i>Journal of Physics D: Applied Physics</i>, <i>27</i>(7), 1412–1422. https://doi.org/10.1088/0022-3727/27/7/012</div>
3. <div class="csl-entry">Dyatko, N. A., Kashko, D. A., Pal’, A. F., Serov, A. O., Suetin, N. v., &#38; Filippov, A. v. (1998). Actinometric method for measuring hydrogen-atom density in a glow discharge plasma. <i>Plasma Physics Reports</i>, <i>24</i>(12), 1041–1050.</div>
4. <div class="csl-entry">Dyatko, N. A., Kashko, D. A., Pal’, A. F., Serov, A. O., Suetin, N. v., &#38; Filippov, A. v. (1998). Actinometric method for measuring hydrogen-atom density in a glow discharge plasma. <i>Plasma Physics Reports</i>, <i>24</i>(12), 1041–1050.</div>
