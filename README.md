<img width="2508" height="1224" alt="ppt生成" src="https://github.com/user-attachments/assets/b76ffa7c-22fb-4555-ba47-78102fde53ac" />
**AI Agent 平台** — 文件问答、深度研究与 PPT 自动生成的智能工作台

---

## 简介

XiaoYe-Agent 是我独立开发的 AI Agent 平台，集成文件问答、深度研究和 PPT 自动生成能力。  
平台支持自然语言任务输入、工具调用、任务状态管理和流式交互，能够处理复杂任务、生成结构化结果，并支持任务中断与恢复。

---

## 核心功能

1. **文件问答**
   - 支持文档上传和检索（PDF、Word、TXT、图片等）
   - 使用 RAG 技术结合向量检索生成智能回答
   - SSE 流式输出回答，支持任务中途停止

2. **深度研究**
   - 复杂问题拆解为多阶段计划
   - 并行/串行任务执行
   - 自动结果评估与反馈循环
   - 上下文压缩支持长期任务

3. **PPT 自动生成**
   - 状态机驱动生成流程：需求 -> 搜索 -> 模板 -> 大纲 -> Schema -> 渲染
   - 支持创建、修改与恢复
   - 可生成结构化 PPT，支持快速汇报与展示

<img width="2526" height="1239" alt="首页" src="https://github.com/user-attachments/assets/50da3a71-a17a-4382-a748-96560f8d6874" />
