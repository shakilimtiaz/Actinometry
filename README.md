# Actinometry of Low Density Hydrogen Plasma
Optical Emission Spectroscopy. (OES) attains a crucial stance in the measurement of ground electronic state species concentrations and temperatures of plasma. It adheres to a principle of non-perturbation as scaled with other techniques of plasma diagnostics which makes it crucial to the field.
### Formulas Involved:

> #### The emission intensity of $H-\alpha$ line is given by:

<span style="color:blue"> $$ I_{H-\alpha} = K(\nu_{H_{\alpha}}) A_{32} \nu_{H_{\alpha}} \nu_{emiss} \displaystyle \frac{ [H(n=1)] k^{H_{\alpha}}_{e} n_{e} + k_{diss} [H_{2}] n_{e} }{ [H] k_{Q H_{\alpha}/H} + [H_{2}] k_{Q H_{\alpha}/H_{2}} + k_{R} }$$ </span>

where,

$A_{ij}$ is the Einstein Coefficient (obtained from NIST database),

$k_{R} = (A_{32} + A_{31}) = 9.8 \times 10^{7} s^{-1}$,

$K(\nu_{H_{\alpha}})$ is the constant taking into account the optical device response,

$k_{Q H_{\alpha}/H}$, $k_{Q H_{\alpha}/H_{2}}$ represent the quenching rate constants of $H-\alpha$ by the $H_{2}$ molecules and the H atoms

> #### The emission intensity of $Ar$ line is given by:

<span style="color:blue"> $$ I_{Ar} = K(\nu_{Ar^{*}}) A_{44} \nu_{Ar^{*}} \nu_{emiss} \displaystyle \frac{ [Ar(3p)] k^{Ar^{*}}_{e} n_{e}}{ [H] k_{Q Ar^{*}/H} + [H_{2}] k_{Q Ar^{*}/H_{2}} + k_{R Ar^{*}} }$$ </span>

where,

$A_{44}$ is the Einstein Coefficient for spontaeneous transition,

$k_{R Ar} = A_{44}$,

$k_{Q Ar^{*}/H}$, $k_{Q Ar^{*}/H_{2}}$ represent the quenching rate constants of $Ar^{*}$ by the $H_{2}$ molecules and the H atoms

> Thus, the ratio of emission intensities result in:
<span style="color:blue"> $$ \frac{ [H (n = 1)] }{ [Ar (3p)] } = F \frac{ k^{Ar*}_{e} }{ k^{H\alpha}_{e} } Q_{T} \frac{I_{H\alpha}}{I_{Ar}}$$ </span>

> where $F$ is the optical device factor:
<span style="color:blue"> $$ F = \frac{ K( \nu_{Ar^{*}} ) \displaystyle \left( \frac{\nu_{Ar^{*}} A_{44}}{k_{R.Ar}} \right) }{ K( \nu_{H_{\alpha}} ) \displaystyle \left( \frac{\nu_{H_{\alpha}} A_{32}}{A_{32} + A_{31}} \right) } $$ </span>

here,

$ \nu_{Ar^{*}} = \displaystyle \frac{c}{\lambda_{Ar^{*}}} $;

$ \nu_{H_{\alpha}} = \displaystyle \frac{c}{\lambda_{H_{\alpha}}} $

> while $Q_{T}$ is the factor representing all quenching:
<span style="color:blue"> $$ Q_{T} = Q_{H_{2}} = \frac{ \left[ 1 + 0.132 x_{H_{2}} \sigma^{H\alpha}_{H_{2}} PT^{-\frac{1}{2}} \right] }{ \left[ 1 + 0.162 x_{H_{2}} \sigma^{Ar*}_{H_{2}} PT^{-\frac{1}{2}} \right] } $$ </span>
