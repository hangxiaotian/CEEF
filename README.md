<div id="top" align="center">
  
# CEEF
**Joint Contrast Enhancement and Exposure Fusion for Real-World Image Dehazing**
  
  [[Paper]](https://ieeexplore.ieee.org/document/9537303)
  
  **Xiaoning Liu**, Hui Li, Ce Zhu

<a href="#license">
  <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-blue.svg"/>
</a>
</div>

## Table of Contents
- [Testing Set](#testing-set)
- [Evaluation Metric](#evaluation-metric)
- [Testing](#testing) 
- [Real Image Dehazing](#real-image-dehazing)
  - [Daytime image dehazing](#daytime-image-dehazing)
  - [Nighttime image dehazing](#nighttime-image-dehazing)
- [Image Editing](#image-editing)
- [Third-party Usage and Experiments](#third-party-Usage-and-Experiments)
- [References](#references)



## Testing Set
* [Daytime fog images](https://www.cs.huji.ac.il/w~raananf/projects/dehaze_cl/results/)
* [Nighttime fog images](https://github.com/chaimi2013/MRP)
* [Foggy Driving](http://people.ee.ethz.ch/~csakarid/SFSU_synthetic/)

## Evaluation Metric
[Fog Aware Density Evaluator (FADE)](http://live.ece.utexas.edu/research/fog/index.html)

## Testing

```matlab
git clone https://github.com/hangxiaotian/CEEF
cd CEEF
matlab demo.m
```

## Real Image Dehazing
### Daytime image dehazing

- <img src="InputImages/cliff_input.png" width="350px"/><img src="result/cliff_input_Proposed.png" width="350px"/>
- <img src="InputImages/forest_input.png" width="350px"/><img src="result/forest_input_Proposed.png" width="350px"/>

### Nighttime image dehazing
- <img src="NightTime/flickr10.bmp" width="350px"/><img src="NightResults/flickr10_Proposed.png" width="350px"/>
- <img src="NightTime/flickr20.bmp" width="350px"/><img src="NightResults/flickr20_Proposed.png" width="350px"/> 

## Image Editing
The left is the sample image from [Vivo](http://gallery.vivo.com.cn/). The midle is edited by Vivo. The right is edited by the proposed method.
- <img src="ImageEditing\Input\Before_editing.jpg" width="250px" /><img src="ImageEditing\vivo_sample.jpg" width="250px" /><img src="ImageEditing\Proposed.png" width="250px" />

## Third-party Usage and Experiments
[03/06/2023] CEEF for Underwater Image Enhancement: [UIE_CP](https://ieeexplore.ieee.org/document/10061417/footnotes#footnotes) [[code](https://github.com/xiaoxuan98/UIE_CP/)]

## References
----------
```BibTex
@arctile{liu2021joint, % CEEF
  title={Joint Contrast Enhancement and Exposure Fusion for Real-World Image Dehazing},
  author={Liu, Xiaoning and Li, Hui and Zhu, Ce},  
  journal={IEEE Transactions on Multimedia},   
  year={2022},  
  volume={24},  
  number={},  
  pages={3934-3946},  
  doi={10.1109/TMM.2021.3110483}
}
```
