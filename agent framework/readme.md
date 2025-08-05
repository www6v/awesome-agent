



[autogen]:https://img.shields.io/github/stars/microsoft/autogen.svg?style=flat-square
[CrewAI]:https://img.shields.io/github/stars/joaomdmoura/CrewAI.svg?style=flat-square
[ChatDev]:https://img.shields.io/github/stars/OpenBMB/ChatDev.svg?style=flat-square
[GenerativeAgents]:https://img.shields.io/github/stars/joonspk-research/generative_agents.svg?style=flat-square
[BabyAGI]:https://img.shields.io/github/stars/yoheinakajima/babyagi.svg?style=flat-square
[AutoGPT]:https://img.shields.io/github/stars/Torantulino/Auto-GPT.svg?style=flat-square
[XAgent]:https://img.shields.io/github/stars/OpenBMB/XAgent.svg?style=flat-square
[MetaGPT]:https://img.shields.io/github/stars/geekan/MetaGPT.svg?style=flat-square
[ResearchGPT]:https://img.shields.io/github/stars/assafelovic/gpt-researcher.svg?style=flat-square
[AgentVerse]:https://img.shields.io/github/stars/OpenBMB/AgentVerse.svg?style=flat-square
[GPTEngineer]:https://img.shields.io/github/stars/AntonOsika/gpt-engineer.svg?style=flat-square



# Agent（General）

