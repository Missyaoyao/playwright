# web UI自动化测试
基于Playwright+pytest+poium的UI自动化开源框架

**首先安装本项目所需的依赖库，cmd命令为：pip install -i https://pypi.tuna.tsinghua.edu.cn/simple -r E:\Playwright\requirements.txt
其中：E:\flexoffice路径替换自己项目的磁盘路径。**

----
#### 模块类的设计说明
`data` 用户账号密码

`config` 配置文件，包括：环境配置，运行设置，个人账号配置

`docs` 框架说明

`tools` 公共的工具包

`page_object` 元素对象库

`test_case` 测试用例集

`test_function` 功能函数集

`public` 封装的公共模块,包括:登录登出元素、公共页面按钮统一处理

`test_report` 存放报告

`conftest.py` pytest配置文件，包括：html报告样式

`data.csv` excel存储用户测试数据

`report.css` pytest-html报告的样式文件

`run.py` 定义并执行用例集

`requirements.txt` 项目环境运行所需的第三方库

`pytest.ini` 测试框架的配置文件，制定运行规则

----