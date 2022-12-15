# Camera transition

Camera transition is a simple solution to transition seamlessly between multiple cameras in both 2D and 3D.

## How to install

Download and place the addons under the `addons` of your project. This should look like `addons/camera_transition`.

Then add the `camera_transition.tscn` scene as an autoload. Under `Project Settings > Autoload` select the `addons/camera_transition/camera_transition.tscn` scene and use the node name CameraTransition and click **add**. 

The global variable should be enabled by default when you add it. You can now access `CameraTransition` from anywhere.

## How to use

### 2D

Call the function `CameraTransition.transition_camera2D()` with your cameras and the transition time.

`CameraTransition.transition_camera2D($Camera2D1, $Camera2D2, 3.0)` will transition from `$Camera2D1` to `$Camera2D2` in 3 seconds.

### 3D

Call the function `CameraTransition.transition_camera3D()` with your cameras and the transition time.

`CameraTransition.transition_camera2D($Camera1, $Camera2, 3.0)` will transition from `$Camera1` to `$Camera2` in 3 seconds.

## Demo

You can check the 2D & 3D demos under the **demo** folder. Run `main.tscn` to try the demo.

If you want to learn more about this technique, you can watch [the video](https://youtu.be/8Lj3pUYuVe8) I made about it.

## License

This addon is using the MIT license, for mor info read [LICENSE](LICENSE).