# Who moved my cheese? Automatic Annotation of Rodent Behaviors with Convolutional Neural Networks 
[[Project]](https://jason718.github.io/project/wacv17/project.html)   [[Paper]](https://jason718.github.io/project/wacv17/files/wacv17.pdf)

If you use this work, please cite:
```bibtex
@inproceedings{ren-wacv2017,
    title = {Who moved my cheese? Automatic Annotation of Rodent Behaviors with Convolutional Neural Networks},
    author = {Ren, Zhongzheng and Noronha, Adriana and Ciernia, Annie Vogel and Lee, Yong Jae},
    booktitle = {Winter Conference on Applications of Computer Vision (WACV)},
    year = {2017}
}
```
## Setup

### Prerequisites
- Linux
- NVIDIA GPU + CUDA CuDNN Recommended(CPU mode and CUDA without CuDNN also work)

### Getting Started
- Install [[Caffe]](http://caffe.berkeleyvision.org/)
- Install [[C3D]](https://github.com/facebook/C3D)
- Install [[pythonVideoAnnotator]](pythonVideoAnnotator)
- Clone this repo

### Dataset
Please visit this [[google drive folder]](https://drive.google.com/drive/folders/0B6lmuyb_dWMtaTVMODJwTmVNcHc?usp=sharing)

## Running

### Annotating Your videos
You can use the UI in this code to annotate your own videos. It can be used to annotate any videos with dense frame-level action labels. We also provide the tools to parse the annotations and generate txt files for caffe to use.

### Training
We fine-tune an alexnet and C3d model here. Basically, change the softmax to 5 class and fine-tune the whole networks. 

### Testing


## Contact
If you meet any trouble when using this program, fell free to contact me!

