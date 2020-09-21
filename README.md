# CCF JC

All data from Allen CCFv3, and this paper:

Wang, Quanxin, Song-Lin Ding, Yang Li, Josh Royall, David Feng, Phil Lesnar, Nile Graddis, et al. 2020. “The Allen Mouse Brain Common Coordinate Framework: A 3D Reference Atlas.” Cell 181 (4): 936–53.e20.

1. CCF nrrd and label files downloaded from [here](http://download.alleninstitute.org/publications/allen_mouse_brain_common_coordinate_framework/transgenic_lines_25_um_grid/ccf/)
2. Install ITK-SNAP [here](http://www.itksnap.org/pmwiki/pmwiki.php?n=Downloads.SNAP3)

## Files from Allen CCF
- CCF/
	- These files are too large for github, you need to download from Allen's FTP above
	- average template nrrd file, load as image in ITK-SNAP
	- segamentation file, value on each voxel corresponding to structure id in the CCF, load as segamentation in ITK-SNAP
	- More details about using ITK-SNAP can be found on [youtube](https://www.youtube.com/watch?v=BvQyjk1etLU&t=13s)
- PLY/
	- mesh files, which is named by acronym of CCF structures
- python/
	- Example code to load nrrd and ply files
- StructureTree/
	- Json files convert region ids to region names, or many other properties in the Allen CCF structure tree, made from description [here](https://allensdk.readthedocs.io/en/latest/reference_space.html)