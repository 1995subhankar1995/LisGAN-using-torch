# LisGAN-using-torch
Implementation of "Leveraging the Invariant Side of Generative Zero-Shot Learning" paper.\
I stopped the "zsl_LisGAN using torch" code at 102 epochs, because the accuricies are almost converged for AWA2 dataset. If you choose to test it on other dataset, please change the name in "parser.dataset". "argparse" do not work in the colab, so I converted it into class and passed all values.\
The accuracy for "gzsl_LisGAN using torch" is very less for unseen class in 100 epochs, due to lack of computation resources I have not ran it after 100 epochs. If you have enough resources please feel free to run the code for nearly 2000 epochs, I am positive that it should mimic the results of the paper.\
You can take a look for the paper: https://arxiv.org/pdf/1904.04092.pdf.\
You can get the data from this website https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/zero-shot-learning/zero-shot-learning-the-good-the-bad-and-the-ugly/. Please click on "Proposed Split Version 2.0".\
Give exact root of the data, what you will download on the "parser.dataroot".
