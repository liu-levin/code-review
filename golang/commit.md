

#### 参考链接
- https://stevendxc.github.io/Blog/2015/01/20/git_commit_msg/
- https://zhuanlan.zhihu.com/p/182553920
- 


#### Commit message format
```
 <type>: <subject>
```
注意冒号后面有空格。

##### git commit的 type选择，基本上是使用这7个标识
```
feat：新功能（feature）
fix：修补bug
docs：文档（documentation）
style： 格式（不影响代码运行的变动）
refactor：重构（即不是新增功能，也不是修改bug的代码变动）
test：增加测试
chore：构建过程或辅助工具的变动
```
如果type为feat和fix，则该 commit 将肯定出现在 Change log 之中。

subject是 commit 目的的简短描述，不超过50个字符，且结尾不加句号（.）。



