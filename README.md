# Paper Title
Revealing Land Use Dynamics in Armed-Conflict Hotspots in North-East Nigeria Using Earth Observation Data


# Graphical Summary
![Graphical Abstract](Figures/Graphical_Abstract.png "Graphical Abstract")


# How to Run
All dependencies and their versions are listed in `land_conflict.yml` file.

## 1. Create the Conda environment

Open **Anaconda Prompt** and navigate to the folder containing `land_conflict.yml`:

```bash
cd path\to\your\folder
```

Then create the environment (the name `land-conflict` is already defined inside the `.yml`):

```bash
 conda env create -f land_conflict.yml
```

## 2. Activate the environment

Once installation completes successfully, activate it:

```bash
conda activate land-conflict
```

## 3. Activate the environment
This project requires (login) credentials for **ACLED** and **Google Earth Engine (GEE)**, and a project name for **DTM**.

Create a `.env` file in the project root folder (same location as the notebook) and add the following:

```
GEE_PROJECT_NAME="your-gee-project-name"
ACLED_EMAIL="your_acled_email@example.com"
ACLED_PASSWORD="your_acled_password"
DTM_API_KEY=your-dtm-api-key
```

- **GEE_PROJECT_NAME**: Your Google Earth Engine project name. Register at https://earthengine.google.com.
- **ACLED_EMAIL** and **ACLED_PASSWORD**: Register at https://acleddata.com.
- **DTM_API_KEY**: Register at https://dtm-apim-portal.iom.int to get your subscription key.

Never share your `.env` file or commit it to version control. 


# How to Cite
If you used the code and/or data, kindly cite this paper:

```bibtex
@article{lateef2025revealing,
  title={Revealing Land Use Dynamics in Armed-Conflict Hotspots in North-East Nigeria Using Earth Observation Data},
  author={Lateef, Lateef O. and Tella, A. and Miano, J. R. and Aina, Y. A.},
  journal={Land Use Policy},
  volume={157},
  pages={107673},
  year={2025},
  doi={10.1016/j.landusepol.2025.107673},
  publisher={Elsevier}
}
```


# Credits
This project includes code from:

-  Ujaval Ghandi: https://gee-community-catalog.org/tutorials/examples/glc_fcs30d_lulc/


# Copyright
&copy; 2025. All rights reserved.