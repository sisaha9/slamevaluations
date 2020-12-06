# slamevaluations

This is just a repo containing the evaluation scripts for SLAM made by the Computer Vision Group in Technical University of Munich's Department of Informatics. I have modified it to work with python3. See this for the original files https://svncvpr.in.tum.de/cvpr-ros-pkg/trunk/rgbd_benchmark/rgbd_benchmark_tools/src/rgbd_benchmark_tools/


Once you get the 3 text files in the format mentioned in the link above/from the simulator repo here: https://github.com/sisaha9/dsc180a-slam-simulator

Just run 
1. python evaluate_ate.py rtabmap_slam.txt rtabmap_gt.txt --plot ate.png
2. python evaluate_rpe.py rtabmap_odom.txt rtabmap_gt.txt --plot rpe.png --fixed_delta

Soon a library for better hyperparameter tunign will be released with this as a base
