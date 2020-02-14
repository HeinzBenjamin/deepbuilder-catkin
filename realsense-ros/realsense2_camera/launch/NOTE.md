on jetson: rosrun nodelet nodelet standalone depth_image_proc/convert_metric image_raw:=camera/depth/image_rect_raw

on jetson: rosrun nodelet nodelet standalone depth_image_proc/point_cloud_xyz camera_info:=camera/depth/camera_info image_rect:=/image

subscribe to /points
