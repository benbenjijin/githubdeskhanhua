###更新说明
- v3.2.3  (2015-08-18)

	1.优化翻译

	2.修复了关闭最后一个窗口出现错误的 bug


- v3.2.0  (2015-08-17)

	1.增加了部分遗漏翻译

	2.增加了 Setting 部分的汉化,时间匆忙，可能有理解或者翻译错误的地方，请到 [Issues](https://github.com/chinakids/atom-simplified-chinese-menu/issues) 告诉我~十分感谢。部分理解模糊的地方没有翻译...等待测试后再翻译，本次翻译部分参考[微软术语检索](http://www.microsoft.com/Language/zh-cn/Search.aspx),以及感谢好基友岩岩的帮助



- v3.1.6  (2015-08-06)

	优化 mac 下部分翻译，另外做个统计，是否需要汉化第三方插件扩展的菜单 or Setting菜单？有需要的请到 [Issues](https://github.com/chinakids/atom-simplified-chinese-menu/issues) 告诉我~

- v3.1.5  (2015-08-05)

	优化部分翻译，代码完全 coffee 化，修复 bug

- v3.1.0  (2015-07-21)

	优化部分翻译，本地化翻译内容

- v3.0.8  (2015-07-10)

	解决官方1.0.2升级造成的4处汉化失效(设置，打开，打开文件夹，另存为)
	bug 产生 因为官方 menu 中这几处的 label 值中`...`变为了`…`(查证后为官方正常改动，后期均为`…`)
	解决方案：在 main.coffee 中对`…` 确认，替换为`...`，从而兼容后期 atom 官方的更改`...` -> `…`
	目前版本兼容Atom 所有已发布版本，请放心使用，建议所有用户更新