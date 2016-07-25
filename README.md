icub-custom-urdf
=============


Description
-----------

The URDF file icub_arms_torso_free.urdf is a model of the humanoid robot iCub. It is a custom URDF used for the simulation experiments in the framework [learnOptimWBC](https://github.com/serena-ivaldi/learnOptimWBC).
It is based on the URDF found in the repository [robotology-playground/icub-model-generator](https://github.com/robotology-playground/icub-model-generator/blob/master/generated/gazebo_models/icubGazeboSim/icub_simulation.urdf). The only modifications are type changes of all undesired joints from "revolute" to "fixed" in order to have a model with only its arms and torso free.  
This model have 32 joints but only 17 none fixed joints, therefore only 17 degrees of freedom.
