# Conda的channel相关操作

1. 恢复默认源
```
conda config --remove-key channels
```

2. 添加中国大陆源

```
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge/
```

3. 查看当前源
```
conda info
```