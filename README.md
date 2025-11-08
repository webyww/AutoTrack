# AutoTrack

<div align="center">
  
**AutoTrack 主要功能演示**

<img src="https://github.com/webyww/AutoTrack/blob/main/doc/AutoTrack.gif" width="1000" alt="AutoTrack功能演示">


</div>

![comparison](https://github.com/webyww/AutoTrack/blob/main/doc/AutoTrack.gif)

![comparison](https://github.com/webyww/AutoTrack/blob/main/doc/lb.png)

### [Youtube](https://youtu.be/RgQ2RkXjt44)
## Main Results

### [nuScenes](https://www.nuscenes.org/tracking?externalData=all&mapData=all&modalities=Any)

#### 3D Multi-object tracking on nuScenes test set   
[NuScenes Leaderboard](https://eval.ai/web/challenges/challenge-page/476/leaderboard/1321)   

 Method       | Detector      | AMOTA    | MOTA     | IDS      |   Model   |   log    |
--------------|---------------|----------|----------|----------|----------|----------|
 AutoTrack    | FocalFormer-F | 77.9     | 66.5     | 178      |       [Google Drive](https://www.nuscenes.org/tracking?externalData=all&mapData=all&modalities=Any)     |----------|


#### 3D Multi-object tracking on nuScenes val set   

 Method       | Detector      | AMOTA    | MOTA     | IDS      |   Model   |   log    |
--------------|---------------|----------|----------|----------|----------|----------|
 AutoTrack    | FocalFormer-F | 79.3     | 69.6     | 136      |       [Google Drive](https://www.nuscenes.org/tracking?externalData=all&mapData=all&modalities=Any)     |----------|
 

#### 3D Multi-object tracking on KITTI test set

  Method       | Detector      | HOTA      | MOTA     | IDS      |   Model  |   log    |
--------------|---------------|------------|----------|----------|----------|----------|
 AutoTrack    | Centerpoint   | 81.05      | 89.87    | 36       |      [Google Drive](https://www.nuscenes.org/tracking?externalData=all&mapData=all&modalities=Any)     |----------|

#### 3D Multi-object tracking on KITTI test set

  Method       | Detector      | HOTA      | MOTA     | IDS      |   Model  |   log    |
--------------|---------------|------------|----------|----------|----------|----------|
 AutoTrack    | Centerpoint   | 81.05      | 89.87    | 36       |      [Google Drive]([https://www.nuscenes.org/tracking?externalData=all&mapData=all&modalities=Any](https://drive.google.com/file/d/1mMJwioLTqLOcuGHiuQ8d5FPaHqhRZQQA/view?usp=sharing))     |----------|

 https://eval.ai/web/challenges/challenge-page/476/leaderboard/1321

 
## Acknowledgement

- In the detection part, many thanks to the following open-source projects:
  
  - [FocalFormer](https://github.com/tusen-ai/SST?tab=readme-ov-file)
    
  - [VirConv](https://github.com/hailanyi/VirConv)
    
  - [CenterPoint](https://github.com/tianweiy/CenterPoint)
    
- In the tracking part, many thanks to the following open-source projects:
  
  - [Fast-poly](https://github.com/lixiaoyu2000/FastPoly)
  
  - [MCTrack](https://github.com/megvii-research/MCTrack)
    
  - [Poly-MOT](https://github.com/lixiaoyu2000/Poly-MOT)


 
