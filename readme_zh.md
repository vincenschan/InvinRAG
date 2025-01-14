# InvinRAG

Invincible RAG（无敌RAG）旨在构建一个智能的、进化的、面向高阶玩家的RAG，拥有完善的后端、前端、算法板块，且容易进行改造可直接应用于业务的RAG系统。 系统基于Django和LlamaIndex构建，针对LLM的接入、数据切片、检索方式等做了诸多的定制，也支持开发者自定义。

## 支持功能：

- 基于 纯文本 & 多模态 的Doc问答
1. 数据切片
2. 向量化入库: 支持数据库Minlvus, Faiss, Chroma
3. 检索: ES检索 + 向量检索
4. Reranker: 
5. 问答: 本地LLM调用, LLM api调用

- 基于Graph的问答
1. 图谱挖掘
2. 向量化入库: 支持数据库NEO4J
3. Graph检索
4. 问答: 本地LLM调用, LLM api调用

## 系统架构


