# SakuraLLM-Notebooks
## 介绍
- 在colab/kaggle上运行[Sakura-13B-Galgame](https://github.com/SakuraLLM/Sakura-13B-Galgame)模型

## 模型运行情况
- transformers autogptq模型（使用v0.8版本进行测试）

|  模型量化类型 | colab (T4) | kaggle (T4×2) |
|:-------:|:-------:|:-------:|
| 全量 | ❌  | ❌  |
| 8bit | ❌ | ✔ |
| 4bit | ✔ | ✔ |
| 3bit | ✔ | ✔ |

- llama.cpp GGUF模型（使用v0.9.0pre3模型进行测试）

|  模型量化类型 | colab (T4) | kaggle (T4×2) |
|:-------:|:-------:|:-------:|
| fp16 | 未测试 | ❌ |
| Q8_0 | 未测试 | ✔ |
| Q6_K | 未测试 | ✔ |
| Q5_K_M | 未测试 | ✔ |
| Q4_K_M | 未测试 | ✔ |
| Q3_K_M | 未测试 | ✔ |
| Q2_K | 未测试 | ✔ |
## 致谢
- [SakuraLLM/Sakura-13B-Galgame](https://github.com/SakuraLLM/Sakura-13B-Galgame)
