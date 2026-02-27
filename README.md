# RAWS_2026_TWIN
Data processing of TWIN array at Gauribidanur Radio Observatory (RRI)<br>

The .ipynb file processes the data from Two-Element Interferometer (TWIN) and performs baseline estimation<br>

TWIN:<br>
Location: Gauribidanur Radio Observatory<br>
Latitude: 13.60° N; Longitude: 77.44° E<br>
Baseline: 8.5m<br>
Operating Frequency: 180 - 350 MHz<br>


Follow the instructions for running the program


```terminal
git clone https://github.com/gnpaneendra/RAWS_2026_TWIN.git
```

```terminal
cd RAWS_2026_TWIN
```
Download the data file from: https://drive.google.com/file/d/1oygiJbyg1axjsBY8ufRK9LeMYPOccx8L/view?usp=sharing
```terminal
unzip 2025_10_21.zip -d 2025_10_21 # Unzips data data file
```
```terminal
sudo apt update
```
```terminal
python3 --version # Output= 3.12.2
```
```terminal
sudo apt install python3.12-venv # Give the python-venv version according to your python version
```
```terminal
python3 -m venv venv_twin # create a python virtual environment, venv_twin is the name of the environment
```
```terminal
source venv_twin/bin/activate # activate virtual environment
```
```terminal
python3 -m pip install numpy pandas matplotlib datetime tqdm notebook
```
```terminal
python3 -m notebook
```

Disclaimer: There are few lines of code which run on linux, but they can be commented out and it will not affect the data processing


Contact details: paneendra.res@gmail.com