| Agent（General） | Type | Code | desc |
| --- | --- | --- | --- |
|**AutoGen**  paper 🔥|Multi Agent|[code](https://github.com/microsoft/autogen)![GitHub Badge][autogen]|customizable, **conversable**,  **seamlessly allow human participation** [v](https://www.bilibili.com/video/BV1DH4y1Z7Ep)|
|**MetaGPT** paper 🔥|Multi Agent-role base|[code](https://github.com/geekan/MetaGPT)![GitHub Badge][MetaGPT]|覆盖软件公司全生命流程|
|**CrewAI** 🔥|Multi Agent|[code](https://github.com/joaomdmoura/CrewAI)![GitHub Badge][CrewAI]|流程定义更灵活 [v](https://www.bilibili.com/video/BV12C4y1Y7xm)|
|**BabyAGI**|**plan and execute**|[code](https://github.com/yoheinakajima/babyagi)![GitHub Badge][BabyAGI]||
|**AutoGPT** 🔥|General|[code](https://github.com/Torantulino/Auto-GPT)![GitHub Badge][AutoGPT]||
| **LangGraph**  🔥 | flow engineering          | [code](https://github.com/langchain-ai/langgraph) | [v](https://www.bilibili.com/video/BV1VN4y1n7bt/) |
|XAgent|双循环，人可参与|[code](https://github.com/OpenBMB/XAgent)![GitHub Badge][XAgent]|autogpt，babyagi - 没法收敛，有时候会不可控<br/>metagpt，chatdev sop优化- 有一定的局限性，通用性不够好 [v](https://www.bilibili.com/video/BV1D34y1M74F)|
| Agents  paper | single agent\|multi agent | [code](https://github.com/aiwaves-cn/agents)                 | 基于SOP [v](https://www.bilibili.com/video/BV1C8411k7UL) |
| phidata |                           | [code](https://github.com/phidatahq/phidata) | Memory, knowledge and tools for LLMs |
|MiniAGI||[code](https://github.com/muellerberndt/mini-agi)|simple general-purpose autonomous agent based on the OpenAI API [v](https://www.bilibili.com/video/BV1Hh4y1k7Jz)|
|AL Legion||[code](https://github.com/eumemic/ai-legion)|An LLM-powered autonomous agent platform|


# Agent(tool/assistant) 

| Agent(tool/assistant)                                        | Type                       | Code                                                         | desc                                                     |
| ------------------------------------------------------------ | ------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **ResearchGPT** ***                                          | plan and execute               | [code](https://github.com/assafelovic/gpt-researcher)![GitHub Badge][ResearchGPT] | 融合论文拆解+网络爬虫                                        |
| WorkGPT                                                      | tools                          | [code](https://github.com/team-openpm/workgpt)               | A GPT agent framework for invoking APIs                      |
| **AgentTuning**  paper | 指令微调Agent                  | [code](https://github.com/THUDM/AgentTuning)                 | [清华] [v](https://www.bilibili.com/video/BV1E84y197Cj/) |
| **ModelScope-Agent** | tools, MSAgent-Bench 训练agent | [code](https://github.com/modelscope/modelscope-agent)       | [阿里魔塔]  [v](https://www.bilibili.com/video/BV1u34y137if) |
| open-interpreter                                             | os agent                       | [code](https://github.com/KillianLucas/open-interpreter)     | A natural language interface for computers                   |
| Qwen-Agent |                                | [code](https://github.com/QwenLM/Qwen-Agent)                 | Agent framework and applications built upon Qwen, featuring Function Calling, Code Interpreter, RAG, and Chrome extension [v](https://www.bilibili.com/video/BV1c34y1P7Yg) |
|AutoGPT-Plugins||[code](https://github.com/Significant-Gravitas/Auto-GPT-Plugins)|Auo-GPT插件|
| GPTEngineer                                                  | code  assistant | [code](https://github.com/AntonOsika/gpt-engineer)![GitHub Badge][GPTEngineer] | **自动**工具构建和代码生成                                   |
| Aider                                                        | code  assistant | [code](https://github.com/paul-gauthier/aider)               | **交互式**                                                   |

# Agent(simulation)   
| Agent(simulation)                                            | Type                | Code                                                         | desc                                                         |
| ------------------------------------------------------------ | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Hyperwriteai [website](https://www.hyperwriteai.com/personal-assistant)*** | web agent, os agent | [code](https://github.com/OthersideAI/self-operating-computer) | [v](https://www.bilibili.com/video/BV1BZ421B7ar/)            |
| **MultiON** ***                                              | web agent           |                                                              | [v](https://www.bilibili.com/video/BV1mt421W7sw/)            |
| webarena paper                                               | web agent           | [code](https://github.com/web-arena-x/webarena)              | WebArena: A Realistic Web Environment for Building Autonomous Agents  网络拟真环境，可用于自主智能体的测试，支持在线购物，论坛，代码仓库etc |
| MiniWoB++：                                                  | web agent           | [code](https://github.com/Farama-Foundation/miniwob-plusplus) | a web interaction benchmark for reinforcement learning       |
| **OpenAgents** paper***                                      | web agent           | [code](https://github.com/xlang-ai/OpenAgents)               | [港大] [v](https://www.bilibili.com/video/BV1wM41197N7/)     |
| Mobile-Agent                                                 | app agent           |                                                              | [阿里] [v](https://www.bilibili.com/video/BV1Xv42117hh/)     |
| **AppAgent**  [paper]                                        | app agent           |                                                              | [腾讯] [v](https://www.bilibili.com/video/BV1De411S7ka)      |
| CAMEL                                                        |                     | [code](https://github.com/camel-ai/camel)                    | CAMEL: Communicative Agents for “Mind” Exploration of Large Language Model Society |
| **Generative Agents**                                        |                     | [code](https://github.com/joonspk-research/generative_agents)![GitHub Badge][GenerativeAgents] | 斯坦福AI小镇                                                 |
| AgentVerse                                                   |                     | [code](https://github.com/OpenBMB/AgentVerse)![GitHub Badge][AgentVerse] | 多模型交互环境                                               |
| GPTeam                                                       | Multi Agent         | [code](https://github.com/101dotxyz/GPTeam)                  | 多智能体交互                                                 |
| **ChatDev**                                                  | Multi Agent         | [code](https://github.com/OpenBMB/ChatDev)![GitHub Badge][ChatDev] | 虚拟软件公司[面壁智能] [v](https://www.bilibili.com/video/BV1334y1T7K5/) |
| GPT PILOT                                                    |                     |                                                              | **交互式**                                                   |
| DevOpsGPT                                                    |                     |                                                              | 自动                                                         |


# Agent

| Agent                                                        | Type                       | Code                                                     | desc                                                     |
| ------------------------------------------------------------ | ------------------------------ | -------------------------------------------------------- | ------------------------------------------------------------ |
| TaskingAI | LLMOps                         | [code](https://github.com/TaskingAI/TaskingAI)           | [v](https://www.bilibili.com/video/BV1gp4y1m75S/) |
| DIFY 🔥 | LLMOps                         |                                                          | [v](https://www.bilibili.com/video/BV14V411Q7wP/) |
| **AutoGen Studio**  *** | LLMOps                         |                                                          | [v](https://www.bilibili.com/video/BV1fi4y1i7g7/) |
| L3AGI   | LLMOps                         |                                                          | [v](https://www.bilibili.com/video/BV1s94y1K7fP) |
| agenta                                                       | LLMOps | [code](https://github.com/Agenta-AI/agenta)              | The all-in-one LLM developer platform: prompt management, evaluation, human feedback, and deployment all in one place. |
| SuperAGI | LLMOps |  |  |
| N8N    | work flow                      |                                                          | [v](https://www.bilibili.com/video/BV1vT4y1h7UM/) |
| TaskWeaver |                                |                                                          | 以代码为中心[微软] [v](https://www.bilibili.com/video/BV16C4y1c7rd) |
| ProAgent | work flow                      |                                                          | [清华] [v](https://www.bilibili.com/video/BV1eu4y1b7DN) |
| Prompt flow |                                |                                                          | [微软] [v](https://www.bilibili.com/video/BV1aG411m7A4/) |
| AgentGPT | agent store, agent template    |                                                          | [v](https://www.bilibili.com/video/BV1V94y1s7uT) |
| Bisheng *                                                    |                                |                                                          | dify+flowise的结合体                                         |






# 参考

1. [awesome-ai-agents](https://github.com/www6v/awesome-ai-agents) git list
2. [DecryptPrompt](https://github.com/www6v/DecryptPrompt)  ***  git list
3. [AIGCLINK](https://space.bilibili.com/471000665/video?tid=0&pn=1&keyword=&order=pubdate) V