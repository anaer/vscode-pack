# README

笔记扩展包

## 编辑相关

- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - Markdown 工具

## 编程相关

- [httpYac - Rest Client](https://marketplace.visualstudio.com/items?itemName=anweber.vscode-httpyac)
  - Http API测试工具 功能相比Rest Client多一点

- [REST Formatter](https://marketplace.visualstudio.com/items?itemName=ShinyaSuzuki.rest-formatter)
  - http/rest文件格式化, 配合Rest Client使用

## 其他

- [VSCode Base Pack](https://marketplace.visualstudio.com/items?itemName=anaer.vscode-base-pack)
  - 包含常用的一些扩展

<details>
<summary> 待定 </summary>

- [Dyno File Utils](https://marketplace.visualstudio.com/items?itemName=dyno-nguyen.vscode-dynofileutils)
  - 文件操作工具
- [Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete)
  - 路径补全
- [Paste Image](https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image)
  - Markdown 贴图
- [Auto Header](https://marketplace.visualstudio.com/items?itemName=anaer.vscode-auto-header)
  - 自动更新文件头
- [Foam](https://marketplace.visualstudio.com/items?itemName=foam.foam-vscode)
  - Markdown Tag展示工具
- [markdown-tags](https://marketplace.visualstudio.com/items?itemName=SimVet.markdown-tags)
  - markdown 标签
- [Terminal Code Runner](https://marketplace.visualstudio.com/items?itemName=zardoy.terminal-code-runner)
  - 终端代码执行
- [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)
  - 类似 PostMan, 大于 v2.6.2 版本的Git Sync为付费订阅功能
- [Markdown Link Updater](https://marketplace.visualstudio.com/items?itemName=mathiassoeholm.markdown-link-updater)
  - 调整文档路径时, 自动更新图片链接, 很方便
- [GitDoc](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gitdoc)
  - 自动同步Git, 免除手动提交操作
- [markdown-memo](https://marketplace.visualstudio.com/items?itemName=svsool.markdown-memo)
  - 替换foam, 支持wikilink
- [vscode-httpyac](https://marketplace.visualstudio.com/items?itemName=anweber.vscode-httpyac)
  - 兼容rest client, 舒适度差点
- [Codeiume](https://marketplace.visualstudio.com/items?itemName=codeium.codeium)
  - 代码补全, 新版体验好点, 直接放base包中
- [vscode-drawio](https://marketplace.visualstudio.com/items?itemName=eightHundreds.vscode-drawio)
  - 集成 drawio 画流程图
- [Rest Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
  - Http API测试工具

</details>

[扩展图标]: https://www.iconfinder.com/icons/1519778/book_colorful_notebook_office_school_icon

打包命令备忘:

```sh
nvm use 22.11.0 && vsce publish
```