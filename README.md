微软积分自动化 microsoft rewards

主要使用库：

selenium==4.4.3
webdriver-manager>=3.8.5
需要安装chrome webdrive 放在main文件或selenium库文件夹下
https://registry.npmmirror.com/binary.html?path=chromedriver/
上面的网址内容不够新
你可以在以下网址查找与你的 Chrome 版本匹配的 ChromeDriver：https://googlechromelabs.github.io/chrome-for-testing/
参考了dalao的项目[charlesbel/Microsoft-Rewards-Farmer: A simple bot that uses selenium to farm Microsoft Rewards written in Python (github.com)](https://github.com/charlesbel/Microsoft-Rewards-Farmer)

由于国内的任务少，且访问加载较慢，就自己写了一个简化版，实现了完成PC和手机搜索任务和点击任务，但程序比较简单，实现思路也比较直白，有很大的改进空间。有兴趣的朋友可以尝试一下。

```json
[
    {
        "username": "",
        "password": ""
    },
    {
        "username": "",
        "password": ""
    },
    {
        "username": "",
        "password": ""
    }
]
```

