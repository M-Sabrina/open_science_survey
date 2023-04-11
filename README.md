# Open Science Survey

Open Science is a term that is increasingly more used and applied in research practices. Open Science practices are also increasingly required by research funders.
In 2022, the first Open Science Team of the Faculty of Applied Sciences at Delft University of Technology was established. The team conducted a series of surveys and meetings, aiming to examine which types of support would be the most useful for improving Open Science practises within the faculties' individual departments. The conclusions drawn from this effort were summarized and can be found in the following publicly available repository on Zenodo:

https://zenodo.org/record/7641319

To learn about what employees of the [Bionanoscience Department](https://www.tudelft.nl/en/faculty-of-applied-sciences/about-faculty/departments/bionanoscience/) think about Open Science, the team set up an online survey on the topic, which was made available from 03/11/2022 to 02/12/2022.
The questions asked within the survey as well as the anonymized answers can be found in the data sheet "Open_Science_Survey_BN_cln.xlsx" within this repository.

Further, this repository contains a Jupyter notebook "Survey_results.ipynb". The notebook analyses and graphically represents the data contained within the data sheet.
To run the notebook, clone the repository to your local machine and follow the instruction below to set up the required Python environment:

- Open folder in terminal
- Create environment with `conda env create --file environment.yml --force`
- Activate environment with `conda activate open_science_survey`
- Run jupyter lab with `jupyter lab`
- In jupyter lab, open file "Survey_results.ipynb" and follow instructions there

The survey results can be viewed either directly within the Jupyter notebook, or in the output auto-generated by it (in the folder "plot_results_BN" as pdf files).

The file "Open Science Survey BN web results.pdf" contains the survey results in the representation generated by Microsoft Forms for comparison.