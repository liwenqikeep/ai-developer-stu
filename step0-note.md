# Stage 0: Understand What An Agent Is


-[x] 区分 chatbot、workflow、agent、multi-agent。

-[x] 理解 agent 的基本循环：observe -> think -> act -> observe。

-[x] 明白什么时候不该用 agent：任务可预测、流程稳定、普通脚本能解决时，agent 反而增加不确定性。

-[x] 读完  [Anthropic: Building effective agents](https://www.anthropic.com/research/building-effective-agents)；[中文翻译版本](./resource/cn/index.html)


-[x] 读完 [OpenAI: A practical guide to building agents](https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/)；[中文翻译版本](./resource/cn/openai-agents-guide.html)


# 结论记录

chatbot. 一问一答
workflow. 按照固定的步骤执行，llm处于工作流的一环或几个步骤
agent. 智能体，llm自行根据工具返回自行决策停止还是继续调用其他工具
multi-agent. 多智能体，将任务拆分，多个智能体分别执行，然后聚合结果输出

观察、思考、执行、观察

