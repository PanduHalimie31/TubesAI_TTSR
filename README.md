# TubesAI_TTSR
This is a major college AI assignment entirely based on the reference link [Learning Texture Transformer Network for Image Super-Resolution](https://github.com/researchmm/TTSR). However, there are slight differences in the dataset preparation and evaluation sections as I couldn't access the necessary files for those purposes.

# User Manual
The steps of usage can be followed on [GitHub](https://github.com/researchmm/TTSR) as it uses the same code. However, here it will be explained again with a bit more detail.

1. Download and install [Python](https://www.python.org/downloads/), i use 3.11
2. Install python packages `pip install opencv-python imageio`
4. Download pre-trained model provided by Original TTSR Author [Google Drive](https://drive.google.com/drive/folders/1CTm-r3hSbdYVCySuQ27GsrqXhhVOS-qh?usp=sharing)
5. Install [PyTorch, Torchvision with Cuda](https://pytorch.org/get-started/locally/). I used Cuda 12.1 with Nvidia GTX 1650 Ti
6. Clone this repo by using `git clone https://github.com/PanduHalimie31/TubesAI_TTSR.git`
7. Move the downloaded pre-trained model into the TTSR directory
8. You may want to check and change the model_path in "test.sh" in this case, i don't change anything
9. Run test using `sh test.sh`

# Notes
Inside the "bahan" folder, there are 5 tests that have been conducted along with their results. Here is a brief explanation:
- I used GitBash to run the whole project.
- The photo named "ref" serves as the reference file, while "lr" represents the low-resolution file which is 4 times smaller in size compared to "ref".
- The "ref" file used during my trials had a maximum size of 300KB, but for smooth testing purposes, the "ref" file I utilized was a maximum of 100KB in size with "lr" sized 4 times smaller.
- I tried to run the project without Cuda but i can get it run, without knowing the reason why so i had to use Cuda to keep it running.

# Test Result
![lr - low resolution](https://github.com/PanduHalimie31/TubesAI_TTSR/assets/85004246/b087952a-5409-4506-af22-44101e735ebe)

# Closing
Thank you for the original Author [GitHub](https://github.com/researchmm/TTSR) for letting me used its project to let me learn more about Image Restoration AI as im nothing but a beginner.

LinkedIn Profile:
[Pandu Halimie P](https://www.linkedin.com/in/pandu-halimie-prahatama-53818a19a/), [Naura Nafisah](https://www.linkedin.com/in/naura-nafisah-236118224/), [Ananda Ayu C](https://www.linkedin.com/in/ananda-ayu-chellsya-5813a62a7/)
