## 前言
华为招聘URL：https://career.huawei.com/socRecruitment/services/portal3/portalnew/getJobList/page/10/1?curPage=1&pageSize=10&jobFamilyCode=&deptCode=&keywords=&searchType=1&orderBy=P_COUNT_DESC&jobType=1

## python知识点
2. 命令行如何退出python环境?
`quit()`函数可以退出
3. __init__函数
需明确的概念点：
- 两个下划线开头的函数是声明该属性为私有，不能在类的外部被使用或访问
- __init__函数（方法）的第一个参数必须为self，后续参数为自己定义
4. 如何安装python第三方库
比如：xlwt、random等三方库，通过`pip install *`会报错。

去[该网站](https://pypi.org/project)搜索xlwt等，下载相应的压缩文件，解压之后，在含有`setup.py`的文件夹下执行下面命令即可
```
python setup.py install
```

