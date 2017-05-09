# convenience_store_objects

## Usage


```bash
# record
roslaunch convenience_store_objects record_object_rosbag.launch name:=<object name>

# upload the rosbag to https://drive.google.com/open?id=0B5hRAGKTOm_KOTR0a0Q2TmtjTzA

# play
roslaunch convenience_store_objects play_object_rosbag.launch rosbag:=<bag file>
```


## Sample

```bash
sudo pip install gshell
gshell download --with-id 0B9P1L--7Wd2vWTczaVdtLWJJS0k  # you need to login @jsk.imi.i.u-tokyo.ac.jp

roslaunch convenience_store_objects play_object_rosbag.launch rosbag:=$(pwd)/takenoko_no_sato_2017-05-09-21-37-12.bag
```

![](_static/sample_play_object_rosbag.gif)
