# Face Verification Bypass

Evaluate data on baseline using Generate_Profile_Images_baseline.
Select appropriate results and evaluate on Face_Verification.




<!-- ABOUT THE PROJECT -->
## About The Project


Generating fake profile images that can be verified with your own face but look as different as possible.



<!-- GETTING STARTED -->
## Getting Started

All files can be run locally using jupyter.

<!-- USAGE EXAMPLES -->
## Usage
1. Preprocess images from your personal dataset by running Data_Preprocessing.ipynb. 
2. Set up the face verification system by running Face_Verification.ipynb. Save the generated database.pkl file for later use.
3. To test baseline use Generate_Profile_Images_baseline.ipynb. This is based on FreezeD. 
4. To test on starGAN v2 use starGAN_v2.ipynb. 
5. Evaluate selected generated images in Face_Verification.ipynb under Experiments by loading the previously downloaded database.pkl file. 
6. To experiment with a naive Freeze-D implementation for starGAN, replace the solver.py file in the core folder (after downloading the repository) with the solver.py file in this repository. 


