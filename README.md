# Source code address
Note: 
Due to GitHub's memory size limit (less than 25MB), I put it in my online disk, and the address of the online disk is as follows: 

Address： https://pan.baidu.com/s/1cuOKeqcloo3-SF-CT4Xqmg 
Extraction code： 1234


# RHCF
A new visual tracker called RHCF based on correlation filter.

NOTE: This tracker is an improved approach based on CF2 (HCF), so there are plenty of codes are brought from CF2, and the paper name is "Hierarchical Convolutional Features for Visual Tracking".

1. Download the VGG-NET-19 mat file and put into the model folder using the link
https://uofi.box.com/shared/static/kxzjhbagd6ih1rf7mjyoxn2hy70hltpl.mat

or using the link if you are in China
http://pan.baidu.com/s/1kU1Me5T 

Note that this mat file is compatile with the MatConvNet-1beta10 used in this work, if you download the mat file from
http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat,
please pay attention to the version compatibility.  

2. Include the path of matconvnet/matlab

3. Run the main entry file run_tracker.m

% Note that run_RHCF is an interfance for OBT-50 and OBT-100:
%
% process a sequence using RHCF (Correlation filter tracking with convolutional features)
%
% Input:
%     - seq:        sequence name
%     - res_path:   result path
%     - bSaveImage: flag for saving images
% Output:
%     - results: tracking results, position prediction over time
%
%   It is provided for educational/researrch purpose only.
%   If you find the software useful, please consider cite our paper：
%
%   Reinforced Tracker Based on Hierarchical Convolutional Features
%

The folder RHCF_OTB2013_Mat_results includes the results of RHCF, RHCF_LM, RHCF_LHC over OTB2013.


Note: 
Due to GitHub's memory size limit (less than 25MB), I put it in my online disk, and the address of the online disk is as follows: 

Address： https://pan.baidu.com/s/1cuOKeqcloo3-SF-CT4Xqmg 
Extraction code： 1234

# CITE
If you think these codes can help you find new trackers, please cite the following papers:
[1] ZENG X, ZHANG L, LUO Z, et al. Reinforced Tracker Based on Hierarchical Convolutional Features[J]. IEICE TRANSACTIONS on Information and Systems, 2022, 105(6): 1225-1233.
[2] Zeng X, Zhang L, Luo Z, et al. An Improved Visual Tracking Approach Based on Hierarchical Convolutional Features[C]//2021 IEEE Asia Conference on Information Engineering (ACIE). IEEE, 2021: 42-46.


