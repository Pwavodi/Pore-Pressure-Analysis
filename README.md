# Pore-Pressure-Analysis Using Eaton's Equation

INTRODUCTION:

High pore pressures within sedimentary basins and subduction zones present a significant hazard during the drilling and
completion of wells during oil and gas exploration, geothermal energy exploration etc

Pore Pressure Analysis workflow using Eaton's Equation:

--- Steps
1. Data Cleaning and Processing
2. Estimate the Normal compaction trend line (NCT)
$$
P_{pg}=\sigma v_{g}-\left(\sigma v_{g}-P_{hg}\right)\left(\frac{\Delta t_n}{\Delta t}\right)^m 
$$

$$
\Delta t_n=\Delta t_m-\left(\Delta t_{ml}-\Delta t_m\right)\,e^{-cz}
$$
3. Estimate Lithostatic Pressure
$$
\sigma v_{g}=\frac{\left(P_{sea}+\int_0^Z\rho_b(Z)\,g\,dZ\right)-P_{sea}}{Z}\label{eq:OBG_def}=\frac{\int_0^Z\rho_b(Z)\,dZ}{Z}\,g\
$$

4. Estimate Hydrostatic Pressure
$$
P_{hg}=\frac{(P_{sea}+\rho_{w}\,g\,Z)-P_{sea}}{Z}=\rho_w\,g\\
$$

5. Etimate of Pore Pressure using Eaton's Equation

$$
P_{pg}=\sigma v_{g}-\left(\sigma v_{g}-P_{hg}\right)\left(\frac{\Delta t_n}{\Delta t}\right)^m 
$$


$$
P_f=P_{sea}+P_{pg} Z
$$


6. Estimate effective stress from classical Terzaghi's Equation

$$
σ_{v} = σ_{e} - P_{f}
$$

7. Estimate of Lithostatic Load and Pore Pressure excess ratios 
$$
\lambda^* = \frac{(P_{f} - P_{hydro})} {(P_{litho} - P_{hydro})}
$$ 

$$
P^*=P_{f} - P_{hydro}
$$


$$
\lambda = \frac{P_{f}}{P_{litho}}
$$
     
