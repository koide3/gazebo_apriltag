# gazebo_apriltag

<img src="ss.png" width="712pix" />

Install models:
```bash
cp -R gazebo_apriltag/models/* ~/.gazebo/models/
```

Generate additional tag models:
```bash
# Edit the following lines in generate.py to create tag models you want
# 45:	for i in range(16):
# 46:		generator.generate('apriltag-imgs/tag36h11', 'tag36_11_%05d' % i, tag_size)
```