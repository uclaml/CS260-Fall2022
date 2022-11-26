
# Homework 6

Starter code containing the Colab notebooks can be downloaded [here]([https://www.dropbox.com/s/ltvp0cpf7k8iq2m/hw6.zip?dl=0]). Please carefully read the setup + submission instructions before getting started + when you are ready to submit respectively.

Due Dec 7th (11:59 PM).

## Setup

This homework will be done in [Google Collaboratory](https://colab.research.google.com/). Google Colaboratory is basically Jupyter notebook on Google Drive. It runs entirely in the cloud and comes preinstalled with many useful packages (PyTorch, Tensorflow, etc). Colab also has free access to hardware accelerators like GPUs and TPUs which will be useful for future homeworks / your projects. 

To use Colab, you must have a Google account with an associated Google Drive. Assuming you have both, you can connect Colab to your Drive with the following steps:

1. Click the wheel in the top right corner and select `Settings`.
2. Click on the `Manage Apps` tab.
3. At the top, select `Connect more apps` which should bring up a `GSuite Marketplace` window.
4. Search for `Colab` then click `Add`.

We provide you with a download link to a zip file containing Colab notebooks and Python starter code. You can upload the folder to Drive, open the notebooks in Colab and work on them, then save your progress back to Drive. Please watch [this tutorial video](https://www.youtube.com/watch?v=DsGd2e9JNH4&feature=emb_imp_woyt&ab_channel=MooJinKim) which demonstrates the recommended workflow.

Note that resources aren’t guaranteed in Colab, so if you are idle for a certain amount of time or your total connection time exceeds the maximum allowed time, the Colab VM will disconnect. This means any unsaved progress will be lost. So please frequently save your code whilst working on this homework. 

If you wish to use a GPU, click `Runtime -> Change runtime type -> Hardware Accelerator -> GPU` (You won't need this for this assignment, but it can come in handy later / for projects).

Although we highly recommend working in Colab, you are free to work on your local hardware if you choose. Instructions to help you do so can be found [here](https://cs231n.github.io/setup-instructions/#working-locally-on-your-machine).

Once you have completed "ConvolutionalNetworks" notebooks except `collect_submission.ipynb`, proceed to the submission instructions.

## Question : Image Captioning with Vanilla RNNs 

The notebook `RNN_Captioning.ipynb` will walk you through the implementation of vanilla recurrent neural networks and apply them to image captioning on COCO.

## Submitting Your Work

**Make sure that the submitted notebooks have been run and the cell outputs are visible before following these steps.**

Once you have completed all the notebooks and filled out the necessary code, do the following to submit your work:

1. Open `collect_submission.ipynb` in Colab and execute the notebook cells.

This notebook/script will:

- Generate a zip file of your code (`.py` and `.ipynb`) called `a6_code_submission.zip`.
- Convert all notebooks into a single PDF file called `a6_inline_submission.pdf`.
- If your submission for this step was successful, you should see the following display message:

`### Done! Please submit a6_code_submission.zip and a4_inline_submission.pdf to Gradescope. ###`

2. Submit the PDF to Gradescope and the zip file to Bruinlearn.

Remember to download `a6_code_submission.zip` and `a6_inline_submission.pdf` locally before submitting.

## Acknowledgment
The material in this homework is adapted from Prof. Fei-Fei Li's offering of [CS 231n](http://cs231n.stanford.edu/).

