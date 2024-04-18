# outfit-anyone
[English](https://github.com/ihmily/outfit-anyone/blob/main/README.md)  | [简体中文](https://github.com/ihmily/outfit-anyone/blob/main/README_CN.md)

Outfit Anyone（最新修复版）：适用于任何服装和任何人的超高品质虚拟试穿



## 如何运行

**测试环境:**  **Python 3.10(ubuntu22.04 RTX 4090)**

拉取或下载代码

```
git clone https://github.com/ihmily/outfit-anyone.git
```

安装依赖

```
cd outfit-anyone
pip install -r requirements.txt
```

**设置环境变量（重点）**

```
export OA_IP_ADDRESS=https://humanaigc-outfitanyone.hf.space/--replicas/ppht9/
```

运行

```
python app.py
```

启动成功后，web服务运行在6006端口。你将看到以下类似信息

```
API: https://humanaigc-outfitanyone.hf.space/--replicas/ppht9/
Loaded as API: https://humanaigc-outfitanyone.hf.space/--replicas/ppht9/ ✔
Running on local URL:  http://127.0.0.1:6006
```

如果 `OA_IP_ADDRESS` 失效导致无法正常运行，请联系我更新 或者 访问[OutfitAnyone - a Hugging Face Space by HumanAIGC](https://huggingface.co/spaces/HumanAIGC/OutfitAnyone) 自行获取。



## 演示结果

![screenshot_image](./images/Snipaste_2024-04-18_19-06-02.jpg)

![screenshot_image](./images/Snipaste_2024-04-18_19-13-52.jpg)

![screenshot_image](./images/Snipaste_2024-04-18_19-11-35.jpg)



