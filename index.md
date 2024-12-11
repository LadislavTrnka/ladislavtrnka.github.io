---
layout: default
---

## Research interests

*   Numerical methods for differential equations (spectral collocation method, finite element method)
*   Nonlinear dynamical systems and bifurcation analysis
*   Elastic solids, Newtonian and non-Newtonian fluids, viscoelastic fluids (numerical simulations, thermodynamics)
*   Reduced-order models and machine learning for fluid mechanics

{% include images.html url="fig/flow.png" description="Multiple steady states of viscoelastic fluid in a sudden expansion channel" %}

## Education

* **09/2022-present**&emsp;Master's study programme, [Mathematical Modelling in Physics and Technology](https://mod.karlin.mff.cuni.cz/study/modelling-mathematics/), Charles University, Faculty of&nbsp;Mathematics and Physics
    * Planned graduation: 06/2025
    * Thesis title: _Bifurcation analysis of viscoelastic flows using deflation method_
    * Supervisor: [Doc. Mgr. Vít Průša, Ph.D.](https://www.karlin.mff.cuni.cz/~prusv/)

* **09/2019-06/2022**&emsp;Bachelor degree with honours, [Mathematical Modelling](https://mod.karlin.mff.cuni.cz/study/mathematical-modelling-bc/), Charles University, Faculty of Mathematics and Physics
    * Thesis title: [_Spectral collocation methods in solid mechanics_](https://dspace.cuni.cz/bitstream/handle/20.500.11956/173829/130332530.pdf?sequence=1&isAllowed=y)
    * Supervisor: [Doc. Mgr. Vít Průša, Ph.D.](https://www.karlin.mff.cuni.cz/~prusv/)

{% include images.html url="fig/spectral_col_met.png" description="Deflection of a semi-infinite elastic solid by
a surface load" %}

## Publications

*  Vít Průša and **Ladislav Trnka**. Mechanical response of elastic materials with density dependent Young modulus. _Applications in Engineering Science_, 2023. [doi:10.1016/j.apples.2023.100126](https://doi.org/10.1016/j.apples.2023.100126)

{% include images.html url="fig/cylinder_n_1.png" description="Extension of a right circular cylinder, prediction by the standard linearised elasticity model (red), prediction by the model with density dependent Young modulus (yellow)" %}

## Preprints

* Jan Blechta, Vít Průša, Ladislav Trnka, and Karel Tůma. Fast construction of the discrete green operator for a second order ordinary differential equation, 2024. URL [https://arxiv.org/abs/2412.06242](https://arxiv.org/abs/2412.06242)

## Research experience

*  **02/2023-12/2024**&emsp;Team researcher, [_Mathematical analysis of partial differential equations describing far-from-equilibrium open systems in continuum thermodynamics_](https://www.karlin.mff.cuni.cz/~mbul8060/expro2020/info.html), Czech Science Foundation, EXPRO 20-11027X, Principal investigator [Doc. RNDr. Miroslav Bulíček, Ph.D.](https://www.karlin.mff.cuni.cz/~mbul8060/)

* **09-11/2022**&emsp;Principal investigator, _Elastic bodies with density dependent material moduli_, [Student Faculty Grants](https://www.mff.cuni.cz/en/students/bc-mgr/sfg), Charles University, Faculty of Mathematics and Physics 

## Recent talks, posters

* **2024**&emsp;[Modelling, PDE Analysis and Computational Mathematics in Materials Science](https://www.karlin.mff.cuni.cz/~prusv/ncmm/conference/mpde/info.html), Faculty of Mathematics and Physics, Charles University, September 22-27, Prague, Czech Republic,  [poster](conferences/poster_mpde2024.pdf)

* **2024**&emsp;[High Performance Computing in Science and Engineering Conference](https://hpcse.it4i.cz/HPCSE24/), IT4Innovations National Supercomputing Center, VSB (Technical University of Ostrava), May 20-23, Karolinka, Czech Republic,  [poster](conferences/poster_hpcse2024.pdf)

* **2024**&emsp;[EMS School, Mathematical Aspects of Fluid Flows](https://ems-maff.cuni.cz/), EMS (European Mathematical Society), Faculty of Mathematics and Physics, Charles University, May 12-17, Kácov, Czech Republic,  [slides](conferences/kacov2024.pdf)

<br>
<br>
Last Updated: <span id="time"></span>
<script>
var date = new Date(document.lastModified);
var dd = date.getDate(); 
var yyyy = date.getFullYear(); 
const months = ["January","February","March","April", "May", "June","July", "August","September", "October", "November", "December"];
var currentMonthName = months[date.getMonth()];
var datetime = currentMonthName + " " + dd + ", " + yyyy; 
document.getElementById("time").innerHTML = datetime;
</script>
