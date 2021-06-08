<img src="https://images.unsplash.com/photo-1481627834876-b7833e8f5570?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=841&q=80" width="800" height="400">

## Description
This repository contains a Jupyter Notebook that parses Zoom's self-generated audio transcripts, and outputs a .txt and .docx file of the transcript which combines each speaker's adjacent spoken words. By default, Zoom breaks each person's speech up every set amount of time. This results in pages of transcript for a few sentences of actual transcribed text. This notebook file searches for all .txt files in a given directory, and combines adjacent transcribed speech from the same speaker. 

## Disclaimer
By using the files contained in this directory, you agree not to use them for monetary gain.
Please give credit if you decide to use it 😃!

## Required Software and Packages
To run the .ipynb, you need to have Jupyter Notebook and Python 3.xx installed. I recommend using [Anaconda](https://www.anaconda.com/products/individual#Downloads) for this, as it will simplify the installation process. 

In whatever distribution you choose to use, the following packages are required:
* pandas for data management & manipulation
* pathlib for file and directory interactions
* docx for exporting word docs (.docx)
* tqdm for progress bar for main loop
* ipyfilechooser for browsing to file path (same for below two)

Running the notebook chunk by chunk, the process should explain itself.
