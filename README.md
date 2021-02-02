# 2SeaColor
Two-stream remote sensing model for water quality mapping: 2SeaColor (Salama and Verhoef, 2015 Remote Sensing of Environment 157, 111–122).

- 2SeaColor is a Matlab/Octave (Python IS ALSO available) code that provides analytical solution of the radiative transfer equation in the water column.
- 2SeaColor treats the direct and diffuse solar radiation separately and derives the depth profile of the downwelling attenuation coefficient   together with inherent optical properties from observed above-water remote sensing reflectance.
- The common high turbidity of inland waters is accounted for in 2SeaColor by projecting its effect on the inherent optical properties (IOPs) using the similarity transform. 

The code is provided with test data obtained from radiative transfer simulations, at 30° sun zenith, of synthesized inherent optical properties (IOPs), (Lee, 2006). More details on the IOCCG data sets can be found at http://www.ioccg.org/groups/OCAG_data.html.

Use the main_Inversion2SeaColor.m to run the 2SeaColor model. The code with the test data will produce figures 3 and 4 of Salama and Verhoef (2015, Remote Sensing of Environment 157, 111–122).


Please cite as: Salama, M.S and Verhoef, W. (2015). Two-stream remote sensing model for water quality mapping: 2SeaColor. Remote Sensing of Environment. Volume 157, February 2015, Pages 111–122.

2SeaColor was developed using MATLAB R2009b, a Python version is also avaliable. Please provide your suggestions to improve the model and the code.
