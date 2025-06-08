# PromptMicroTune-Revolution
把一段提示词变成“软微调”——重塑大模型定制成本与想象力的边界
<p align="center">
  <img src="https://raw.githubusercontent.com/PhantasmAI/PromptMicroTune-Revolution/main/docs/banner.png" width="620"/>
</p>

## 🌌 为什么是一次“革命”？
> 过去：微调 = 显卡 + LoRA + 数小时训练  
> 现在：**写提示词** 就能获得同级体验  
> 这就是 Prompt Micro-Tune，幻宙团队首创的“软微调范式”。

### 超越传统 Few-shot
- 不只是“让模型学格式”，而是把 **推理链、情感动机、人物阴影** 一起塞进提示词  
- 三段式（问题 / thinking / 回答）一次性解决**角色一致性**与**长程情绪张力**

### 把 Chain-of-Thought 推向创作领域
- CoT 最初为逻辑题而生，我们让它成为角色心理剧本  
- 训练时就对齐结构 → 推理时立刻吸收 → 无需改权重

### 平权：把“大模型私有化”交还给每个人
- 零显卡       → 任何设备都能跑  
- 零训练成本      → 费用≈老模型 **5.74~7.32 折**  
- 零编程门槛      → 复制模板，三步上手  
- 无限想象力      → NPC、小说角色、陪伴 AI，随手定制

---

## 🚀 一分钟快速体验
```bash
# ① 获取 Key
#    https://phapi.furina.junmatec.cn/halo

# ② 复制 system_template.jsonc 到请求的 system 区域

# ③ 发一句话
curl https://phapi.furina.junmatec.cn/v1/chat/completions \
 -H "Authorization: Bearer $KEY" \
 -d @examples/curl_demo.json
