# Template World
This is a template world to demonstrate how to structure your submission

# Structure
Your submission to this repository should look something like this:
```
.
|-- input_points.yaml   A yaml file containing any important input points
|-- map
|   |-- project_map.pgm                             A pgm image of the map as made by rospy SLAM
|   `-- project_map.yaml                            A yaml file designating the parameters of the map file
|-- models                                          
|   |-- model_name                                  Name of the custom model
|   |   |-- materials                               Any materials needed
|   |   |   |-- scripts                             
|   |   |   |   `-- Cluedo_character.material       Custom mateial scripts
|   |   |   `-- textures                            
|   |   |       `-- Cluedo_character.png            Any textures used
|   |   |-- model.config                            Model config
|   |   `-- model.sdf                               3D model of the model
|-- project.world                                   Gazebo world file
`-- readme.md                                       This readme file
```

# Author
George Sykes: el18gs@leeds.ac.uk
