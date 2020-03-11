# request-funjs


# 快速上手

## 安装

```shell
npm install request-funjs
```

### 全局注册（在main.js文件里注册）

```javascript
import Request from 'request-funjs';
Vue.prototype.Request = Request;
//在这里需要声明一个 host 变量，作为请求的主机名称
Request.host = 'https://www.baidu.com'
```

### 局部注册（在你所使用的vue里注册）

```javascript
import Request from 'request-funjs';
//在这里需要声明一个 host 变量，作为请求的主机名称
Request.host = 'https://www.baidu.com'
```

## 例子

```javascript
Request.Get("api/list",this.params,
	res => {
	   console.log(res);
	},
	err => {
	   console.log(err);
})
```

#### 目录

```javascript
1、get请求 :
	Request.Get

2、post请求 :
	Request.Post

3、批量post :
	Request.PostBatch

4、put请求 :
	Request.Put

5、delete请求 
	Request.Delete

6、批量delete :
	Request.DeleteBatch

7、微信分享 :
	Request.SetShare
```
<img width="180" src="http://crazy-x-lovemysoul-x-vip.img.abc188.com/images/beishang.png" align="left">  
<img  width="180" src="http://crazy-x-lovemysoul-x-vip.img.abc188.com/images/zan.png"  align="left" />
<img  width="180" src="http://crazy-x-lovemysoul-x-vip.img.abc188.com/images/zan.png"  />
