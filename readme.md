# eslint-config-het

## 简介 
就职于和而泰时写的，eslint-config规则，没什么描述的，参考的antd规则，然后放松了一些，不适合我们团队的。

## 作者
"author": "zhcyy  董小yuan  叶超尧 <823499823@qq.com>"

## 注意事项：
下面这条规则，需要根据各自项目的别名，个性化定制：  

	"import/no-unresolved": [
		2, 
		{ "ignore": [
			"^static/", 
			"^flux/", 
			"^config/", 
			"^components/", 
			"^newApi/", 
			"^newAsset/", 
			"^newComponents/", 
			"^newConfig/", 
			"^newReflux/"
		]}
	],