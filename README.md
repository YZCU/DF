# [DF](https://ieeexplore.ieee.org/document/9803284)

The official implementation for "**Single Object Tracking in Satellite Videos: A Correlation Filter-Based Dual-Flow Tracker**", 
IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (JSTARS), 2022.

- Authors: 
[Yuzeng Chen](https://yzcu.github.io/), 
[Yuqi Tang*](https://faculty.csu.edu.cn/yqtang/zh_CN/zdylm/66781/list/index.htm),
Zhiyong Yin,
[Te Han](https://github.com/rshante0426),
[Bin Zou](https://faculty.csu.edu.cn/binzou/zh_CN/index.htm), and 
[Huihui Feng](https://faculty.csu.edu.cn/fenghuihui/zh_CN/index/62683/list/index.htm)
- Central South University and Key Laboratory of Metallogenic Prediction of Nonferrous Metals and Geological Environment Monitoring
## Usage
- We've updated and embedded DF tracker into the [OOTB](https://github.com/YZCU/OOTB) project
- OOTB is a benchmark including oriented satellite video datasets and evaluation benchmark
- Codes for DF tracker is in the path `\tracker_benchmark_v1.0\trackers\DF`
- Download the related OOTB dataset on [Baidu Cloud Disk (code: OOTB)](https://pan.baidu.com/s/11hsA4pOliwA1FpOqNol93w)
- Run the `\tracker_benchmark_v1.0\main_running.m`
- Results are saved in `\tracker_benchmark_v1.0\results\results_OPE_ootb`
- Evaluation of the DF tracker. Run `\tracker_benchmark_v1.0\perfPlot.m`
## Abstract
>Satellite video (SV) can acquire rich spatiotemporal information on the Earth. Single object tracking (SOT) in SVs enables the continuous acquisition of the position and range of a specific object, expanding the field of remote-sensing applications. In SVs, objects are small with limited features and vulnerable to tracking drift. In this paper, a correlation filter-based dual-flow (DF) tracker is proposed to explore how the hybridization of spatial-spectral feature fusion and motion model can boost tracking. To represent small objects, the DF adaptively fuses complementary features using a state-aware indicator in feature flow. In motion flow, the indicator perceives the confidence of the feature flow. A dual-mode prediction model is then constructed to simulate the object¡¯s motion pattern, and cooperate linear and non-linear motion patterns to implement SOT in SVs. The ablation experiments demonstrate the dual-flow contributes to tracking. Experimental comparisons on 14 real SVs captured by the Jilin-1 satellite constellation show that DF achieves optimal performance with an area under the curve of 0.912 in the precision plot, 0.700 in the success plot, and a speed of 155.2 frames per second. This work would encourage the development of remote-sensing ground surveillance.

## Overview
 ![image](/fig/df.jpg)
## Results
- Results on OOTB
 ![image](/fig/overallresults.jpg)
 ![image](/fig/overallfigs.jpg)

## Contact
If you have any questions or suggestions, feel free to contact me.  
Email: yuzeng_chen@whu.edu.cn 

## Citation
If you find our work helpful in your research, kindly consider citing it. We appreciate your support.

```
@ARTICLE{9803284,
  author={Chen, Yuzeng and Tang, Yuqi and Yin, Zhiyong and Han, Te and Zou, Bin and Feng, Huihui},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={Single Object Tracking in Satellite Videos: A Correlation Filter-Based Dual-Flow Tracker}, 
  year={2022},
  volume={15},
  number={},
  pages={6687-6698},
  keywords={Correlation;Videos;Remote sensing;Satellites;Object tracking;Adaptation models;Optical filters;Correlation filter (CF);motion model;satellite video (SV);state-aware indicator (SAI);single object tracking (SOT)},
  doi={10.1109/JSTARS.2022.3185328}}
```
