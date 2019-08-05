# Image-Restoration-Inpaint
Inpainting is the process of reconstructing lost or deteriorated parts of images and videos. It is an advanced form of interpolation that can be used to replace lost or corrupted parts of the image data.

 **cv2.inpaint**(input image, mask, inpaintRadius, Inpaint Method)
 
 **inpaintRadius** – Radius of a circular neighborhood of each point inpainted that is considered by the algorithm. Smaller values look less blurred, while larger values look more pixelated or blurred.
    
 **inpaint Methods**
    - INPAINT_NS - Navier-Stokes based method [Navier01]
    - INPAINT_TELEA - Method by Alexandru Telea [Telea04] - Better as it integrates more seamlessley into the image.
    
--------------------------------------

## How to use:
- Place the image to be restored in ```images``` folder with name ```original.jpg```
- Using ms-paint mark the regions to be restored with 255 color i.e white. (Note that threshold is kept as 254 in python script)
- Run the code and view restored image in ```images\``` with file name ```restored.jpg```
