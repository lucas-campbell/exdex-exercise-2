To run this notebook, do the following:

1. Download the repo's files locally, then unzip input.zip into just input/ :
Linux:
unzip input.zip -d .

Windows:
Use the File Explorer GUI and unzip input.zip to sit at the same level as the notebook script.

Be sure to confirm sure all 8 .csv files are inside a folder labeled 'input'
that exists at the same level as the notebook file. Then, 5 world shapefiles 
(ne_110m*) should be in their own subdirectory (./input/world-shapefile/).

The final directory should look like the following, after unzipping. Note that 
this includes files and directories generated after running the notebook:

$ tree
.
├── Missing
│   ├── df_access level_missing.txt
│   ├── df_computer skills_missing.txt
│   ├── df_coverage by speed_missing.txt
│   ├── df_digital skills_missing.txt
│   ├── df_missing within country_missing.txt
│   ├── df_traffic outside country_missing.txt
│   ├── df_traffic within country_missing.txt
│   └── df_use frequency_missing.txt
├── README.txt
├── Unique
│   ├── df_access level_unique.txt
│   ├── df_computer skills_unique.txt
│   ├── df_coverage by speed_unique.txt
│   ├── df_digital skills_unique.txt
│   ├── df_missing within country_unique.txt
│   ├── df_traffic outside country_unique.txt
│   ├── df_traffic within country_unique.txt
│   └── df_use frequency_unique.txt
├── ex2.ipynb
├── ind_type_name_mapping.txt
├── info_society_indicator_name_mapping.txt
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
├── q3_correlation_time_series.csv
├── q3_line_plot_professional.png
└── requirements.txt

2. Run: 

pip install -r requirements.txt

in your venv or other chosen python environment


3. Run the notebook with your *.ipynb program of choice. This notebook was 
confirmed to work in Kaggle and using the VSCode Jupyter plugin.