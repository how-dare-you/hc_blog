# 首页

- 这里用来输出自己的思考
- 记录自己的想法
- docker 本地预览指令，在项目根目录(有mkdoc.yml文件的目录) cmd 执行；

```cmd
docker run --rm -it -p 8000:8000 -v "%cd%":/docs squidfunk/mkdocs-material
```
- 使用mkdoc远程部署(需要本地安装npm)，目前还是用git action 提交后自动部署；
```cmd
mkdocs gh-deploy --force
```
- obsidian 输入数学公式  $\sqrt{i}$
```latex
$\sqrt{i}$
```