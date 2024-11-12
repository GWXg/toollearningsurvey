# A survy on tool-learning
# 〇，abstract

# 一，introduction
前人研究现状、不足、本文补充内容、本文结构



# 二，background

## 1.工具的定义&历史演变
[Augmented Language Models: a Survey](https://openreview.net/forum?id=jh7wH2AzKK) 工具的定义，较模糊<br>
[What Are Tools Anyway?A Survey from the Language Model Perspective](https://arxiv.org/pdf/2403.15452) 工具的定义，较清晰<br>
[Tool Learning with Large Language Models: A Survey](https://arxiv.org/abs/2405.17935) 总结工具的定义，但没有对工具的类型进行分类，文章认为单个api、搜索增强都属于工具<br>

## 2.工具学习的定义&历史演变
[ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs](https://openreview.net/forum?id=dHng2O0Jjr) LLM与工具交互、复杂任务，没有明确说明工具学习具备哪些机制<br>

推理能力（任务拆解）、上下文学习、自我调试（反馈机制）
[Awesome-Tool-LearningAugmented Language Models: a Survey](https://arxiv.org/abs/2302.07842) 模型的推理能力和学习能力<br>
https://arxiv.org/abs/2308.11432 模型的推理 action能力<br>
https://openreview.net/forum?id=jh7wH2AzKK<br>


三，工具学习的具体应用
## 1.总结工具的类型和表示方式
基于图形界面的工具、基于程序的工具
[ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs](https://openreview.net/forum?id=dHng2O0Jjr)
幻觉--获取即时更新的外部信息
增强专业知识
https://www.nowpublishers.com/article/Details/CGV-110  https://openreview.net/forum?id=yHdTscY6Ci visprog 中间提示/调用<br>
codenav 检索内容/代码<br>
https://openreview.net/forum?id=dHng2O0Jjr  https://arxiv.org/abs/2302.04761  api<br>

## 2.工具学习的使用场景/任务分类（解决哪些问题，一般用什么方法解决这些问题）
### 1）日常场景 （完成日常任务，如发邮件....）
https://proceedings.neurips.cc/paper_files/paper/2022/file/82ad13ec01f9fe44c01cb91814fd7b8c-Paper-Conference.pdf
### 2）AI领域场景（利用专家模型 单模态/多模态 专门的模型）

### 3）专业领域（化学/医疗）


# 四，工具学习的过程&策略
## 1.工具使用的分类/框架/范式/步骤
https://github.com/zorazrw/awesome-tool-llm 基本范式<br>
https://arxiv.org/abs/2405.17935 四个步骤 2个范式（是否反馈）<br>
https://arxiv.org/abs/2304.08354 四个框架 分类<br>

## 2.对模型的处理，如何生成好的响应
### 1）微调
是什么、优点、缺点、适用情况、不适用情况
### 2）上下文学习
是什么、优点、缺点、适用情况、不适用情况
### 3）tocken融入 预测工具
是什么、优点、缺点、适用情况、不适用情况
## 3.检索机制/选择机制
https://arxiv.org/pdf/2203.05115<br>
https://openreview.net/forum?id=ZTCxT2t2Ru<br>
是什么、优点、缺点、适用情况、不适用情况
## 4.反馈机制
是什么、优点、缺点、适用情况、不适用情况

# 四，工具学习的评估
https://arxiv.org/abs/2310.03128

# 五，conclusion & outlook
## 1.工具学习的发展历程（时间顺序，什么时候提出什么观点）时间轴的表

## 2.本文的观点与贡献总结回顾

## 3.未来的研究方向与问题

# 六，reference

