# HuiStudio

产品概述
HuiStudio 是一个面向个人及企业的多智能体协作平台，核心概念是 “AI工作室”——用户可以像组建团队一样将多个AI
Agent加入一个“工作室”，并配置它们之间的协作方式（自由讨论、主管分配或自定义流程），从而完成复杂任务。每个Agent可拥有私有知识库和工具集，既能使用系统预置能力，也能自定义扩展。
平台采取“通用平台+深度定制”的双层策略：

- 普通聊天室
- 多agent工作室
- 专业工作室（内置）
- skills角色模板、tools 市场
- 多agent工作室模板
- 自定义agent、tool 编排

技术栈：前端 React、TS、Vite，后端 Python FastAPI，LangChain、LangGraph，数据库 MySQL，缓存与消息队列 Redis，异步任务 Celery，向量检索
FAISS，对象存储 MinIO。