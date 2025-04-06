## language: {language}
> 分析当前项目是否引入了相关语言规范化工具，如模块化方式、预编译语言等

formatter library:
- [tools1（version）]()
- [tools2（version）]()

usable utils and components:
> 给出当前项目中已有的公共方法、组件的目录，并简介作用
```
- pkg // {module name}
	- xxx // {function}
```

coding conventions:
> 代码职能分工明确，路由、业务、工具分开
```
- api 	// 请求路由管理
- views // 业务代码书写
- utils // 工具方法书写
...
```

folder and variable naming conventions:
- 语义化
- 驼峰 | 短横线
- 长度限制

Error monitoring and logging:
> 合理使用debugger、console等调试语句，并做好清除工作
> 适当添加注释，但避免过度注释

