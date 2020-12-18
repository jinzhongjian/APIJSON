# Contributing

我们提倡您通过提 Issue 和 Pull Request 方式来促进 APIJSON 的发展。


## Acknowledgements

非常感谢以下几位贡献者对于 APIJSON 的做出的贡献：

- [ruoranw](https://github.com/ruoranw)
- [zhoulingfengofcd](https://github.com/zhoulingfengofcd)
- [Zerounary](https://github.com/Zerounary)
- [vincentCheng](https://github.com/vincentCheng)
- [justinfengchen](https://github.com/justinfengchen)
- [linlwqq](https://github.com/linlwqq)
- [redcatmiss](https://github.com/redcatmiss)
- [linbren](https://github.com/linbren)
- [jinzhongjian](https://github.com/jinzhongjian)
- [CoolGeo2016](https://github.com/CoolGeo2016)
- [1906522096](https://github.com/1906522096)

其中特别致谢: <br/>
justinfengchen 提交的 6 个 Commits, 对 APIJSON 做出了 3,130 增加和 0 处删减(截止 2020/11/04 日)； <br/>
ruoranw 提交的 18 个 Commits, 对 APIJSON 做出了 328 增加和 520 处删减(截止 2020/11/04 日)； <br/>
Zerounary 提交的 6 个 Commits, 对 APIJSON 做出了 1,104 增加和 1 处删减(截止 2020/11/04 日)。 <br/>

<br/>
APIJSON 持续招募贡献者，即使是在 Issue 中回答问题，或者做一些简单的 Bug Fix ，也会给 APIJSON 带来很大的帮助。 <br/>
APIJSON 已开发近 4 年，在此感谢所有开发者对于 APIJSON 的喜欢和支持，希望你能够成为 APIJSON 的核心贡献者， <br/>
加入 APIJSON ，共同打造一个更棒的自动化 ORM 库！🍾🎉

​                       

## Issue 提交

#### 对于贡献者

在提 Issue 前请确保满足一下条件：

- 必须是一个 Bug 或者功能新增。
- 必须是 APIJSON 相关问题。
- 已经在 Issue 中搜索过，并且没有找到相似的 Issue 或者解决方案。
- 完善下面模板中的信息

如果已经满足以上条件，我们提供了 Issue 的标准模版，请按照模板填写。

​             

##  Pull Request

我们除了希望听到您的反馈和建议外，我们也希望您接受代码形式的直接帮助，对我们的 GitHub 发出 Pull Request 请求。

以下是具体步骤：

#### Fork 仓库

点击 `Fork` 按钮，将需要参与的项目仓库 Fork 到自己的 Github 中。

#### Clone 已 Fork 项目

在自己的 Github 中，找到 Fork 下来的项目，git clone 到本地。

```bash
$ git clone git@github.com:<yourname>/APIJSON.git
```

#### 添加 APIJSON 仓库

将 Fork 源仓库连接到本地仓库：

```bash
$ git remote add <name> <url>
# 例如：
$ git remote add APIJSON git@github.com:Tencent/APIJSON.git
```

#### 保持与 APIJSON 仓库的同步

更新上游仓库：

```bash
$ git pull --rebase <name> <branch>
# 等同于以下两条命令
$ git fetch <name> <branch>
$ git rebase <name>/<branch>
```

#### Commit 信息提交

Commit 信息请遵循 [Commit 消息约定](./CONTRIBUTING_COMMIT.md)，以便可以自动生成 `CHANGELOG` 。具体格式请参考 Commit 文档规范。
