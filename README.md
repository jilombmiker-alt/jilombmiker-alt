<p align="center">
  <img src="./assets/profile-signal-header.svg" width="100%" alt="Jilomb Miker，AI 产品独立开发者。公开作品覆盖产品验收、产品拆解、桌面助手、表达训练、演示生成与英语教培。" />
</p>

<p align="center">
  <a href="https://github.com/jilombmiker-alt?tab=repositories"><strong>查看全部公开仓库</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:jilombmiker@gmail.com"><strong>联系我</strong></a>
</p>

## 这里有什么

这是我的 AI 产品公开作品入口。我独立完成需求判断、交互设计、开发、评测和发布，并把可以公开验证的演示、源码、测试与边界留在 GitHub。

你可以在这里直接体验网页产品、下载 macOS 应用、安装 Codex Skill，也可以查看两个可运行的学习产品原型。下面先展示 6 个代表项目，后面列出其余 7 个公开项目。

| 公开内容 | 对应项目 | 打开后能做什么 |
| --- | --- | --- |
| 可直接体验或下载 | 验收助手、Handy | 运行在线演示，或下载 macOS 测试版 |
| 可安装到 Codex | 产品拆解、SceneDeck | 复用产品拆解方法，或生成可编辑 PPTX |
| 可在本地运行 | 表达训练器、英语教培 AI 产品 | 查看完整产品流程、源码、测试与当前边界 |

## 可以直接体验或下载

<a href="https://github.com/jilombmiker-alt/acceptance-assistant"><img src="./assets/project-acceptance-assistant.svg" width="100%" alt="验收助手，给独立开发者和小团队使用的网页产品检查与复检工具。" /></a>

### [验收助手](https://github.com/jilombmiker-alt/acceptance-assistant)

**给独立开发者和小团队使用的网页产品检查与复检工具。** 提供检查目标和网页项目后，它会执行支持的页面路径，记录问题位置、触发操作、预期结果和实际差异；修复后可按原标准重新检查。

