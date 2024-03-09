# 笔记主题

一些可能适合于用 $\LaTeX$ 写的笔记

- 运筹学 Operations Research
- 机器学习与数据分析 Machine Learning and Data Analysis

# 初始化步骤

首先下载 $\LaTeX$ 环境：

```shell
apt update
apt install texlive-full
```

## 下载字体

下载wget工具

```shell
apt-get install wget
```

再利用wget工具下载字体（source: [[LaTeX] 使用Github Codespaces作为在线LaTex编辑器！](https://jeza-chen.com/2022/11/11/Use-Github-Codespaces-As-Online-LaTex-Editor/)

仿宋（FangSong）:

```shell
wget -P /usr/share/fonts/ https://github.com/dolbydu/font/raw/master/unicode/FangSong.ttf
```

宋体（SimSun）：

```shell
wget -P /usr/share/fonts/ https://github.com/dolbydu/font/raw/master/unicode/SimSun.ttc
```

黑体（SimHei）：

```shell
wget -P /usr/share/fonts/ https://github.com/dolbydu/font/raw/master/unicode/SimHei.ttf
```

楷体（KaiTi）：

```shell
wget -P /usr/share/fonts/ https://github.com/dolbydu/font/raw/master/unicode/Kaiti.ttf
```

Times New Roman：

```shell
wget -P /usr/share/fonts/ https://www.freebestfonts.com/yone//down/times.ttf
```

Arial：

```shell
wget -P /usr/share/fonts/ https://raw.githubusercontent.com/matomo-org/travis-scripts/master/fonts/Arial.ttf
```

使用`fc-cache`命令更新字体缓存：

```shell
fc-cache -fv
```