# FBU-DTW-for-signature-verification
The code of "Information Divergence-Based Matching Strategy for Online Signature Verification"

## FBU-DTW
- Paper Link: http://ieeexplore.ieee.org/document/8097414

- Title: Information Divergence-Based Matching Strategy for Online Signature Verification
  
- Author: Lei Tang, Wenxiong Kang, Yuxun Fang (from BIP Lab, SCUT, P.R.China)
  
- Date: 2018/01/10
  
- Contact: fang.yuxun@mail.scut.edu.cn
  
- COPYRIGHT (C) Lei Tang, Wenxiong Kang, Yuxun Fang 
  
- ALL RIGHTS RESERVED

  The code can be used only for academic researches, when use this code in your paper, please cite the paper.
  
  __L. Tang, W. Kang, Y. Fang, Information Divergence-based Matching Strategy for Online Signature Verification, IEEE Transactions on Information Forensics & Security, 2018.13(4): 861-873.__

## Instructions
  Because of the permissions, we can't provide the database. You need to add the susig and mcyt database to the folder.

  Run the "main.m" script in MATLAB.
  
  You can select the initialization parameters in __setting__.
  
## Performance
__Note__: The result is slightly different from the report of the paper, which is mainly because the numerical differences in the process of reproduction. What's more, we find a better parameter of the classifier ID2 and slightly imporve the performance.

database |  EER TN 5  | EER TN 10 |
---------|  --------  |  -------- |
  mcyt   |    3.11%   |    2.16%  |
 susig   |    2.34%   |    1.60%  |
 
*TN: training sample number