[在线体验](https://modelscope.cn/studios/mlhx0808/acceptance-assistant) · [查看源码与说明](https://github.com/jilombmiker-alt/acceptance-assistant)

- **进入仓库可看** 在线演示、脱敏报告、受控修复对比、源码和本地接入指南。
- **当前边界** 在线版运行固定案例；自己的网页项目需要在本机接入，任意业务与主观质量仍需专门验收。
- **仓库名** `acceptance-assistant`

<br />

<a href="https://github.com/jilombmiker-alt/Handy"><img src="./assets/project-handy.svg" width="100%" alt="Handy，用快捷键唤出的 macOS 本地语音行动助手。" /></a>

### [Handy · macOS 语音行动助手](https://github.com/jilombmiker-alt/Handy)

**用快捷键唤出的 macOS 本地桌面助手。** 说出目的或粘贴内容后，可以完成快捷记录、继续笔记、待办安排、会议整理、录音转写、计时和剪贴板操作，并逐步核对执行结果。

[下载 0.1.0 测试版](https://github.com/jilombmiker-alt/Handy/releases/tag/v0.1.0) · [查看使用说明](https://github.com/jilombmiker-alt/Handy/blob/main/docs/USER-GUIDE.md) · [查看源码](https://github.com/jilombmiker-alt/Handy)

- **进入仓库可看** Apple Silicon 测试版下载、完整使用说明、界面与权限边界、源码和构建方法。
- **当前边界** 0.1.0 测试版；通用 Computer Use 尚未接入，邮件只读，语音和第三方软件兼容性需按本机环境验收。
- **仓库名** `Handy`

## 可以安装到 Codex

<a href="https://github.com/jilombmiker-alt/product-lens"><img src="./assets/project-product-lens.svg" width="100%" alt="产品拆解，把真实产品体验转成证据、方案和 PRD 的 Codex Skill。" /></a>

### [产品拆解](https://github.com/jilombmiker-alt/product-lens)

**把真实产品体验转成证据、方案和 PRD 的 Codex Skill。** 它沿着用户实际操作记录事实与未知，再判断哪些机制值得借鉴，随后形成 Agent、工具、数据和工作流方案。

[查看安装方法](https://github.com/jilombmiker-alt/product-lens#在codex中安装) · [阅读教学示例](https://github.com/jilombmiker-alt/product-lens/blob/main/docs/customer-support-example.md) · [查看 Skill 源码](https://github.com/jilombmiker-alt/product-lens/tree/main/skills/product-lens)

- **进入仓库可看** 五步工作流、安装方法、客服示例、任务模板、40 项合成交接协议测试和完整 Skill 源码。
- **适合使用** 产品经理、独立开发者，以及需要把竞品研究继续推进到方案和实现的团队。
- **仓库名** `product-lens`

<br />

<a href="https://github.com/jilombmiker-alt/scenedeck-ppt"><img src="./assets/project-scenedeck.svg" width="100%" alt="SceneDeck，把想法、笔记或资料变成可编辑 PowerPoint 的 Codex Skill。" /></a>

### [SceneDeck · 演示生成 Skill](https://github.com/jilombmiker-alt/scenedeck-ppt)

**把想法、笔记或源文件变成面向特定受众的可编辑 PowerPoint。** 它先明确汇报对象和决策任务，再组织有证据边界的页面计划，生成 PPTX，并逐页渲染检查。

[查看安装方法](https://github.com/jilombmiker-alt/scenedeck-ppt#install) · [查看生成规则](https://github.com/jilombmiker-alt/scenedeck-ppt#what-it-enforces) · [查看源码](https://github.com/jilombmiker-alt/scenedeck-ppt)

- **进入仓库可看** 1.0.0 安装方法、调用示例、生成规则、验证脚本和 Skill 源码。
- **适合使用** 产品提案、业务复盘、销售方案、融资材料、教学演示和专业报告。
- **仓库名** `scenedeck-ppt`

## 可以本地运行的产品原型

<a href="https://github.com/jilombmiker-alt/expression-trainer"><img src="./assets/project-expression-trainer.svg" width="100%" alt="表达训练器，用两轮阅读转述、语音证据和反馈训练中文表达。" /></a>

### [表达训练器](https://github.com/jilombmiker-alt/expression-trainer)

**帮助用户练习中文转述和快速总结的 Web 与 Android 产品原型。** 一份资料会被拆成两轮“阅读、转述、反馈”练习；系统保留语音证据，指出口头习惯、中心信息和下一轮训练重点。

[查看本地启动方法](https://github.com/jilombmiker-alt/expression-trainer#快速启动) · [查看产品架构](https://github.com/jilombmiker-alt/expression-trainer#技术架构) · [查看源码](https://github.com/jilombmiker-alt/expression-trainer)

- **进入仓库可看** 完整训练流程、浏览器与 Android 代码、BYOK 多模型接入、数据与隐私契约，以及 134 项前后端测试。
- **当前边界** 模型与语音服务需要使用者自行配置；自动化测试不等于全部真机、麦克风权限和生产部署已经验收。
- **仓库名** `expression-trainer`

<br />

<a href="https://github.com/jilombmiker-alt/star-ai-english-buddy-h5"><img src="./assets/project-star-english.svg" width="100%" alt="英语教培 AI 产品，面向儿童的英语语音陪伴与学习关卡 H5 原型。" /></a>

### [英语教培 AI 产品](https://github.com/jilombmiker-alt/star-ai-english-buddy-h5)

**面向儿童的英语语音陪伴与关卡学习 H5 原型。** 孩子可以进行中英文语音对话，完成朗读、单词、情景演绎和综合挑战；系统按真实任务结果解锁关卡并生成成长记录。

[查看本地启动方法](https://github.com/jilombmiker-alt/star-ai-english-buddy-h5#启动) · [查看已实现功能](https://github.com/jilombmiker-alt/star-ai-english-buddy-h5#已实现) · [查看源码](https://github.com/jilombmiker-alt/star-ai-english-buddy-h5)

- **进入仓库可看** 单页 H5 产品、学习任务与关卡逻辑、主备模型配置、语音交互、成长报告、测试和数据边界。
- **当前边界** 当前为单机单档案，本地运行；尚未实现多儿童、云同步和完整 82 节点地图迁移。
- **仓库名** `star-ai-english-buddy-h5`

## 其他公开项目

下面这些项目仍然公开，只是没有放进前面的 6 个代表项目中。

| 项目 | 主要内容 | 当前形态 |
| --- | --- | --- |
| [Veriscribe Web](https://github.com/jilombmiker-alt/veriscribe-web) | 把语音或原始文字整理成准确、清楚、可直接使用的文本，支持改口理解与多语翻译 | 有公开网页测试版 |
| [Mirror V0.3.1](https://github.com/jilombmiker-alt/mirror-v03) | 面向 18 至 24 岁邀请测试用户的关系体验研究原型，包含语音输入、场景生成与证据化报告 | 有在线体验与 Android 包 |
| [星星 AI 英语伙伴线上版](https://github.com/jilombmiker-alt/star-ai-english-buddy) | 面向 6 至 12 岁儿童的语音优先英语学习网站，包含开放域对话、课程任务与七级地图 | 妙搭线上版本 |
| [AI 产品经理工作流 Skills](https://github.com/jilombmiker-alt/work-skill) | 竞品证据研究与 PRD 决策审查两个可安装 Skill | 公开 Skill 源码 |
| [中文写作 Skill](https://github.com/jilombmiker-alt/human-writing-skill) | 中文写作与改稿 Skill 的公开源码 | 当前缺少仓库 README |
| [无相山海：邪潮](https://github.com/jilombmiker-alt/wuxiang-shanhai) | 东方神怪题材的离线 2D 像素肉鸽 RPG，公开最新源码快照与 Web 构建 | 开发候选版本 |
| [末日方舟](https://github.com/jilombmiker-alt/doomsday-ark-design) | 独立物资、AI 幸存者、交易关系与剧情选择构成的末日回合生存游戏设计 | 仅公开设计文档 |

<p align="center">
  <img src="./assets/product-method.svg" width="100%" alt="我的产品方法：发现真实问题，构建可用产品，验证任务与边界，发布公开证据。" />
</p>

<p align="center">
  <strong>Build the product. Test the boundary. Leave the proof.</strong>
</p>
