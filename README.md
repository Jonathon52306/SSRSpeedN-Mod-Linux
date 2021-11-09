# SSRSpeedN-Mod
本项目基于项目[youshandefeiyang/SSRSpeedN-Mod](https://github.com/youshandefeiyang/SSRSpeedN-Mod)，砍掉测速功能（频繁测速会给机场其他用户造成巨大的影响），仅输出奈飞解锁检测，几乎不消耗任何流量！<br/>

## Windows 用户请看 [youshandefeiyang/SSRSpeedN-Mod](https://github.com/youshandefeiyang/SSRSpeedN-Mod) 项目

## 运行环境

`
Macbook Pro Intel Version
macOS 11.6
Python 3.9.5
`

由于鄙人用的是 intel 版本的 Macbook ，该项目暂时不支持 Arm 架构 macbook

使用需要一点 python 基础
## 使用步骤
1. 先自行安装 Python3 环境，以及 pip3
2. git clone 本库，或者下载 zip
3. 命令行 cd 到库目录下 执行
```terminal
pip3 install -r requirements.txt
```
4.执行
```terminal

python3 main.py

-u [订阅地址(不含引号，需转义)] (必填)   
-g [自定义测试组名] 
--include-remark [使用关键字通过注释筛选节点] 
--exclude-remark [通过使用关键字的注释排除节点] 
```

[在线转义工具](https://codeplayer.vip/app/string-escape)，输入输出都选择「纯文本」

## 效果预览：
![result](https://raw.githubusercontent.com/chinnsenn/BlogFigureBed/master/blogimg2021-11-08-14-01-39.png)