Podbay播客漏洞报告\Podbay Podcast Vulnerability Report

1，漏洞症状:当你搜索自己喜欢的音频想添加在home里，他就会报错Something went wrong! If this error persists, let us know via the Feedback page.

从而无法添加，并且无法浏览订阅音频最新内容，刷新无效

Vulnerability symptoms: When you search for your favorite audio and want to add it to home, it will report an error "Something went wrong! If this error persists, let us know via the Feedback page." This makes it impossible to add it, and it is impossible to browse the latest content of the subscribed audio, and refreshing is invalid

2，漏洞频率：每10至20分钟随机出现，无法正常浏览页面

Vulnerability frequency: Occurs randomly every 10 to 20 minutes, and the page cannot be browsed normally

3，影响：错误发生后页面可能短暂无响应,影响用户体验

Impact: After an error occurs, the page may be temporarily unresponsive, affecting the user experience

4，测试环境： 操作系统：Windows 11，浏览器：Chrome 121

Test environment: Operating system: Windows 11, Browser: Chrome 121

5，复现步骤

(1). 正常浏览podbay（首页或发现页均可）  

(2). 进行常规操作搜索  

(3). 立刻点击add to my podcasts错误会自动出现  

 Steps to reproduce

(1) Browse Podbay normally (home or discovery page)

(2.) Perform a normal search

(3. )Immediately click "Add to my podcasts" and the error message will automatically appear

补充信息:

1，错误似乎与页面动态加载内容有关  

2,这个问题从上周更新后开始出现  

Additional information: 

1. The error seems to be related to the dynamic loading of the page content 

2. This problem started to occur after the update last week

