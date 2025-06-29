# portafolio-python-reduction

In this work, we will locate the HII regions from an uncorrected image of a galaxy, using a broad R band and a narrow H-alpha band, each containing four fits images. Through this program written in python, we will create lists of all the elements used for the observation (bias, flats, and the galaxy's original image) along with their corresponding statistical data. Next, we will clean the original image of cosmic rays detected by the CCD and remove the noise produced by the detector itself (bias). We will also take into account the pixel sensitivity using the flats, the sky light that hinders the observation of the galaxy, as well as the exposure time for each band. Finally, we will remove the continuum from the H-alpha band to obtain only the H-alpha line and plot the obtained HII regions in both two and three dimensions.

## Data

The data used in this work can be downloaded in this link: https://www.dropbox.com/scl/fo/amsoy4i3lkmyorozpb81u/ABQ8Z7djP_Ks1o1xq4Qe01g?rlkey=zafi4cm9ngenpbc172yo46xqj&st=jgyagc30&dl=0

## You need to have (Requirements)

- Python 3.10

- NumPy

- Matplotlib 

- Astropy 

- Photutils

- LaCosmic 

- SciPy 

- Jupyter Notebook

Install using:

```bash
pip install -r requirements.txt
```

## Structure
```
├── reduction_250316.ipynb # Notebook 
├── requirements.txt # Requirements
└── README.md
```

## What you need to do

- Create an environment:
```
python3 -m venv envAstro
```
- Activate it:
source envAstro/bin/activate

- Install requirements inside environment
  
- Download the data

- Execute cells on jupyter lab

## Results

Clean a real image from multiple types of noise that hindered our ability to observe the H II regions of the galaxy under study and represent these regions in two and three dimensions. 
 
## Author

Miguel Ángel Susillo Ridao

Linkedin: 
