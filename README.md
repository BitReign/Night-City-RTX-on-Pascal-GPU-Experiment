Night City - RTX on Pascal GPU Experiment
===================
![NVIDIA GTX 1070 RTX](http://sumfx.net/wp-content/uploads/2019/06/NightCity1.2763.png)

What is this?
===================

Started as an unnamed R&D project then wanted to share with anyone who owns supported Pascal GPU and want to test RTX without any leg work. It's a basic experiment with Ray Tracing features in Unreal Engine on Pascal GPU (mine was GTX 1070). As a conclusion, it has far exceeded my expectations on this GPU.

Sequencer video render:

[![VIDEO - Night City - RTX on Pascal GPU Experiment](https://i9.ytimg.com/vi/pUrHlfVZ9sQ/mqdefault.jpg?sqp=CKCL1ucF&rs=AOn4CLCdiZ-T6ywKlG95Jtc3e1qo_jnhgw&time=1559594584992)](https://www.youtube.com/watch?v=pUrHlfVZ9sQ)



Enabling DX12 and Ray Tracing
===================

Go to the main menu and use the File menu to open the Project Settings.

Under Platforms > Windows, use the Default RHI dropdown to select DX12.

![Under Platforms > Windows, use the Default RHI dropdown to select DX12.](https://docs.unrealengine.com/Images/Engine/Rendering/RayTracing/EnableDX12Mode.jpg)

Under Engine > Rendering, enable Ray Tracing.

![Under Engine > Rendering, enable Ray Tracing.](https://docs.unrealengine.com/Images/Engine/Rendering/RayTracing/ProjectSetting_EnableRT.jpg)

To enable Ray Tracing, Support Compute Skincache must be enabled for the project. If it is not already enabled, you’ll receive a message dialogue asking if you would like to enable it now. If so, click Yes.
![To enable Ray Tracing, Support Compute Skincache must be enabled for the project.](https://docs.unrealengine.com/Images/Engine/Rendering/RayTracing/SupportSkinCache.jpg)

Restart the engine to launch the Editor with DX12 and to enable Ray Tracing for your project.

Engine support
===================

Minimum Unreal Engine version is **4.22**
