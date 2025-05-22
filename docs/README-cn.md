[What is Liuyao/什么是六爻](./docs/Introduction-to_Liuyao.md) 
# mcp-Liuyao


## 项目简介
**mcp-Liuyao** 是一款面向所有用户的智能卜卦工具。它让你无需了解复杂的易学原理，只需提供最基本的信息，就能获得严谨、专业的卦象解读。无论你想要探寻人生方向、解决现实困惑，还是单纯体验传统文化的智慧，mcp 都会认真对待你的每一个问题。

## 使用方式
1. **在你任意的 mcp client（cursor、cline、Claude）中配置如下内容：**

   **macOS：**
   ```json
   {
       "mcpServers":{
           "liuyao":{
               "command": "npx",
               "args": ["-y", "mcp-server-liuyao"]
           }
       }
   }
   ```

   **Windows：**
   ```json
   {
       "mcpServers":{
           "liuyao":{
               "command": "cmd",
               "args": ["/c","npx","-y","mcp-server-liuyao","--studio"]
           }
       }
   }
   ```

2. **向 agent 提问，比如"今晚吃什么？"**

3. **感受神的指引**

## mcp 工具会自动为你完成：
1. 一次抛 3 个硬币，获得一爻，一共摇 6 次，称为六爻
2. 根据你的地点计算当前地点的真太阳时（这是能否算对的重要因素！）
3. 自动进行卦象解读，并给出详细回应


## 工具特点
- **简单**：只需提供问题相关的信息，无需了解背后的原理。
- **严谨**：每次起卦都结合随机性与真太阳时，保证结果认真、符合易理。
- **包容**：无论你提出什么类型的问题，mcp 都会认真对待并给出回应。


## 下一步计划
- **图片输出**：直接输出起卦的卦象图片
- **Agent 支持**：Agent as a tool
如需进一步帮助或有任何疑问，欢迎在 Issues 区留言。mcp 致力于为每一位用户带来专业、友好的卜卦体验！ 
