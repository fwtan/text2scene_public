# [Text2Scene: Generating Compositional Scenes from Textual Descriptions ](https://arxiv.org/abs/1809.01110)
Fuwen Tan, Song Feng, Vicente Ordonez. CVPR 2019


## Overview
In this work, we propose Text2Scene, a model that generates various forms of compositional scene representations from natural language descriptions. Unlike recent works, our method does NOT use Generative Adversarial Networks (GANs). Text2Scene instead learns to sequentially generate objects and their attributes (location, size, appearance, etc) at every time step by attending to different parts of the input text and the current status of the generated scene. We show that under minor modifications, the proposed framework can handle the generation of different forms of scene representations, including cartoon-like scenes, object layouts corresponding to real images, and synthetic images. Our method is not only competitive when compared with state-of-the-art GAN-based methods using automatic metrics and superior based on human judgments but also has the advantage of producing interpretable results.


conda install scikit-image opencv seaborn nltk 

## Citing

If you find our paper/code useful, please consider citing:

	@InProceedings{text2scene2019, 
    author = {Tan, Fuwen and Feng, Song and Ordonez, Vicente},
    title = {Text2Scene: Generating Compositional Scenes from Textual Descriptions},
    booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    month = {June},
    year = {2019}
    }

    
# License

This project is licensed under the [MIT license](https://opensource.org/licenses/MIT):

Copyright (c) 2019 University of Virginia, Fuwen Tan, Song Feng, Vicente Ordonez.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.







