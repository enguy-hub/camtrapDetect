# CamtrapDetect

This Cameratrap Image Classifier can classify the following three classes "**Capreolus_Capreolus**", "**Human**", and "**Sus_scrofa**" 

<!-- GETTING STARTED -->
## Getting Started

To get a local version of this project up and running, please follow these simple steps.

## Prerequisites

Download & install Miniconda3

```sh
https://docs.conda.io/en/latest/miniconda.html
```

Create Miniconda environment with Python 3.6

```sh
conda create --name ENVIRONMENT_NAME python=3.6
```

Useful Miniconda 'cheatsheat'

```sh
https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf
```

## Usage example

**Step 1**: Clone this project

* via HTTPS
```sh
git clone https://github.com/hiennguyentum/CamtrapDetect.git
```

* via SSH
```sh
git clone git@github.com/hiennguyentum/CamtrapDetect.git
```

**Step 2**: Activate your newly created Conda environment - type this in command prompt

* For Windows
```sh
activate ENVIRONMENT_NAME
```

* For Linux
```sh
source activate ENVIRONMENT_NAME
```

**Step 3**: Install requirements (Do this inside the newly cloned resporitory - path/to/CameratrapDetect/)

```sh
pip install -r requirements.txt
```

**Step 4**: Test run with 'Detect' folder by running and follow the instruction prompt from the below python script 

```sh
python detect.py
```

**Step 5**: Try to classify your own images by putting all of your images into one folder and then copy that folder into 'path/to/CamtrapDetect/' => Then run the same script as the step above

## Release History 

* 0.0.1
    * Work in progress

## Meta

Hien Nguyen – hien.nguyen@tum.de

## License
Distributed under the MIT License. See `LICENSE.txt` for more information.