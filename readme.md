## 虚拟环境

```
# 查看当前已存在的虚拟环境
workon

# 选中和退出虚拟环境，vir_name为虚拟环境名称
workon [vir_name]
deactivate

# 创建新的虚拟环境，path为本机python路径
mkvirtualenv [vir_name] -p [path]

# 查看当前已配置的python版本
pyenv version

# 下载和安装新的python版本
wget https://www.python.org/ftp/python/[3.6.5]/Python-[3.6.5].tar.xz -P  ~/.pyenv/cache/

pyenv install [3.6.5] -v


```



## 窗口

```
ctrl + a + c  # 创建一个新窗口
ctrl + a + n  # 显示下一个窗口
ctrl + a + p  # 显示上一个窗口
ctrl + a + d  # 退出会话
```