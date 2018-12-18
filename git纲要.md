###git实战笔记
- 对于公司项目在远端仓库没有任何东西的时候，咋们可以通过在本地创建好仓库，然后同步到远程的仓库，此时你可以做的是:

```
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:xiangcman/test.git
git push -u origin master
```
- 如果公司项目已经在远端仓库有代码的时候，此时你可以通过**clone**方式到本地:

```
git clone git@github.com:xiangcman/test.git
```

- 如果远程的仓库中不存在该分支，你此时想要在本地创建好分支后，然后提交到远程的仓库中：



master分支提了点东西
1.dev1提交了点东西
2.dev1提交了点东西，主分支用rebase的形式合并代码
3.dev1提交了点东西，主分支用merge的形式合并代码
4.dev1提交了点东西，主分支用merge的形式合并代码œ
5555555555555
6666666666666
7777777777777
发生冲突的地方

