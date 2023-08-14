# Modified
## What is Different
* I have change from the whisper large-v2 model from openai to faster-whisper large-v1 model.
NOTE: The reason for large-v1 instead of v2 is due to error from the model. I am too lazy to find the problem. It would freeze the entire program on random audio file and crash the program.
* Benefits: It is faster and more efficient.

# Original Message:

# OZEN toolkit, AI powered audio dataset helper.

OZEN is a small tool to help you process audio files to a LJ format.

Given a folder of files or a single audio file, it will extract the speech, transcribe using Whisper and save in the LJ format (wavs in wavs folder, train and valid txts).

## INSTALLATION

```sh
Accept the license terms on https://huggingface.co/pyannote/segmentation 
Install Anaconda or setup your own environment and install requirements
git clone https://github.com/devilismyfriend/ozen-toolkit
run Set Up Ozen.bat
```

## USAGE


Drag a folder or a file on the Drag_Here.bat to process it.
FOLDER DOESN'T WORK CORRECTLY YET.

The first time you'll be prompted to provide an HuggingFace token, once you do a config file will be created where you can specifiy models to use, the validation/training data desired split and more.

Alternatively you can use ozen.py in cli.

