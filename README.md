# Reduced-Protocol-Scheme-Files

These scheme files contain the MRI acquisition settings used to obtain the MRI data. The pathway for these files need to be defined in the MATLAB code containing the VERDICT model and the deep learning models. This code could not be shared due to permission and therefore can be requested from Dr. Matteo Figini/Dr. Marco Palombo.

To further explain the contents of each acquisition text file, the original protocol scheme file is NV and has 154 lines (volumes).
The first 41 lines correspond to the 10 shells of VERDICT. The remaining lines correspond to the 2 Shells of NODDI.
We subsampled these shells to generate shortened acquisition protocols. And then we used these protocols to train deep learning models
to make VERDICT estimates when provided MRI data.
