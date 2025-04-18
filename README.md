## Setup

Note: after cloning the repo change the file path for [file97.iq](file97.iq) to the one where this repo is present in your machine
```file: /Users/phillo/code/assign/file97.iq``` in line number 43 of [assig.grc](assig.grc) and in line number 118 of [assig.py](assig.py)

### Install the gnuradio

#### By using brew
```bash
brew install gnuradio
```

#### By using condo

1. Install conda
```bash
mkdir -p ~/miniconda3
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm ~/miniconda3/miniconda.sh
```

2. Activate it
```bash
source ~/miniconda3/bin/activate
conda init --all
```

3. Create a new environment
```bash
conda create -n gr-env -c conda-forge gnuradio
conda activate gr-env
```

### Start gnuradio
```bash
gnuradio-companion
```

A gnuradio window should pop up.

### File Loading

1. Click on file and then open

2. Browse to the folder where the [assig.grc](assig.grc) file is present and open it.

3. Flow diagram should pop up

4. Press the run button to generate the graph
