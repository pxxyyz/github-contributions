# github-contributions

- 一种基于Echart的图表网页，绘制Github的贡献热力图。

- 数据处理的方法是简单而暴力的正则表达式获取`https://github.com/users/#{params['username']}"+ "/contributions`的data-count和data-date。

