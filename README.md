# H5 UI 分层展示 Skill

把已有的 H5 / 移动端 Figma 页面整理为可编辑的作品集分层展示。Skill 会先读取原画板，再按内容关系处理纵向倾斜、玻璃层级、渐隐和引线标注，并用“视觉表达 / 体验价值”解释每一层。

## 作品示例

以下图片从当前 Figma 展示画板导出，展示 Skill 所针对的排版方式。图片是静态参考，不包含可编辑 Figma 源文件。

| 中秋活动弹窗 | 中秋主会场 | 万圣节兑换区 |
| --- | --- | --- |
| <img src="examples/01-mid-autumn-popup.png" alt="中秋活动弹窗 UI 分层展示" width="250"> | <img src="examples/02-mid-autumn-main-venue.png" alt="中秋主会场 UI 分层展示" width="250"> | <img src="examples/03-halloween-redemption.png" alt="万圣节兑换区 UI 分层展示" width="250"> |

## 安装

在支持 Skill 安装器的 Codex 中，可使用：

    $skill-installer install https://github.com/havero896/h5-ui-layered-showcase/tree/main/skills/h5-ui-layered-showcase

也可以将 [Skill 文件夹](skills/h5-ui-layered-showcase/)整体放入所用 Agent 的 Skills 目录。其他平台的安装路径请以其当前文档为准。

## 使用

示例提示词：

> 使用 $h5-ui-layered-showcase，把我当前 Figma 的「原画板名称」做成旁边一张可编辑的作品集分层展示。原画板不动；参考我附的图，但保留原页面文案和内部布局。请检查倾斜方向、按钮文字、渐隐边界、折线圆点和字体。

最好提供可编辑的 Figma 原画板、编辑权限、参考图和项目说明。只有单张截图时，Skill 会先说明哪些部分缺少可编辑源素材；它不能凭截图恢复原生图层。

## 文件与许可

- [Skill 入口](skills/h5-ui-layered-showcase/SKILL.md)及其配套文件采用 [MIT 许可](skills/h5-ui-layered-showcase/LICENSE)。
- [作品示例图](examples/)仅供查看展示，**不在 MIT 许可范围内**；详见 [图片使用说明](examples/RIGHTS.md)。

Skill 是设计工作流程，不是可直接运行的 H5 网页，也不包含上述案例的 Figma 源文件。
