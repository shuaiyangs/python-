第一天来认识一个新同学：request
=======================

官方文档中的说明：
>An extensible library for opening URLs using a variety of protocols

>request是Python的urllib中的一个模块用来以各种协议打开URL

## 主要方法

### urlopen
'''Python

from urllib.request import urlopen

URL = 'https://www.baidu.com/'
r = urlopen(URL)#返回一个respond类

'''
