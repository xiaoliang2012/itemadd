---
描述: 为玩家添加表情动作
---

# 💃 表情动作

{% hint style="warning" %}
版本需求：**ItemsAdder v3.0.5+** **Minecraft 1.17+**.\
该特性处于测试阶段.
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=posxlbudF8I" %}

### 主要特点

* 独立开发了为 Minecraft 玩家模型制作动画的 [Blockbench](https://www.blockbench.net/) 扩展
* 完全使用异步处理，不会造成TPS降低
* 针对大型服务器进行了优化
* 在动画中使用声音和粒子
* 显示玩家的手持装备

## 局限性

* 目前无法显示玩家的盔甲装备
* 仅使用于 Minecraft 1.17+ 
* 使用光影mod（Optifine, Iris）时会导致渲染错误, [更多详情](../../../faq/emotes-bugs/textures-broken-by-shaders-mod.md).
* 某些情况下，放置的头颅无法正常显示, [更多详情](../../../faq/emotes-bugs/placed-heads-texture-glitched.md).
