# Graphics Final Project: The End
  
### Bayan Berri Period 10

### New Features

#### Lighting

Relevant MDL commands: ambient, light, constants  
light name r g b x y z - creates a "light" datastructure with rgb values r,g,b at location x,y,z. This is inserted into the symbol table.
  
ambient r g b - specifies how much ambient light is in the scene  
  
constants name kar kdr ksr kag kdg ksg kab kdb ksb - saves a set of lighting components in the symbol table under "name."  

#### Polygon Meshes

Relevant MDL commands: mesh  
mesh [constants] :filename - adds corresponding points from filename to the polygon matrix. File must be in .obj format with three vertices per face.  