# fabric-doc-cn

## 项目介绍

* 这是Hyperledger fabric 官方文档的民间汉化版。 

* 基于Hyperledger fabric V1.0版本中doc/source下的所有rst文件。
也可以参照 [官方文档](http://hyperledger-fabric.readthedocs.io/en/latest) 。

* 我们的目标是把官方文档翻译成中文，让更多的小伙伴了解学习Hyperledger fabric。并在翻译的同时学习理解Hyperledger fabric。

* 有兴趣的小伙伴们，快来加入吧！
## 参与贡献

贡献者 [名单](https://github.com/alvinleee/fabric-doc-cn/graphs/contributors)。

本书源码开源托管在 Github 上，欢迎参与维护：
[github.com/alvinleee/fabric-doc-cn](https://github.com/alvinleee/fabric-doc-cn)

1. GitHub 上 `fork` 到自己的仓库，如 `yourname/fabric-doc-cn`，然后 `clone` 到本地，并设置用户信息。

```sh
$ git clone https://github.com/yourname/fabric-doc-cn.git
$ cd fabric-doc-cn 
$ git config user.name "yourname"
$ git config user.email "your email"
```

2. 更新内容后提交，并推送到自己的仓库。

```sh
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```

3. 在 GitHub 网站上提交 pull request 即可。

4. 建议定期使用项目仓库内容更新自己仓库内容。

   更新过程如下所示：

```sh
$ git remote add upstream https://github.com/alvinleee/fabric-doc-cn
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```


