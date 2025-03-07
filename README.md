# VGG_Plant_Seedlings_Classification
在 **mmastererliu** 作者的 **vggmast** 项目上增加了点内容，https://github.com/mmastererliu/vggmast

## 简介
基于 OnethingAI 云平台完成的大数据课程作业。
- **邮箱**: pzy261228@gmail.com
## 环境配置
- **PyTorch 版本**: 2.3.1
- **Python 版本**: 3.10
- **操作系统**: Ubuntu 22.04
- **CUDA 版本**: 12.1.1

## 硬件配置
- **CPU**: 16 核
- **内存**: 64G
- **GPU**: NVIDIA RTX 4090 24G 
## 流程
- 运行 txt.py 对 train 文件夹下的数据集生成标签文件
- 修改 main.py 中的 epoch batchsize 等参数后运行等待生成 bestmodel.pth 、损失函数和精度图，存放在根目录
- 运行 evaluate.py 对模型进行评估，生成 mAP 曲线、混淆矩阵图、个分类指标，存放在新生成的 evaluation 文件夹
- 运行 predict.py 对test文件夹下的图片进行识别，结果图存放在新生成的 predict 文件夹
- model 文件夹放的是预训练模型权重
## 结果
![Image](https://github.com/user-attachments/assets/48493778-525e-421f-9d60-0292d3d5bf6e)
![Image](https://github.com/user-attachments/assets/de27d758-8c92-4bc6-a038-f5ec39c791a8)
![Image](https://github.com/user-attachments/assets/786bdb69-dd87-445f-bbca-393a1fb68c79)
![Image](https://github.com/user-attachments/assets/73717364-b604-4440-a8db-58d0f448ae9a)
![Image](https://github.com/user-attachments/assets/c48a0e9a-72dc-4d49-9529-11ad6caffac7)
![Image](https://github.com/user-attachments/assets/dafc576d-8546-45fe-8c37-3b57d62e0abb)
![Image](https://github.com/user-attachments/assets/ca0c34ac-fac6-4416-ae75-083ff7df536f)
![Image](https://github.com/user-attachments/assets/f866f256-8066-4016-84c6-8200680e66cd)
![Image](https://github.com/user-attachments/assets/b743d51e-e587-4874-80c6-eb26d72f1776)
![Image](https://github.com/user-attachments/assets/8fb5c06b-17c6-42c3-8e8c-b6d8f595165d)
![Image](https://github.com/user-attachments/assets/4ae21cc2-a393-44ae-91a2-aa165259c961)
![Image](https://github.com/user-attachments/assets/1d9ac159-2e5a-482d-bc19-995c2aa8a3fb)
![Image](https://github.com/user-attachments/assets/48a79355-b847-48da-8152-b78b4647d258)
![Image](https://github.com/user-attachments/assets/d2749e9b-32ad-457e-8aea-6e5a92867995)
![Image](https://github.com/user-attachments/assets/b25e1392-2c94-43ba-9fc3-aaf3c8228f1e)

