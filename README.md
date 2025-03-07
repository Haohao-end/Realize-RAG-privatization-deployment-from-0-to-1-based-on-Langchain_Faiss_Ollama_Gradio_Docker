# 📚 PDF智能问答助手 🤖

欢迎来到 **PDF智能问答助手** 的奇妙世界！这是一个基于 **RAG（检索增强生成）** 技术的超级工具，让你能上传PDF文件，然后像跟老朋友聊天一样跟它互动！😎 不管你是学生👩‍🎓、职场大佬👨‍💼，还是研究狂人🔬，这个助手都能帮你从PDF里挖出金子，省去翻页找答案的苦恼！

---

## 🚀 项目简介

**PDF智能问答助手** 是一个让你惊呼“哇塞”的工具！它结合了超强大脑（大型语言模型）和闪电般的文档检索技术，核心功能有：

- 📄 上传任何PDF文件（是的，随便扔进来！）
- 💬 问啥答啥，答案直接从文档里掏出来
- 🔄 支持多轮对话，聊得再久也不会懵

简单来说，它就是你的私人文档小秘书，随时待命，绝不摸鱼！😊

---

## 🌟 超酷功能

- **PDF魔法处理** 📂  
  - 随便丢个PDF进来，它会自动切成小块，方便检索。
  - 用 **FAISS** 向量数据库存起来，查找快到飞起！✈️

- **智能问答大师** 💡  
  - **普通模式**：没PDF时，它就是个万能聊天机器人。
  - **文档模式**：有了PDF，回答精准到像读了全文一样！
  - 多轮对话还能记住前因后果，聪明得像个小天才！🧠

- **炫酷界面** 🖥️  
  - 拖拽上传PDF，操作简单到奶奶都会用！👵
  - 实时对话，清空、重来随你挑，体验丝滑无比。

---

## 🛠️ 快速上手指南

### 1. 准备环境

先弄个小窝给它住：

```bash
conda create --name rag python=3.12
conda activate rag
```

然后给它装上装备：

```bash
pip install langchain faiss-cpu gradio PyMuPDF
pip install -U langchain-community
```

别忘了请来大神 **ollama** 和它的法宝 **deepseek-r1**：

```bash
ollama pull deepseek-r1
```

### 2. 启动冒险

跳到项目目录，敲下这行咒语：

```bash
python RAG.py  
```

### 3. 打开传送门

浏览器输入 `http://127.0.0.1:8888`，迎接你的智能助手吧！🌐

### 4. 开始玩耍

- 把PDF拖进上传框（就像扔垃圾一样简单！🗑️）
- 在聊天框里问问题，点“发送”。
- 坐等助手献上的智慧果实！🍎

---

## 🎨 小试牛刀

假设你丢了一本机器学习的PDF📘，可以这么玩：

- **你**：监督学习是啥？  
  **助手**：监督学习就是让机器通过“带答案的练习题”学会预测，比如教它分辨猫狗！🐱🐶

- **你**：举个例子呗？  
  **助手**：当然！比如垃圾邮件过滤，训练它认出“垃圾”和“非垃圾”，新邮件来了它就能秒判！✉️

答案直接从PDF里捞出来，靠谱到不行！🔍

---

## 🤝 一起搞乱（划掉）搞好

我们超欢迎你加入！有想法💡或者发现bug🐞，随时：

- 扔个Issue 📝
- 甩个Pull Request 🔄

一起把这个项目变成GitHub上的明星吧！⭐

---

## 📜 许可证

本项目用的是 [MIT许可证](LICENSE) 🔓，随便用、随便改，只要开心就好！

---

## 🎉 尾声

感谢你点开 **PDF智能问答助手**！希望它能成为你的学习工作小帮手。如果有啥问题或建议，随时喊我们一声。😊

**现在，上传你的PDF，开始这场智能冒险吧！** 🚀

--- 
