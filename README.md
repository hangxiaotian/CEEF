## Joint Contrast Enhancement and Exposure Fusion for Real-World Image Dehazing
**Xiaoning Liu**, **Hui Li***, Ce Zhu

This paper is accepted by [IEEE TMM](https://ieeexplore.ieee.org/document/9537303).

## Testing Set
* [Daytime fog images](https://www.cs.huji.ac.il/w~raananf/projects/dehaze_cl/results/)
* [Nighttime fog images](https://github.com/chaimi2013/MRP)
* [Foggy Driving](http://people.ee.ethz.ch/~csakarid/SFSU_synthetic/)

## Evaluation Metric
[Fog Aware Density Evaluator (FADE)](http://live.ece.utexas.edu/research/fog/index.html)

## Testing

```python
matlab demo.m
```

## Real Image Dehazing
### Daytime image dehazing
<center class="half">
<img src="InputImages/cliff_input.png" width="350px"/>
<img src="result/cliff_input_Proposed.png" width="350px"/>
</center>

- <img src="InputImages/buildings_input.png" width="350px"/><img src="result/buildings_input_Proposed.png" width="350px"/>

### Nighttime image dehazing
- <img src="NightTime/flickr10.bmp" width="350px"/><img src="NightResults/flickr10_Proposed.png" width="350px"/>
- <img src="NightTime/flickr20.bmp" width="350px"/><img src="NightResults/flickr20_Proposed.png" width="350px"/> 

## Image Editing
The left is the sample image from [Vivo](http://gallery.vivo.com.cn/). The right is the denoised image by FFDNet

References
----------
```BibTex
@arctile{liu2021joint, % CEEF
  title={Joint Contrast Enhancement and Exposure Fusion for Real-World Image Dehazing},
  author={Liu, Xiaoning and Li, Hui and Zhu, Ce},  
  journal={IEEE Transactions on Multimedia},   
  year={2021},  
  volume={},  
  number={},  
  pages={1-1},  
  year-{2021}
  doi={10.1109/TMM.2021.3110483}
}
```
