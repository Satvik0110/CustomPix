Features implemented
1. Make mask with help of SAM and can replace:
  (a) some object in image
  (b) background of image [taking inverse of mask]
2. Inpainting with Stable Diffusion XL
3.  Removal of unwatwed objects[works inconsistently]
4.  Style transfer[to be integrated in main pipeline]
5. Coloring SAM generated mask by specifying RGB vals using OpenCV (both foreground and background)
6. Removing background using SAM background mask to make into png
   
To be implemented:
1. Creation of objects[try strength=1]
2. Integration of SAM with gradio interface
3. Integration of style transfer and coloring feature with gradio interface
