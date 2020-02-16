## boleming.github.io
bootstrap pc端演示项目：说实话这是我在GitHub中上传的第一个测试项目，也就倒腾了一下基础的git指令。
#### git的基本操作：
> 下载与安装以及基础配置已省略，如需要请查阅https://www.cnblogs.com/sdcs/p/8270029.html
#### git文件的上传:(前提文件上传前必须先建远程GitHub仓库）
1. 切换盘符：
```
cd F:
```
2. 切换具体文件夹路径：
* 注意斜杠方向
```
cd web/vue项目
```
3. 把这个目录变成Git可以管理的仓库
```
git init
```
4. 提交全部文件到git仓库：（不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了）
```
git add .
```
5. 添加文件提交的文字说明：
```
git commit -m "提交文件"
```
6. 关联远程仓库：
```
git remote add origin git@github.com:用户名/项目仓库名.git
```
7. 把本地库的有内容推送到远程仓库：
```
git push -u origin master
```
注：实际上安装后也可以用cmd提交到远程仓库，并且不会生成.git文件夹
