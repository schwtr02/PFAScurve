# PFAScurve
This repository outlines the procedure for estimating PFAS concentrations from suspect and non-target high resolution mass spectrometry data.

PFAScurve.Rmd is an R Markdown file with the code for generating a weighted least squares regression (i.e. weighted linear regression) from the Excel file "Calibration PFAS Curve.xlsx". The Excel file contains the LCMS calibration data from 50 PFAS analytes used to generate the "PFAS curve". The PFAS curve can be used to estimate concentrations for PFAS which have no authentic standard, sometimes called "suspects" or "nontargets". 
