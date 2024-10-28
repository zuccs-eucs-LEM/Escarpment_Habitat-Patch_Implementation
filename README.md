Workflow for re-producing landscape evolution models and habitat patch evolution

Landscape Models using goSPL workflow:

-	Firstly, use the create_escarpment_mesh.ipynb notebook. This enables creation of the escarpment as a grid and mesh.

-	Secondly, the Escarpment_extraction.ipynb notebook will create the associated netCDF files needed for subsequent figures/analysis in a secondary program (e.g. Paraview) for visualisation of landscape evolution through time (see section 3.3.1. – Fig. 8). Further, these files enable extraction of escarpment cross-profiles and flexural response curves.

Habitat Patches workflow:

-	Thirdly, the Habitat_Patch_Creation.ipynb notebook will create and visualize the habitat patch dynamics through time (see section 3.4.3 for more details)

Miscellaneous: 
-	input_escarpment.yml – referred to in create_escarpment_mesh.ipynb and Escarpment_extraction.ipynb

-	Scripts folder, build_ncgrids.py, and runModel.py are utilized in the create_escarpment_mesh.ipynb
