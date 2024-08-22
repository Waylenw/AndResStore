# Surface
## lockHardwareCanvas

### HwuiContext
- HardwareRenderer
   - setSurface
   - unlockAndPost
- RecordingCanvas
- RenderNode

## C++部分

### frameworks/base/libs/hwui/jni/android_graphics_HardwareRenderer.cpp
- RenderProxy

### frameworks/base/libs/hwui/renderthread/RenderProxy.cpp
- setSurface
- syncAndDrawFrame
  - mDrawFrameTask.drawFrame()
  - DrawFrameTask::run()
 
###  frameworks/base/libs/hwui/renderthread/CanvasContext.h
- 

### frameworks/base/libs/hwui/renderthread/DrawFrameTask.cpp
-   mDrawFrameTask.setContext(&mRenderThread, mContext, rootRenderNode);

