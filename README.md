# ComfyUI-BiRefNet-Hugo

## 介绍 | Introduction

本仓库将BiRefNet最新模型封装为ComfyUI节点来使用，相较于旧模型，最新模型的抠图精度更高更好。<br>
This repository wraps the latest BiRefNet model as ComfyUI nodes. Compared to the previous model, the latest model offers higher and better matting accuracy.

## 安装 | Installation 

1. 进入节点目录, `ComfyUI/custom_nodes/`
2. `git clone https://github.com/MoonHugo/ComfyUI-BiRefNet-Hugo.git`
3. `cd ComfyUI-BiRefNet-Hugo`
4. `pip install -r requirements.txt`
___

1. Go to comfyUI custom_nodes folder, `ComfyUI/custom_nodes/`
2. `git clone https://github.com/MoonHugo/ComfyUI-BiRefNet-Hugo.git`
3. `cd ComfyUI-BiRefNet-Hugo`
4. `pip install -r requirements.txt`

## 使用 | Usage

示例工作流放置在`ComfyUI-BiRefNet-Hugo/workflow`中<br/>
The demo workflow placed in `ComfyUI-BiRefNet-Hugo/workflow`

加载模型支持两种方式，一种是自动下载远程模型并加载模型，另外一种是加载本地模型。加载本地模型的时候需要把load_local_model设置为true，并把local_model_path设置为本地模型所在路径，例如：H:\ZhengPeng7\BiRefNet<br/>
Loading the model supports two methods: one is to automatically download and load a remote model, and the other is to load a local model. When loading a local model, you need to set 'load_local_model' to true and 'local_model_path' to the path where the local model is located, for example: H:\ZhengPeng7\BiRefNet.

![](./assets/e21c32bf-ab98-444a-8055-54975ac47da3.png)

模型下载地址：https://huggingface.co/ZhengPeng7/BiRefNet/tree/main<br/>
Model download address: https://huggingface.co/ZhengPeng7/BiRefNet/tree/main


___
工作流workflow.json的使用<br/>
The use of workflow.json

![plot](./assets/d0a22b2a-ceb3-4205-9b4e-f6a68e4337c7.png)

工作流video_workflow.json的使用<br/>
The use of video_workflow.json
___
![plot](./assets/2de5b085-1125-46f9-8ef3-06706743f182.png)

## 效果演示 | Sample Result

![](./assets/demo1.gif)

![](./assets/demo2.gif)

![](./assets/demo3.gif)

![](./assets/demo4.gif)

## 社交账号 | Social Account Homepage
- Bilibili：[我的B站主页](https://space.bilibili.com/1303099255)

## 感谢 | Acknowledgments

感谢BiRefNet仓库的所有作者 [ZhengPeng7/BiRefNet](https://github.com/zhengpeng7/birefnet)

Thanks to BiRefNet repo owner [ZhengPeng7/BiRefNet](https://github.com/zhengpeng7/birefnet)

部分代码参考了 [ZHO-ZHO-ZHO/ComfyUI-BiRefNet-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI-BiRefNet-ZHO) 感谢！

Some of the code references [ZHO-ZHO-ZHO/ComfyUI-BiRefNet-ZHO](https://github.com/ZHO-ZHO-ZHO/ComfyUI-BiRefNet-ZHO) Thanks!

## 关注历史 | star history

[![Star History Chart](https://api.star-history.com/svg?repos=MoonHugo/ComfyUI-BiRefNet-Hugo&type=Date)](https://star-history.com/#MoonHugo/ComfyUI-BiRefNet-Hugo&Date)