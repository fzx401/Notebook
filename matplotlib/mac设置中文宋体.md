# Mac下设置中文宋体

1. 读取本地matplotlib字体路径
```
import matplotlib

path = matplotlib.matplotlib_fname()
```

2. 将下载的SimSun.ttf移动到上述路径(当前目录已下好)
```
mv ~/Downloads/SimSun.ttf path
```

3. 在finder"用户"目录下shift+command+.开启隐藏目录，删除Fontlist文件

4. 重启Python Kernel