# TubesAI_TTSR
This is a major AI assignment entirely based on the reference link [GitHub](https://github.com/researchmm/TTSR). However, there are slight differences in the dataset preparation and evaluation sections as I couldn't access the necessary files for those purposes.

# User Manual
The steps of usage can be followed on [GitHub](https://github.com/researchmm/TTSR) as it uses the same code. However, here it will be explained again with a bit more detail.

1. Download and install Python, i use 3.11.
2. Download and install GitBash. I personally use GitBash to run the project.
3. Download pre-trained model provided by Original TTSR Author [Google Drive](https://drive.google.com/drive/folders/1CTm-r3hSbdYVCySuQ27GsrqXhhVOS-qh?usp=sharing)
4. Install python packages `pip install opencv-python imageio`
5. Install PyTorch, Torchvision, Cuda here [PyTorch](https://pytorch.org/get-started/locally/). I used Cuda 12.1 with Nvida 
6. Clone this repo by using `git clone https://github.com/PanduHalimie31/TubesAI_TTSR.git`
7. Move the downloaded pre-trained model into the TTSR directory
8. You may want to check and change the model_path in test.sh. In this case, i don't change anything.
9. Run test using `sh test.sh`.

# Notes
Inside the "bahan" folder, there are 5 tests that have been conducted along with their results. Here is a brief explanation:
- The photo named "ref" serves as the reference file, while "lr" represents the low-resolution file which is 4 times smaller in size compared to "ref".
- The "ref" file used during my trials had a maximum size of 300KB, but for smooth testing purposes, the "ref" file I utilized was a maximum of 100KB in size with "lr" sized 4 times smaller.

# Closing
Thank you for the original Author [GitHub](https://github.com/researchmm/TTSR) for letting me used its project to let me learn more about Image Restoration AI as im nothing but a beginner.

LinkedIn Profile:
[Pandu Halimie P](https://www.linkedin.com/in/pandu-halimie-prahatama-53818a19a/)
