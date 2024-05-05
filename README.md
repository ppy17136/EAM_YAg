Companion repository for the paper:



YAg potential

Contents

The interatomic potential described in the publication is provided as a tabulated LAMMPS potential file to be used in molecular dynamics/statics simulations of the Y-Ag system.

Usage

Use the following LAMMPS commands in the LAMMPS input file:

        pair_style eam/alloy
        pair_coeff * * YAg_BLLv.eam.alloy Y Ag
    
References
