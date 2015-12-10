# <div align="center">ATUS Analysis</div>

The ATUS Analysis notebook used data from the [U.S. Department of Labor's 2014 survey](www.bls.gov/tus/) on Americans' time use for research and analysis in the attempt to find useful and interesting correlations.

## <div align="center">Instructions</div>

* The ATUS Analysis notebook can be viewed on GitHub or downloaded to the users computer.
* Before the user can view the ATUS Analysis notebook on their computer, the user must first clone the `atus-analysis` repo onto their computer. The user must have Python 3 installed.
* To properly run the notebook, the contents of requirements.txt must be installed.
  * After navigating to the folder containing `atus_analysis.ipynb`, enter `pip install -r requirements.txt` on the command-line to download the contents of requirements.txt.
* The user can then enter `ipython notebook atus_analysis.ipynb` on the command-line to open the ATUS Analysis notebook.
* The data used was downloaded from bls.gov and can be easily downloaded to the user's computer using the download_data script.
  * The ATUS Analysis notebook was designed to use data saved in the `data` folder. After navigating to the folder containing `download_data.sh`, the user will need to create a folder titled `data`.
  * After navigating to the newly created `data` folder, the user must enter `bash ./download_data.sh` on the command-line to run the download_data script and download the pertinent data.
* The ATUS user guide can be found [here](www.bls.gov/tus/atususersguide.pdf).
