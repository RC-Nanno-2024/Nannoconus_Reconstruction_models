**##Exaplanations of the operations with line numbers in layer model##**

(1-35): Loading the images of the segmented lamella in an 3D-array of numbers
(38-63): Function created to for translation and rotation of the lamellae
(66-82): Functions created to rotate vectors
(84-150): Mesh and convex hull are created from the 3D-array to reduce its size
(152-157): The lamella (hull) is alienated parallel to the basal plane, with its centre at the origin of the co-ordinate system and
(159-401): 12 series of points (r, ɵ, z), representing 12 layers are created.
(403-540): The lamella is assigned with rotation creating tilt and inclinations in each point of the 12 layers. The skeleton is generated by combining 12 layers. This saved as a 3D array
(542-549): The 3D array of the reconstructed skeleton is visualized as 3D object in the software (Dragonfly)

**##Exaplanations of the operations with line numbers in segment model##**

(1-35): Loading the images of the segmented lamella in an 3D-array of numbers
(38-63): Function created to for translation and rotation of the lamellae
(66-82): Functions created to rotate vectors
(84-150): Mesh and convex hull are created from the 3D-array to reduce its size
(152-157): The lamella (hull) is alienated parallel to the basal plane, with its centre at the origin of the co-ordinate system and
(159-401): 12 series of points (r, ɵ, z), representing 12 segments are created.
(403-587): The lamella is assigned with rotation creating tilt and inclinations in each point of the 12 segments. The skeleton is generated by combining 12 segments. This saved as a 3D array
(589-596): The 3D array of the reconstructed skeleton is visualized as 3D object in the software (Dragonfly)
