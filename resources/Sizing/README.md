# Sizing

In this folder you can find `Xschem` schematics to characterize the MOSFETs according to the gm/ID method. The `Xschem` schematics are used to extract the MOSFET parameters and generate the plots. Look a [`techsweep_gf180mcu_plots.ipynb`](techsweep_gf180mcu_plots.ipynb) on how you can visualize the results.

The tables `gf180mcu_nmos_3v3.mat` and `gf180mcu_pmos_3v3.mat` contain the extracted MOSFET parameters for NMOS and PMOS transistors, respectively. You can use Jupyter notebooks and the `pygmid` package to build sizing scripts for your designs.

## NMOS 3v3 Characterization Plots

![gm/ID vs. VGS](techsweep_gf180mcu_plots/gf180mcu_nmos_3v3_gmID_fT_VGS.png)
![fT*gm vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_nmos_3v3_fTgmID_gmID.png)
![fT vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_nmos_3v3_fT_gmID.png)
![gm/gds vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_nmos_3v3_gmgds_gmID.png)
![VDS,sat vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_nmos_3v3_Vdssat_gmID.png)
![ID/W vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_nmos_3v3_IDW_gmID.png)

## PMOS 3v3 Characterization Plots

![gm/ID vs. VGS](techsweep_gf180mcu_plots/gf180mcu_pmos_3v3_gmID_fT_VGS.png)
![fT*gm vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_pmos_3v3_fTgmID_gmID.png)
![fT vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_pmos_3v3_fT_gmID.png)
![gm/gds vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_pmos_3v3_gmgds_gmID.png)
![VDS,sat vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_pmos_3v3_Vdssat_gmID.png)
![ID/W vs. gm/ID](techsweep_gf180mcu_plots/gf180mcu_pmos_3v3_IDW_gmID.png)
