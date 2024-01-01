# SakuraLLM-Notebooks
## 介绍
- 在colab/kaggle上运行[Sakura-13B-Galgame](https://github.com/SakuraLLM/Sakura-13B-Galgame)模型

## 部署教程
- **如果是初次接触[kaggle](https://www.kaggle.com/)/[ngrok](https://ngrok.com/)，请参考[Sakura-13B-Galgame](https://github.com/SakuraLLM/Sakura-13B-Galgame)的[kaggle部署教程](https://github.com/SakuraLLM/Sakura-13B-Galgame/wiki/%E7%99%BD%E5%AB%96Kaggle%E5%B9%B3%E5%8F%B0%E9%83%A8%E7%BD%B2%E6%95%99%E7%A8%8B)进行部署**

## News
- 2024-01-01: 新增[localtunnel](https://github.com/localtunnel/localtunnel)内网穿透工具（无需注册），ngrokToken留空即可启用localtunnel

## 模型运行情况
- transformers autogptq模型（使用v0.8版本进行测试）

|  模型量化类型 | colab (T4) | kaggle (T4×2) |
|:-------:|:-------:|:-------:|
| 全量 | ❌ | ❌ |
| 8bit | ❌ | ✔ |
| 4bit | ✔ | ✔ |
| 3bit | ✔ | ✔ |

- llama.cpp GGUF模型（使用v0.9.0pre3模型进行测试）

|  模型量化类型 | colab (T4) | kaggle (T4×2) |
|:-------:|:-------:|:-------:|
| fp16 | ❌ | ❌ |
| Q8_0 | ❌ | ✔ |
| Q6_K | ❌ | ✔ |
| Q5_K_M | ✔ | ✔ |
| Q4_K_M | ✔ | ✔ |
| Q3_K_M | ✔ | ✔ |
| Q2_K | ✔ | ✔ |

## 致谢
- [SakuraLLM/Sakura-13B-Galgame](https://github.com/SakuraLLM/Sakura-13B-Galgame)
