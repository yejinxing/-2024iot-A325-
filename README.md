# -2024iot-A325-
火山引擎2024iot边缘推理服务的调用示例（A325实验室）

# 使用指南

## 运行环境
### 方式1 ：使用官方镜像
参考 client/README.md

### 方式2 ：安装依赖

> python=3.9.18

```
pip install -r requirements.txt
```
## 运行指令

```
python client.py --image_dir=img --result_dir=res --server_url=[your_server_url] 
--server_url: 模型服务的ip地址:http端口, 如果是本机 ip 地址可以换成 localhost
--image_dir: 原始图片的文件夹
--result_dir: 输出图片的文件夹
```
