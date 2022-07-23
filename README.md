
# Jittor 赛题二



## 简介

本项目包含了第二届计图挑战赛赛题二的代码实现，可微渲染新视角生成

## 安装 
| 在GPU RTX 3090上运行

本次进行40000 epoch
 
#### 安装依赖
执行以下命令安装 依赖
```
sudo apt-get install tcl-dev tk-dev python3
git clone https://github.com/Jittor/JNeRF
cd JNeRF 
python -m pip install -r requirements.txt

cd python
python -m pip install -e .
cd ../
```

##运行
执行以下命令运行增加了todo代码的CGAN
```
python test.py --config-file ngp_comp.py
```

## 注意事项

点击项目的“设置”，在Description一栏中添加项目描述，需要包含“jittor”字样。同时在Topics中需要添加jittor。

![image-20220419164035639](https://s3.bmp.ovh/imgs/2022/04/19/6a3aa627eab5f159.png)