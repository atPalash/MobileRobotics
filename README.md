# MobileRobotics
Various codes developed during mobile robotics course are included in the respective folders
1. Path_finder
    the task was to find a optimal path from start point to goal point using Djikstra, Dynamic and A* algorithm. (The plots were drawn with different set of random nodes)
    
    the map is shown below:
    
    ![obstruction_nodes](https://user-images.githubusercontent.com/25124540/33582118-4d34e48e-d95c-11e7-80be-74871182d2af.jpg)
    
    the paths found using different algorithm are shown below:

    ![dijkstra_path](https://user-images.githubusercontent.com/25124540/33582238-ee68aec6-d95c-11e7-812c-cfe5f8a0c395.jpg)
    
    ![dynamic_path](https://user-images.githubusercontent.com/25124540/33582247-f975e522-d95c-11e7-91a1-b9f8c3bd219d.jpg)
    
    ![astar_path](https://user-images.githubusercontent.com/25124540/33582256-040b1d54-d95d-11e7-94a2-b24ca1044b63.jpg)
 
2. path_smoothing & robot controller
    The waypoints were given to reach from start point to goal point, this task implemented path_smoothing using cubic splines and then directed the turtlebot along the path. The smooth path is as shown below:
    
    ![smoothed_path_waypoints](https://user-images.githubusercontent.com/25124540/33583436-1a12a472-d963-11e7-902d-6273ec0b7f53.jpg)

    the link to the video is:https://www.youtube.com/watch?v=G5n23-CyWmk&t=46s
    this folder also contains code for feature extraction using turtlebot camera.




