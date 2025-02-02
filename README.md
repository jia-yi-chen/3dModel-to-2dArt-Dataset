# 3dModel-to-2dArt Dataset

Created by [Jiayi Chen](https://github.com/jia-yi-chen) in June 2017

 Drawing Art is a natural ability of human beings. Artists are even more well-trained on this skill. We believe that machines can be trained to have this ablity. According to the real-world drawing process, some artists create artworks based on observing the 3d physical world, i.e., all of strokes, usage of colors, textures and drawing styles are strongly related to 3d structures of the scene and lighting conditions on each object. Different from "image style transfer" which transfer a real photo into an artistic image, we studies the problem "Painterly rendering for 3d Model or 3d Scene" or "Artistic Image Generetion for 3D Models", directly generating an artistic image given a 3d object and an artwork example. 

  This is a small dataset for studying the "Painterly rendering for 3d Models" problem, focusing on the importance of 3d object's lighting conditions for painting generation.

 ![image](https://github.com/jia-yi-chen/3dModel-to-2dArt-Dataset/blob/master/dataset_intro/3.jpg)

This dataset was created in order to reproduce that in this paper:

Fišer, Jakub, Ondřej Jamriška, Michal Lukáč, Eli Shechtman, Paul Asente, Jingwan Lu, and Daniel Sýkora. **StyLit: illumination-guided example-based stylization of 3D renderings**. ACM Transactions on Graphics (TOG), 2016. [paper](https://dl.acm.org/citation.cfm?id=2925948)

## Dataset Introduction 

This dataset includes three types of data:
* Painting examples in different artistic styles for a 3d sphere. Currently, it only contains one painting created by using the computer drawing tool [CorelPainter](https://www.painterartist.com/en/product/painter/?sourceid=ptr2020-xx-ppc_brkws&x-vehicle=ppc_brkws&gclid=EAIaIQobChMInrG05eLl5AIVzw0rCh1_jwf1EAAYASAAEgK-avD_BwE) and imitating a painting example in [StyLit](https://dl.acm.org/citation.cfm?id=2925948).
* The source file (.max) of 3D Models. The models are created by using the 3D modeling and rendering software [Autodesk 3dMax](https://www.autodesk.com/products/3ds-max/overview). All objects are in the same file.
* Each 3d object also includes six images. Each image represents a type of illumination. These images are outputs of the photorealistic rendering tool NVIDIA Iray SDK.

### Examples
Here is a summary for this dataset. If you need original files to help your research, please contact me.
 ![image](https://github.com/jia-yi-chen/3dModel-to-2dArt-Dataset/blob/master/dataset_intro/1.jpg)
 ![image](https://github.com/jia-yi-chen/3dModel-to-2dArt-Dataset/blob/master/dataset_intro/2.jpg)

## Authors

Jiayi Chen
