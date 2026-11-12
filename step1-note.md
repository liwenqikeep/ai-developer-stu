# Stage 1: Build A Minimal Agent Loop

- [ ] 会用一个 LLM API 完成普通对话。
- [ ] 会让模型输出结构化 JSON。
- [ ] 会定义一个工具函数，例如 search、calculator、read_file。
- [ ] 会解析模型的 tool call / function call。
- [ ] 会执行工具，并把工具结果喂回模型。
- [ ] 会给 agent loop 加最大步数、超时和错误处理。

推荐阅读：

- [OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling)
- [Gemini API Function Calling](https://ai.google.dev/gemini-api/docs/function-calling)
- [Claude Tool Use](https://docs.anthropic.com/en/docs/agents-and-tools/tool-use/overview)

产出：一个 50-150 行的最小 agent，可以选择工具、执行工具、返回最终答案。


# 结论记录

1. 函数声明，函数调用，函数调用返回，函数搜索，多个函数调用