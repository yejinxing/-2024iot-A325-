# -2024iot-A325-
火山引擎2024iot边缘推理服务的调用示例（A325实验室）

# 使用指南
安装相应环境依赖后，运行main.py文件，即可调用火山引擎边缘智能的模型推理服务对创建的MySQL服务器中的ECG数据进行诊断，若判断为心肌梗死则会将诊断信息发送到展示的web页面中。

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

# 注意事项
本项目为火山引擎边缘智能推理服务的调用示例
