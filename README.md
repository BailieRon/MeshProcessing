The associated grasshopper files perform pre-processing of mesh elements and format them for export in .xyz format. One is a demonstration of this workflow for a 2D planar mesh (2DMesh_geometry.gh), 
the other handles a 3D field of voxel mesh elements (LES_LBM_simulation_geometry.gh). Both files require Rhino/Grasshopper installation to be utilized (Rhino 8 is recommended). Neither of these
grasshopper files are associated with a Rhino .3dm file or any Rhino geometry (all geometry is generated within Grasshopper).

To export mesh component data from the grasshopper scripts in .xyz or .txt format, simply right click the yellow panel containing data and select 'stream destination'. Then, set your file type to .xyz (or .txt) and save the
file to your specified location. Please note the data may require some pre formatting, this can easily be done by using 'concatentate' components in grasshopper.

There are no required grasshopper plug-in files for the LES_LBM_simulation_geometry.gh file (all components are native to grasshopper)

A number of plug-ins are required for installation for the 2DMesh_geometry.gh file. Please locate the folder '2DMesh_required_packages' within this repository. The files contained in this folder can
be installed into grasshopper by going to file -> special folders - > components folder, then drag and drop the files into this folder. Restart Rhino/Grasshopper after placing these files into the
components folder. I do not take any ownership to the associated plug ins inside of the '2DMesh_required_packages' folder (Cockroach, Pufferfish, Flexibility).

Please note that these grasshopper scripts were developed on a computer running Windows, and some of the plug in files within the folder '2DMesh_required_packages' may have issues installing on a Mac.
If there are any issues installing plug-in packages or running either grasshopper file please reach out for assistance.
