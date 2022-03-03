# Raghavendra Reddy

### Check pip version if not available install it
python --version

### Check pip version, if not exists install pip
pip --version

### Already had a pip version so, just updated it
python -m pip install --upgrade pip

### Create a  python environment, here i have created env for the project
python -m venv C:\Users\S542272\Documents\44517\python-wordcount-beam-reddy

### Activatating python in my project
C:\Users\S542272\Documents\44517\python-wordcount-beam-reddy\Scripts\activate.ps1

### Downloading and intalling apache beam
python -m pip install apache-beam

### To run the wordcount
python -m apache_beam.examples.wordcount --input sample.txt --output reddy_output