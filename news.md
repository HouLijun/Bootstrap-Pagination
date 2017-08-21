## 首页新闻列表
检索最新6条新闻
```javascript
//返回数据
var newsData={
	data:[				
		{id:1,title:"阿凡达航大富豪是否是大法官",releaseTime:"03-14"},
		{id:2,title:"阿凡达航大富豪是否是大法官",releaseTime:"03-14"},
		{id:3,title:"阿凡达航大富豪是否是大法官",releaseTime:"03-14"},
		{id:4,title:"阿凡达航大富豪是否是大法官",releaseTime:"03-14"},
		{id:5,title:"阿凡达航大富豪是否是大法官",releaseTime:"03-14"},
		{id:6,title:"阿凡达航大富豪是否是大法官",releaseTime:"03-14"}
	],
	code:200
}

```

## 新闻列表页
```javascript
url:/getData?pageNum=10&limit=10
pageNum==页码
limit==每页显示数据个数
```
```javascript
//返回数据格式
var data={
	totalCount:98,		//数据总数
	data:[				//某一页的数据10条
		{id:1,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:2,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:3,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:4,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:5,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:6,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:7,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:8,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:9,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
		{id:10,title:"阿凡达航大富豪是否是大法官",releaseTime:"2017-03-14"},
	],
	code:200
}
```

## 新闻详情页
```javascript
url:/getData?id=1
id==单条新闻id
```
```javascript
var data={
	current:{	//返回当前新闻的所有信息
		id:3
		title:"",
		content:"",
		.....
		
	}
	prev:{		//如果没有上一条或下一条时返回空{}
		id:1
		title:"",
	}
	next:{
		id:1
		title:"",
	}
	code:200
}
```