# Paper Research Assistant Skill

一个面向 AI 论文调研的 Skill，用于帮助用户快速整理研究方向、重要论文、论文关系、阅读路线和结构化论文笔记。

## 功能特点

- 根据研究方向整理代表性论文
- 输出论文发展脉络
- 生成结构化论文阅读笔记
- 比较多篇论文的核心方法、贡献和局限
- 给出入门、进阶、拓展阅读路线
- 输出适合 Markdown / 飞书文档整理的内容
- 支持 LaTeX 公式规范化输出

## 适用场景

- 论文综述
- 研究方向入门
- 论文阅读笔记
- 论文对比分析
- AI 方向调研
- 本科生科研选题准备

## 文件说明

```text
SKILL.md      Skill 主文件
README.md    项目说明文件
examples/    示例输入与输出
````

## 安装方式

### 方式一：手动安装

1. 克隆或下载本仓库：

```bash
git clone https://github.com/dy-iy/paper-research-assistant.git
```

2. 进入项目目录：

```bash
cd paper-research-assistant
```

3. 将 `SKILL.md` 放入支持 Skill 的 Agent / OpenClaw 项目中。

4. 在 Agent / OpenClaw 中启用该 Skill 后，即可在对话中使用。

示例：

```text
帮我整理 agent tool use 方向的重要论文
```

或者：

```text
帮我分析这篇论文的创新点、方法、实验和局限
```

### 方式二：使用 npx 安装

如果你的 Agent / OpenClaw 环境支持通过 `npx skills add` 安装 Skill，可以使用以下命令：

```bash
npx skills add https://github.com/dy-iy/paper-research-assistant.git
```

如果希望跳过交互确认，可以使用：

```bash
npx skills add https://github.com/dy-iy/paper-research-assistant.git --yes
```

如果希望全局安装，可以使用：

```bash
npx skills add https://github.com/dy-iy/paper-research-assistant.git --global
```

也可以同时使用：

```bash
npx skills add https://github.com/dy-iy/paper-research-assistant.git --yes --global
```

## 使用方式

安装完成后，可以在对话中输入类似需求：

```text
帮我整理 agent tool use 方向的重要论文
```

```text
帮我做一份 diffusion model 方向的论文综述
```

```text
帮我分析这篇论文的创新点、方法、实验和局限
```

```text
帮我比较 PatchTST、iTransformer 和 TimesNet 的核心区别
```

Skill 会尽量输出结构化、适合 Markdown / 飞书文档整理的内容。

## Skill 信息

* Name: paper-research-assistant
* Version: 1.1.0
* User Invocable: true
* Allowed Tools: Read, Write, Bash

## License

MIT

