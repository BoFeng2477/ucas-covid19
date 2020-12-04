# ucas-covid19
国科大疫情防控每日填报助手，用于解决忘记填写企业微信中身体状况每日打卡的问题。




# changelog
- 2020年4月15日 添加了随机等待`10-600`秒之后再进行填报
- 2020年4月15日 添加了`user-agent`
- 2020年4月15日 更新了README，添加了设定secrets页面的截图
- 2020年6月12日 更新了README，提醒同学请勿直接在代码中填写密码
- 2020年6月14日 更新了README，添加有关触发action运行的说明
- 2020年6月24日 适配了网站的字段的更新；添加了 debug模式隐藏打卡信息；github action直接输出打卡结果；移除了 serverless 方式的支持
- 2020年9月16日 适配了网站的字段的更新
- 2020年9月26日 更新了README，添加了使用windows计划任务的操作步骤
- 2020年11月3日 更新了README，添加了 MacOS系统中 crontab 的配置方法
- 2020年11月6日 添加了 Telegram Group
- 2020年11月7日 使用环境变量传递口令，解决密码中存在特殊字符导致 sed 截断的问题
- 2020年11月9日 bugfix: 修复环境变量传递口令中存在的 bug， 经过测试已经 work 了，面壁思过中 :( 
- 2020年12月2日 网站证书配置有误导致打卡失败，修改代码为不验证证书


# 致谢
- 感谢 [karuboniru](https://github.com/IanSmith123/ucas-covid19/pull/1) 提供的github actions 支持
- 感谢 [tyfulcrum](https://github.com/IanSmith123/ucas-covid19/pull/2) 对文档的完善工作
- 感谢 [HsimWong](https://github.com/IanSmith123/ucas-covid19/pull/3) 对文档的完善工作
- 感谢 [spwpun](https://github.com/IanSmith123/ucas-covid19/pull/6) 添加了使用 windows 计划任务的操作步骤
- 感谢 [PrimeMHD ](https://github.com/IanSmith123/ucas-covid19/pull/7) 添加了使用 MacOS 的 crontab 的配置步骤

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">知识共享署名-非商业性使用-相同方式共享 3.0 未本地化版本许可协议</a>进行许可。


Les1ie

2020-4-5 23:56:52
