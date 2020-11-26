# ModularBeautySystem
This is a framework for custom modular storage and organization of beauty products.
It currently only supports Red Carpet Manicure brand nail polish, but the intention is to expand support to any needed brand or category of product.
## Modularity
The system consists of 50mmx50mm blocks.
* Blocks can be greater than 50mm in the X and/or Y dimension, as long as they are a multiple of 50 and have the proper tongue/grove in each 50mm length.
* Blocks can be any length in the Z dimension, as long as the dovetail joints are not altered.
## Organization
Parts are sorted into directories for their primary intended use, e.g. Nails, Makeup, etc.
* Each category directory should contain an \_STLs directory with up to date .stl files for every part in that category. 
## Connections
Blocks are connected using dovetail joints.  _TODO: Lexa, create a technical drawing of the standard dovetail joint dimensions including tolerances_
## Naming Convention
[Category] (EN Dash) [Item type], [(opt)Subtype], [(Opt)SubSubtype]
e.g. Misc – Storage Bin, 1x1
