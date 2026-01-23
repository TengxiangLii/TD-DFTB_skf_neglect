# TD-DFTB_skf_neglect

## Author: Tengxiang Li, Sergei Manzhos

This is the supplementary data for the article "A Study of Applicability of Density Functional Tight Binding – Molecular Mechanics Approach for Optical Properties".  
Included are the structures of the dye molecule optimized at PBE and B3LYP levels of theory (files c1_pbe_final.xyz, c1_b3lyp_final.xyz) and the dye-TiO2 nanopartcle complex optimized at these levels of theory (np_c1_pbe.xyz, np_c1_b3lyp.xyz) in ./struc folder, as well as DFTB+ readable parameter files with zeroed-out electronic parameters ( .skf files in ./skf folder).  

*Update*  
Strutures of the Isoindigo molecule, Si nanoparticle (H terminated), and N,P-doped Si nanoparticle are added in ./struc folder. DFTB+ readable parameters files for new added model are also addin in ./skf folder.


```
.
├── README.md
├── skf
│   ├── matsci
│   │   ├── N-P.skf
│   │   └── P-N.skf
│   └── tiorg
│       ├── C-O.skf
│       ├── C-Ti.skf
│       ├── N-N.skf
│       ├── N-O.skf
│       ├── N-S.skf
│       ├── O-C.skf
│       ├── O-N.skf
│       ├── O-S.skf
│       ├── S-N.skf
│       ├── S-O.skf
│       ├── S-Ti.skf
│       ├── Ti-C.skf
│       └── Ti-S.skf
└── struc
    ├── NP_doped_Si_NP.xyz
    ├── Si_NP.xyz
    ├── c1_b3lyp_final.xyz
    ├── c1_pbe_final.xyz
    ├── isoindigo_opted.xyz
    ├── np_c1_b3lyp.xyz
    ├── np_c1_pbe.xyz
    └── tiorg_c1np_opted.xyz
```
