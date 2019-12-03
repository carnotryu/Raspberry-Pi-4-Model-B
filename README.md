## Raspberry-Pi-4-Model-B (Setup for keras, librosa, etc.)

### Install OS (raspbian buster 20190710)

### Venv setup
```bash
sudo apt-get update
sudo apt-get install python3-dev python3-pip 
sudo pip3 install -U virtualenv
virtualenv --system-site-packages -p python3 {venv name}
```

### Pre-req.
```bash
sudo apt-get install llvm               ## pre-req for librosa
sudo apt-get install portaudio19-dev    ## pre-req for pyaudio
sudo apt-get install libatlas-base-dev  ## pre-req for numpy 
sudo apt-get install libhdf5-dev        ## for load_model in keras
```

### Packages (venv activated)
```bash
pip install --upgrade {name}
```
