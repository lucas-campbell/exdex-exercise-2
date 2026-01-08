To run this notebook, do the following:

1. Download the repo's files locally, then unzip input.zip into just input/ :
Linux:
unzip input.zip -d .

Windows:
Use the File Explorer GUI and unzip input.zip to sit at the same level as the notebook script.

Be sure to confirm sure all 8 .csv files are inside a folder labeled 'input'
that exists at the same level as the notebook file. Then, 5 world shapefiles 
(ne_110m*) should be in their own subdirectory (input/world-shapefile/).

The final directory should look like this, after unzipping:

$: tree

.
├── README.txt
├── ex2.ipynb
├── input
│   ├── isoc_cbs_linear_2_0.csv
│   ├── isoc_ci_ifp_iu_linear_2_0.csv
│   ├── isoc_ci_in_h_linear_2_0.csv
│   ├── isoc_sk_cskl_i_linear_2_0.csv
│   ├── isoc_sk_dskl_i_linear_2_0.csv
│   ├── isoc_tmi_linear_2_0.csv
│   ├── isoc_tmo_linear_2_0.csv
│   ├── m_br_within_c_missing.csv
│   └── world-shapefile
│       ├── ne_110m_admin_0_countries.cpg
│       ├── ne_110m_admin_0_countries.dbf
│       ├── ne_110m_admin_0_countries.prj
│       ├── ne_110m_admin_0_countries.shp
│       └── ne_110m_admin_0_countries.shx
├── input.zip
└── requirements.txt

3 directories, 17 files


2. Run: 

pip install -r requirements.txt

in your venv or other chosen python environment


3. Run the notebook with your *.ipynb program of choice. This notebook was confirmed to work in Kaggle and using the VSCode Jupyter plugin.
