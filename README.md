# DeepNude Command Line Interface With No Watermark 

[![Python 3.5](https://img.shields.io/badge/python-3.5-blue.svg)](https://www.python.org/downloads/release/python-350/)
[![Torch 1.1](https://img.shields.io/badge/torch-1.1-blue.svg)](https://shields.io/)
[![DeepNude 2.0](https://img.shields.io/badge/deepnude-2.0-blue.svg)](https://shields.io/)

## Last Update: 16/07/2019

## This project is based in the official DeepNude python source-code

## Description

Create NSFW, Nude images from common images, using Aritificial Inteligence Pix2pix Algorithm using you CUDA GPU or only your CPU. Compatible with Windows, Mac and Linux.

## Benefits

- Process images fast from Unix/Mac Terminal or Windows Cmd.
- Outputs with no Watermark.
- Interface Modifications for Easy to Use.
- Free to use and distribute.

## Requirements

### You need to install the following modules to make sure that everything works correctly

- Python 3.5 or higher
- numpy
- Pillow
- setuptools
- six
- pytorch 
- torchvision
- wheel

## Follow the tutorial at README.MD file in checkpoints folder to download the checkpoint files from Torrent Protocol.

After cloning this repository, you need to download the checkpoint files from the torrent file in the "checkpoints" folder. This is required for DeepNudeCLI to work correctly.

## First Use

For first use, after make sure that you have all needed modules installed, and Checkpoint files located in "checkpoints" folder, execute:

```bash
git clone https://github.com/Yuagilvy/DeepNudeCLI.git
cd DeepNudeCLI
pip install -r requirements.txt
python nude.py -i input.jpg
```
The output will be saved as "output.jpg"

## Usage

```
usage: nude.py [-h] -i INPUT [-o OUTPUT] [-g]

DeepNude App CLI Version with no Watermark.

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        Input image to process.
  -o OUTPUT, --output OUTPUT
                        Output path to save result.
  -g, --use-gpu         Enable using CUDA gpu to speed up the process.
```

## Bugs

Some images may be distorted due to their size, different from the graphical version, this version can not crop the input images then, you can crop manually the images in a image editor.

## Notes

Please, before opening any issue, check if you enviroment meet all requirements.

## Tips

### if you use windows and anaconda, and have difficulty installing pytorch, perform the following commands:

```bash
conda install -c peterjc123 pytorch 
conda install -c pytorch torchvision 
```

