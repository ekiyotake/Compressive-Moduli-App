This MATLAB app will analyze the compressive moduli of cylindrical samples via linear modeling and/or Ogden modeling, and additionally provide failure properties.

Inputs: 
- a file containing sample names/diameters
- up to 72 sample files (from varying softwares or custom files)

Outputs: 
- plots of the data, linear fits, and/or Ogden fits of designated strain regions. 
- An exportable data table contains the compressive moduli, adjusted R^2 of the linear fit, the strain rate, sample heights, ultimate failure stress, ultimate failure strain, Ogden parameters (i.e., shear moduli, G, and nonlinearity parameter, alpha), and the R^2 of the Ogden fit. 
- The user can select to export another Excel file ('stress_strain.xlsx') containing the data for plotting the stress-strain curves, linear fits, stress-stretch curves, and Ogden fits for every sample. 
- The user can take snapshots of the app to capture the current plots displayed.

Required MATLAB Add-Ons:
- Statistics and Machine Learning Toolbox
- Curve Fitting Toolbox
