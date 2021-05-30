# rosbag_tutorial

### preparation
```XML
sudo apt install ffmpeg
sudo apt-get install ubuntu-restricted-extras
```
### Ensure the topic is allowable before recording it
### type following code
```XML
rosbag record desired_topic_name
```
### Use rosbag2video.py to convert bag file to mp4 files (this py files only allow to convert rgb frame)
### Remeber to put the python files and bag files into same directory
### type following code
```XML
python rosbag2video.py bag_file_name
```
