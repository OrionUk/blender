# blender
Stuff to share related to the [Blender 3D](https://www.blender.org/)
creation suite.

## Brekel-Kinect-Face-Pro-2-Drivers-Add-On

Add-on that uses an imported BVH from [Brekel Kinect Face Pro
2](http://www.brekel.com/brekel-pro-face-2/) to create drivers to link
armature bones to mesh shape keys. Each driver maps an armature bone
rotation to a shape key value between 0.0 and 1.0.

For each driver, adds three no-op Bezier interpolation keyframes in
case interpolation control is desired.

See the video tutorial for this add-on [here](https://youtu.be/On_DF6Z8xqw).

## Brekel-Kinect-Face-Pro-2-FBX-Action-Add-On

Add-on that uses an imported FBX v7 binary from [Brekel Kinect Face
Pro 2](http://www.brekel.com/brekel-pro-face-2/) to create a Blender
action and armature similar to the kind created by Brekel Kinect Face
Pro 2 BVH export.

The action and armature created by this add-on can be used by the
aforementioned Brekel-Kinect-Face-Pro-2-Drivers-Add-On.

See the video tutorial for this add-on [here](https://youtu.be/cWoffAR-i7E).