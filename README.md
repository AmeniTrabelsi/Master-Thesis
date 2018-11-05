# Master-Thesis
Master's Thesis Report at University of Louisville

### The code of Molecule Specific Normlization Algorithm is available [here](https://github.com/AmeniTrabelsi/Molecule-Specific-Normalization/) 

## Keywords:
Normalization, Robust Surface Fitting, Machine Learning, Loess Regression, Biomarker Discovery.

## Abstract:
In proteomics and metabolomics, to quantify the changes of abundance levels of biomolecules
in a biological system, multiple sample analysis steps are involved. The steps include mass spectrum
deconvolution and peak list alignment. Each analysis step introduces a certain degree of technical
variation in the abundance levels (i.e. peak areas) of those molecules. Some analysis steps introduce
technical variations that affect the peak areas of all molecules equally while others affect the peak
areas of a subset of molecules with varying degrees. To correct these technical variations, some
existing normalization methods simply scale the peak areas of all molecules detected in one sample
using a single normalization factor or fit a regression model based on different assumptions. As a
result, the local technical variations are ignored and may even be amplified in some cases.
To overcome the above limitations, we developed a molecule specific normalization algo-
rithm, called MSN, which adopts a robust surface fitting strategy to minimize the molecular profile
difference of a group of house-keeping molecules across samples. The house-keeping molecules are
those molecules whose abundance levels were not affected by the biological treatment. We also
developed an outlier detection algorithm based on Fisher Criterion to detect and remove noisy data
points from the experimental data. The applications of the MSN method on two different datasets
showed that MSN is a highly efficient normalization algorithm that yields the highest sensitivity
and accuracy compared to five existing normalization algorithms. The outlier detection algorithm's
application on the same datasets has also shown to be efficient and robust.



### The Flow chart for the complete data preprocessing:
![pipeline](https://github.com/AmeniTrabelsi/Master-Thesis/blob/master/DissertationLatex/flow_data_process.JPG)


