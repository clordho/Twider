# Twider.js

📦 一键使用：输入需要爬取的推特用户名即可下载全部图片和视频到本地，无需登录/开发者账号/浏览器环境/python环境  

💡 与众不同：基于模拟http(s)请求的原生接口数据，没有的冗余html解析过程，代码精简，性能优秀  

🔑 安全无忧：经过大量级测试后未出现接口限制/验证，睡前开启，睡醒收货  

# Usage

### Step 1
```
npm install
```
### Step 2
#### -下载指定用户名的所有推文内容，默认保存至目录./Medias/昵称@用户名/，默认文件名称为${datetime}_(${index})(.jpg|.mp4)
```
npm run download 用户名
```
#### 或
#### -追加更新./Medias目录下的已存在用户的新发布推文内容
```
npm run update
```

# Todo

* 可视化桌面程序（electron）

# License

CC0 1.0 Universal
