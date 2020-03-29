Forked from  https://github.com/9bie/NSRAC

# NSRAC 自动转存百度网盘
## 如何使用

执行`pip install -r requirements.txt` 安装所需依赖。

之后
```python
import nsrac
baidu = nsrac.BaiduPan(Cookies={
    #如果你有cookies的话，请在这里添加BDUSS,STOKEN和BAIDUID，否则请留空
})

baidu.create_floder("文件夹名字")
baidu.transfer("https://pan.baidu.com/s/xxxxx",code="",path="文件夹名字")
```

## 注意
务必保证js.js和nsrac在同一个目录下

