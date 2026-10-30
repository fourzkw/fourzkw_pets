# 灵伴桌宠作品集

这里收录 6 个可独立安装的桌宠形象。每个形象拥有自己的资料、预览图和 Release 附件，在桌宠市场中分别展示。

## 形象目录

| 形象 | 角色归属 | 显示版本 | 专属交互 | 包版本 |
| --- | --- | --- | --- | --- |
| [青墨龙灵](pets/jade-dragon-mage/README.md) | 独立角色 | 原图 | — | 1.0.1 |
| [云羽龙姬](pets/lingpet-chatgpt-dragon/README.md) | ChatGPT | 原图 / 像素 | 点击、摸头 | 1.0.0 |
| [白羽龙姬](pets/lingpet-chatgpt-white-dragon-h3/README.md) | ChatGPT | 原图 / 像素 | 点击、摸头 | 1.0.0 |
| [鲸鱼娘](pets/lingpet-deepseek-h3/README.md) | DeepSeek | 原图 / 像素 | 点击、摸头 | 1.0.0 |
| [橙花书姬](pets/lingpet-orange-blossom-scholar/README.md) | Claude | 原图 | — | 1.0.1 |
| [雪狐 · 冬森小火苗](pets/lingpet-snowfox-winter/README.md) | 独立角色 | 原图 | — | 1.0.0 |

所有形象均包含八种会话状态动画：待机、思考、执行工具、等待输入、等待审批、完成、异常和睡眠。点击形象名称可查看封面、外观介绍、下载链接与素材许可。

## 安装使用

1. 从 [灵伴本体 Release](https://github.com/fourzkw/lingpet/releases) 安装桌面版。
2. 打开上表中的形象介绍，下载对应的 `.petpack` 文件。
3. 在桌宠市场选择“导入本地包”，再到形象列表中选择它。也可在市场中搜索已上架的作品。

橙花书姬归属 **Claude**；云羽龙姬与白羽龙姬归属 **ChatGPT**；鲸鱼娘归属 **DeepSeek**。青墨龙灵与雪狐作为独立角色收录。

## 仓库与更新

`lingpet-index.json` 是多形象索引，`pets/<形象ID>/pet.json` 保存市场资料，`previews/cover.png` 保存各形象封面。动作资源通过 GitHub Release 的 `.petpack` 附件分发，不提交大包到 Git 历史。

市场展示资料可随仓库更新，安装动作以对应 Release 包为准。修正角色归属时，仓库资料与包内角色声明同步更新。新增或重做动作仍属于原形象，沿用原形象 ID；只有独立新形象才新增目录与索引条目。

橙花书姬 1.0.1 修正了 Claude 归属，索引引用 `orange-blossom-scholar-v1.0.1` Release；其余五个形象引用包含新说明的 `collection-v2` Release；包版本和动作资源保持不变。市场从索引指定的 Release 标签读取资料，仅修改默认分支不能刷新旧标签下的说明。

## 素材许可

各形象的素材许可见对应介绍页与 `pet.json`。灵伴本体的代码许可不自动改变这些形象素材的使用条件。
