
# Prerequisites
- Maya2015
- mayapy 2.7.3
- numpy

      % wget https://bootstrap.pypa.io/get-pip.py
      % sudo mayapy get-pip.py   
      % sudo mayapy -m pip install numpy

# Datasets

- Put [MIT mocap dataset](http://mocap.cs.cmu.edu/) in ./external/
- Put models in ./external (not yet implemented)

# How to use
1. Select mocap data used for pose generation.

       % scripts/select_poses.sh
2. generate scenes by using selected poses and models in ./external/

       % scrtips/generate_scenes.sh
3. filiming scenes by multiple virtual cameras



# License

[BSD 2-Clause License](https://github.com/AtsushiHashimoto/PoseEstimationTrainingDataGenerator-maya/blob/master/LICENSE)
