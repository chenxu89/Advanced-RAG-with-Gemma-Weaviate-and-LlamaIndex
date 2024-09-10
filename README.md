# Advanced-RAG-with-Gemma-Weaviate-and-LlamaIndex

# 一、项目简介
## 概述
这是我的第3个AI项目，本项目使用 LlamaIndex 与 Gemma 以及 Weaviate 向量数据库构建高级 RAG 管道

## 时间
2024.09.08-2024.09.09

## kaggle地址（代码和详细注解）
[Advanced RAG with Gemma, Weaviate, and LlamaIndex](https://www.kaggle.com/code/chenxucool/advanced-rag-with-gemma-weaviate-and-llamaindex)

## 技术博客地址
[我的第3个AI项目-Advanced RAG with Gemma, Weaviate, and LlamaIndex](https://blog.csdn.net/weixin_43221845/article/details/142004622?csdn_share_tail=%7B%22type%22:%22blog%22,%22rType%22:%22article%22,%22rId%22:%22142004622%22,%22source%22:%22weixin_43221845%22%7D)

## 主要工作和收获
- 通过自定义类使用 Gemma 模型
- 在 Weaviate 中创建和使用向量存储（VectorStore），并将其与 llama_index 一起用于管理嵌入和索引。
- 构建了一个简单的 RAG查询引擎
- 构建了一个高级的 RAG查询引擎，用到了（自动检索、混合搜索、重新排序、Few-shot 提示）等高级RAG技术
- 把 Weaviate 从V3升级到V4，修复版本兼容bug
- 熟悉了 LlamaIndex 和 Weaviate 的使用
- 了解了openai api 调用可能存在的一些问题

## 技术栈
- 高级RAG技术，LlamaIndex，Weaviate，Gemma

##  数据集
2023-kaggle-ai-report

## 结果
因为openai 的api 需要付费调用，而我觉得自己现在的需求没有付费的必要，所以高级的 RAG查询引擎的部分功能（自动检索）没有真正跑通，不过原理和代码已经懂了，留着以后条件满足了再尝试，详细解释见我技术博客bug修复部分（OpenAI api调用超出限额）。
