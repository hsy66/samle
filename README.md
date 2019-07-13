# samle

> 垃圾分类工具后台

### 功能

- 存储openid
- 分类展示接口
- 分类详情接口
- 获取百度token
- AI识别- 
- 搜索接口

### 接口

存储openid `/login`

分类展示接口 `/type`

分类详情接口 `/type/:id`

获取百度token `/image`

AI识别 `/image/serach`

搜索接口 `/goods/search`


### 配置文件

修改`config/index.ts`中微信小程序和百度的`ApiKey`和`AppSecret`


### 运行

```javascript
    npm install || npm run start
    yarn install || yarn start
```

### 浏览器打开

```javascipt
    http://localhost:3000
```
