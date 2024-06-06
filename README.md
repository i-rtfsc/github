# 代码整合

# i-rtfsc github工程合集
repo init -u git@github.com:i-rtfsc/github.git -m default.xml

# mini aosp 清华源(自己常用到的模块)
repo init -u git@github.com:i-rtfsc/github.git -m mini-aosp.xml

> repo init -u https://mirrors.tuna.tsinghua.edu.cn/git/AOSP/platform/manifest -b android-14.0.0_r45 --depth=1
> 把 mini-aosp.xml 拷贝到当前目录
> repo-mini.py

# aosp 清华源
repo init -u git@github.com:i-rtfsc/github.git -m aosp.xml

# mini lineage 清华源(自己常用到的模块)
repo init -u git@github.com:i-rtfsc/github.git -m mini-lineage.xml
