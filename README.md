# Scene-Rendering
A standalone OpenGL viewer for rendering virtual spheres with lighting provided from an hdr image using image based lighting (IBL).

Created for the [IBL project](https://github.com/zhiyuXiao1221/ImageBasedLight) as a way to integrate rendering into the pipeline of image based light processing. Previous methods of rendering makes use of Autodesk's Maya software for a manually crafted scene for compositing virtual object into real life image.

![Sample render](/images/sample_render.png)

After virtual objects are rendered, compositing (inserting virtual objects into real scene) takes four images to create the final result; original scene, virtual objects rendered on plane, plane without virtual objects, and mask of virtual objects.
| | | 
|:-------------------------:|:-------------------------:|
|<img width="400" src="/images/scene.png"> | <img width="400" src="/images/mask.png"> | 
|<img width="400" src="/images/withObjects.png"> | <img width="400" src="/images/withoutObjects.png">  | 
| | |
