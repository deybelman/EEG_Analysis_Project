# Alpha-Band Entropy Suppression Tracks Cortical State Transitions During High Arousal
## EEG Data Analysis Project

This EEG data analysis project was developed by **Daniel Eybelman** (Applied Mathematics, '29) and **Pearl Werbach** (Neuroscience, '28) for an iGEM undergraduate computational biology symposium at UC Berkeley. The completed poster can be found in this repository.

## Setup

### Installing Dependencies

Before running the analysis notebook, install the necessary packages using the requirements file:

```bash
pip install -r requirements.txt
```

### Data Files

**Note:** Data files are not included in this repository due to licensing reasons. 

To run the analysis notebook, you must place the ASCERTAIN dataset files in the `/data` directory before running the notebook. The expected directory structure should be:

```
data/
├── Arousal.csv
├── Data_Quality_Evaluation.csv
├── Valence.csv
├── Dt_SelfReports.mat
├── Personality_Details.xls - Results.csv
└── EEGData/
    ├── Movie_P01/
    │   ├── EEG_Clip1.mat
    │   ├── EEG_Clip2.mat
    │   └── ...
    ├── Movie_P02/
    └── ...
```

## Usage

Once the data files are in place and dependencies are installed, you can run the analysis notebook `analysis final.ipynb` to perform the EEG data analysis.

