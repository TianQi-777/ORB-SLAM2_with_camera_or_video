# ORB-SLAM2_with_camera_or_video
This is a project modified on the basis of ORB-SLAM2 to use your own camera of PC or video. If you want to know more about ORB-SLAM2, please cite (http://webdiis.unizar.es/~raulmur/orbslam)

The whole project is tested in Ubuntu Platorforms


## Prerequisites needed for compiling and running the raw ORB-SLAM2
Please cite(https://github.com/raulmur/ORB_SLAM2) for more details.

## How to use this demo
1. Replace the raw CMakeLists.txt(Path:XXX/ORB_SLAM2/CMakeLists.txt) with new CMakeLists.txt

2. Create a new folder named Myslam（Path:XXX/ORB_SLAM2/Examples/Myslam)

3. Move myslam.cpp myslam.yaml myvideo.cpp myvideo.yaml to Myslam folder

4. Modify your path in myslam.cpp and myvideo.cpp.
   For examples:  
   in myslam.cpp  
   string parameterFile = "XXX/ORB_SLAM2/Examples/Myslam/myslam.yaml";  
   string vocFile = "XXX/ORB_SLAM2/Vocabulary/ORBvoc.txt";
   
   in myvideo.cpp  
   string parameterFile = "XXX/ORB_SLAM2/Examples/Myslam/myslam.yaml";  
   string vocFile = "XXX/ORB_SLAM2/Vocabulary/ORBvoc.txt";  
   string videoFile = "XXX/XXX.mp4";(Prepare by yourself)
   
5. Re-build all programs like raw ORB-SLAM2

6. Run 
   Current operating environment:XXX/ORB_SLAM2  
   ./Examples/Myslam/myvideo  
   or  
   ./Examples/Myslam/myslam  

## Result
**camera**  
<div align=center>  
  
![](https://github.com/TianQi-777/ORB-SLAM2_with_camera_or_video/blob/master/Images/camera.png)
</div>  

**video**  
<div align=center>  
  
![](https://github.com/TianQi-777/ORB-SLAM2_with_camera_or_video/blob/master/Images/video.png)
</div>
