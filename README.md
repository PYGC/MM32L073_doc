# MM32L073_doc
非官方，将MM32L073官网pdf转换成在线文档

https://docs.mindmotion.studio/zh/latest/

# 步骤

安装 Sphinx
```
pip install sphinx
```

安装 Read the Docs 主题
```
pip install sphinx_rtd_theme
```

新建项目
```
sphinx-quickstart
```

编译生成 html 页面
```
.\make.bat html
```

查看生成页面
```
.\build\html\index.html
```

# 其他功能

编译生成 chm 文档
```
.\make.bat htmlhelp
```

编译生成 latex 文档
```
.\make.bat latex
```

# 教程

http://www.sphinx-doc.org/en/master/

https://zh-sphinx-doc.readthedocs.io/en/latest/index.html